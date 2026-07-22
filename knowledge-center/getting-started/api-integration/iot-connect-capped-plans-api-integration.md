---
title: "IoT Connect Capped Plans API Integration"
---

**Getting started**

This article will explain how to get started with integrating Transatel APIs to manage your **IoT Connect Capped Plans** offer.

If you are on our generic offer IoT Connect, with only pay-per-use or pooled bundles as pricing models, please consult [this article](iot-connect-api-integration.md)

We will summarize all required and recommended APIs, with the links on the [**Transatel Developer Portal**](https://developers.transatel.com/) and API references.  
To start your API integration of our services, [**please read this article first**](README.md).  
It will explain how to get credentials, and where to find the technical values related to your offer in the SIM Management Portal.  
Let’s now go into further details regarding the APIs required to manage our **IoT Connect Capped Plans** SIMs.

**Activating your SIMs**

The SIM’s lifecycle and information are managed with the [**Connectivity Management API**](https://developers.transatel.com/docs/connectivity-management-overview/)  
These APIs are used to:  
– activate SIMs,  
– modify services (called “options”) for your SIMs,  
– suspend or Terminate SIMs,  
– populate information fields such as [**Reference**](../../sim-management/how-to-group-tag-and-label-your-sims.md) or [**Groups**](../../sim-management/creating-groups-of-sims.md) to organize your fleet  
– retrieve the information of the services of a specific SIM

To activate your SIMS, you will find all the required techical labels in the SIM Management Portal, in Catalogue > Options.

You will need:

- the rate plan used for your account  
  If your Account is on our standard plan in Euros, this reference should be  
  **M2MA\_WW\_TSL\_IOTCONNECT\_CAPPED**
- The technical labels for the options you want to configure for the new SIMs.  
  This include choosing between pay-per-use and bundles  
  For example to activate a SIM on bundles pricing model, you will need include the value IOTC\_REF\_BUNDLES for the option “OFFER\_901\_IOT\_CONNECT\_CAP\_PRICING” in your API call.

**How to find your service’s specific options for the API calls?**

All the options’ values can be found in the Catalogue > Options menu of the SIM management platform

![image](/knowledge-center/assets/image-1.png)

There you will be able to find all the technical names of the offer’s options, to include in your API calls.  
If you have multiple rate plans (for example various pooled bundles) available in your contract, you will find them in a drop down list:

![image](/knowledge-center/assets/image-2.png)

Here is an example for one of our generic IoT offers:

![image](/knowledge-center/assets/image-3.png)

**They are the exact values used to create and modify [Service Profiles](../../services/what-is-a-service-profile.md) when using our SIM Management Portal**  
The API call to activate a SIM will contain the exact same information as a Service Profile:  
– the Rate Plan (which is the link to the offer)  
– the value for each option  
  
Note: At the moment Service Profiles cannot be used with APIs, but you can “re-create” any Service Profile configuration with the options using the Connectivity Management APIs.  
  
Some options have multiple choices, and only one can be selected. In our UI, they correspond to the choices in drop-down lists in our SIM Management Portal  
For example, for “Pricing Model”, you must choose between the values for Capped Plans and Pay per Use

![image](/knowledge-center/assets/image-4.png)

Each selection also has a default value – if you do not select one in your call, this is the one that will be implemented. In our SMS example, the default value is to “Enabled”.

Here is an example of an activation call for a SIM that will be on the Bundles pricing model:

![image](/knowledge-center/assets/image-5.png)

Note: If you do not include a specific value for Pricing Model in your SIM activation, the SIM will be configured for the Capped Plans model as default value

**Retrieving the list of SIMs/eSIM**

Use the [**SIM Search API**](https://developers.transatel.com/docs/sim-search-overview/) API to search, filter, sort, and paginate SIM data across your fleet.  
Main Use Cases:  
– Build SIM inventory dashboards  
– Integrate SIM data into customer portals or internal tools  
– Retrieve SIMs by account or group  
– Support customer care and troubleshooting workflows.

In order to keep your interface synchronized, you may want to receive the webhooks related to the SIM’s lifecycle.  
As many actions are asynchronous (ex: it takes a few minutes to activate a SIM after the activation call is sent), you may want to receive events to let you know when a change has been completed.  
The webhooks you can receive are detailed [**here**](https://developers.transatel.com/docs/connectivity-management-events/).

**Adding and managing plans**

To fully manage the plans, you will require the following APIs:  
– [**OCS Subscription**](https://developers.transatel.com/docs/ocs-guides-subscribe-product/)  
This is the main API required for the service.  
It will enable you to add the right data plans to your SIMs.  
  
– [**OCS Inventory**](https://developers.transatel.com/docs/ocs-products/#product-inventory)  
This API allows you to check a SIM’s inventory and remaining balance – of it has plans subscribed, and all their details. Use this API to display the remaining balance of a plan in your own app or interface.  
  
– [**OCS Catalog**](https://api.transatel.com/ocs/catalog/docs/index.html)  
This API allows you to retrieve all available data plans in our catalogue.  
Tip: to check plans by location, we include the locations covered in a bundle in the “tags” field, in ISO-2 format.  
  
– [**OCS Events**](https://developers.transatel.com/docs/ocs-events/)  
These are the Webhook events related to the product’s lifecycle (ex: bundle expired…). This is useful to enable notifications for your end-users, or in your own interface.

**Retrieving the eSIM details**

To retrieve the activation code or QR Code of an eSIM, please use the [**SIM Management API**](https://developers.transatel.com/docs/sim-management-overview/)  
In this set of APIs, you only need and only can use “Get eSIM details”  
This API enables you to  
\* retrieve the Activation Code, QR Code download link, and status of an eSIM  
\* retrieve the status of the eSIM on the device – it can help your support with troubleshooting  
*The APIs to “Reserve” and “Release” profiles do not apply. Your profiles are already reserved and released.*

**Retrieving** **Data usage**

To follow the usage of your SIM cards, you can use:

- the [**OCS Inventory**](https://developers.transatel.com/docs/ocs-products/#product-inventory) – for SIMs using bundles. This API will give all the details on the plans currently subscribed on a SIM, the balance, expiration date…
- the [**Network Usage**](https://developers.transatel.com/docs/network-overview/#network-usage) API – for all SIMs, but especially for SIMS in Pay-per-Use mode. This API will give the aggregate data usage over specific period of time, and can also filter usage by country, date…

**Glossary – API specific values for IoT Connect Capped Plans**

As the API documentation is generic and does not list offer-specific values, here is everything you need to know:  
  
**mvnoRef**: the name of your account, and starts with “M2MA\_WW\_TSL\_…..”  
You can find it easily in our SIM Management Platform:

![image](/knowledge-center/assets/image-6.png)

**COS:**this refers to the catalog of the offer. It is required when requesting the catalog of plans for SIMs in the Capped Plans model  
– the value for production accounts is **WW\_M2MA\_COS\_IOT\_CONNECT**  
  
**Payment:** As you – Transatel’s customer- are paying the bundles to Transatel, the value to input in the subscription requests is “Customer“

![image](/knowledge-center/assets/image-7.png)

**RatePlan**  
This is a value required only if you are planning to use the optional Subscriptions Management API.  
You can find your RatePlan in the SIM Management Plaftorm in Catalogue > Options

The generic rate plan for this offer is **M2MA\_WW\_TSL\_IOTCONNECT\_CAPPED**

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
