---
title: "Service Provider Connect API integration"
---

This article will explain how to get started with integrating Transatel APIs to manage your Service Provider Connect offer.  
We will summarize all required APIs, with the links on the [Transatel Developer Portal](https://developers.transatel.com/) and API references.   
Please check out [this article](how-to-integrate-our-apis.md) first to learn about our APIs.

Transatel offers many APIs, but you can get started with easily with a few of them.

## Authentification API

Transatel API use  `OAuth 2.0` authentication.

Use the [Authentication](https://developers.transatel.com/docs/guides-authentication/) to get access tokens

Please note that API Credentials are not the same as the SIM Management Portal user credentials.   
The Client ID and secret will be provided by your account manager

## OCS APIs (subscription, catalog, inventory)

These are the main APIs required for the service.  
It will enable you to add the right bundles to your SIMs, retrieve the catalog, and check the inventory.  
  
– [OCS Subscription](https://developers.transatel.com/docs/ocs-guides-subscribe-product/)   
This API will enable you to add the right bundles to your SIMs.  
Important note: you can use 2 types of OrderTypes : “preload” and “subscribe”.  
Service Provider Connect SIM cards & eSIMs are delivered to you in Preactivated status. They will automatically activate at the first network attach. (The lifecycle of Service Provider Connect SIMs is detailed [here](https://docs.transatel.com/services-setup/iot-quick-start-guides/getting-started-with-service-provider-connect/)).  
  
Based on the SIM’s status, here is the recommended OrderType to use:   
– Use the **OrderType “Preload”** on Preactivated SIMs –> the SIM will remain preactivated until it is installed and used by the end-user  
– Use **OrderType “Subscribe”**, on Active SIM cards –> you cannot preload a plan on an active SIM Card.  
**In both cases, the data plan will not start until the SIM is being used in a location covered by the plan.**  
  
  
You can use the examples provided in the [OCS Products API reference](https://api.transatel.com/ocs/subscriptions/docs/index.html#tag/Products) to find payload requests with the different values :

![image](/knowledge-center/assets/image-1.gif)
  
– [OCS Inventory](https://developers.transatel.com/docs/ocs-products/#product-inventory)   
This API allows you to check a SIM’s inventory and remaining balance. Use this API to display the remaining balance of a plan in your own app or interface.  
  
– [OCS Catalog](https://api.transatel.com/ocs/catalog/docs/index.html)  
This API allows you to retrieve all available products in our catalogue.  
Tip: to check bundles by location, we include the locations covered in a bundle in the “tags” field, in ISO-2 format.  
  
– [OCS Events](https://developers.transatel.com/docs/ocs-events/)   
Use this API to receive Webhook events related to the product’s lifecycle (ex: bundle expired…). This is useful to enable notifications for your end-users.

## SIM Management

Important note on SIM/eSIM Management in the Service Provider Connect offer

Our service provides you with your own stock of eSIM profiles to manage.

We do not provide an API to get new profiles on demand, instead you are required to keep your own database of profile and manage your stock.

You can update your stock by:

- importing the [SIM delivery file](../../analytics-reports/report-files/sim-delivery-file.md) provided with each new SIM order
- importing the daily [Subscription report](../../analytics-reports/report-files/subscription-report.md), made available on your SFTP account
- or using our [SIM Search API](https://developers.transatel.com/docs/sim-search-overview/)

How to use the SIM Search API to manage your stock

You can use the SIM Search API to request the list of all SIMs, or SIMs in a specific status – for example preactivated SIMs – or also SIMs from a specific group where you add your new SIMs – for example your “Stock” group.

Please remember that the SIM Search API may have a synchronization delay – for example a SIM may already have changed its status, or been moved to a different group. We recommend that you use the APIs related to each service (Connectivity Management APIs, eSIM API…) and webhooks if you need to retrieve the real-time status of a SIM.

## SIM status and eSIM installation status

There are 2 separate lifecycles to keep track of a SIM/eSIM:

- **The SIM status**

This refers of the **telecom** status of the line. For example, a line needs to be active to work, and a can be suspended to stop traffic.

If a customer decides to no longer use the service, you can terminate the line.  
**In Service Provider Connect offer, we deliver the SIMs in preactivated status, so no action is required on your side to activate them.**

- **The eSIM status**

This status is only for eSIM profiles, and refers to the status of the eSIM profile **on a device**.

For example, an eSIM can be “downloaded”, “installed”, “enabled” or “deleted” from a device

**In the Service Provider Connect offer, we deliver the SIMs in “released” status, so here again no action is required on your side to get them ready for end-users (apart from adding a bundle)**

The 2 lifecycles work in parallel, but to work, the SIM must be in:

- active status,
- enabled on the device

## eSIM Details API

As the eSIMs are ready to be used, the only API useful for the Service Provider Connect offer is the “[Get eSIM details](https://developers.transatel.com/api/sim-management/sims/#tag/eSIM-management/operation/getEsimDetailsUsingGET)” API, that allows you tor retrieve the Activation code / QR code and the installation status on the device

***The APIs to “Reserve” and “Release” profiles do not apply to the Service Provider Connect offer. Your profiles are already reserved and released.***

## Connectivity Management APIs (optional)

[Subscription Management API](https://developers.transatel.com/docs/connectivity-management-overview/)  
As mentioned above, Service Provider Connect SIM cards are preactivated, Therefore *you are not required to integrate our Subscription Management APIs*, to activate the SIM cards. They will automatically activate at the first network attach.  
You can however still integrate them if:  
– you wish to Suspend or Terminate SIMs,  
– you would like to populate information fields such as [Reference](../../sim-management/how-to-group-tag-and-label-your-sims.md) or [Groups](../../sim-management/creating-groups-of-sims.md) to organize your fleet, as these dimensions can be found in our SIM Management Portal  
If you would like access to our Subscription Management APIs, please check with your Account Manager to request access, as we usually do not open by default them for Service Provider Connect customers.

## Service Provider Connect specific API glossary

As the API documentation is generic and does not list offer-specific values, here is everything you need to know:  
  
**mvnoRef**: the name of your SPC account, and starts with “M2MA\_WW\_TSL\_…..”  
You can find it easily in our SIM Management Platform:  
![image](/knowledge-center/assets/image-2.png)
  
**COS:** this refers to the catalog of the offer.  
The value for production accounts is ****WW\_M2MA\_COS\_SPC****  
  
**Payment:** in the Service Provider Connect offer, as you – Transatel’s customer- are paying the bundles to Transatel, the value to input in the subscription requests is “Customer“  
  
**RatePlan**  
This is a value required only if you are planning to use the optional Subscriptions Management API.  
You can find your RatePlan in the SIM Management Plaftorm in Catalogue > Options

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
