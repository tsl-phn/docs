---
title: "IoT Connect API integration"
---

**IoT Connect API integration**

This article will explain how to get started with integrating Transatel APIs to manage your IoT Connect offer.  
We will summarize all required and recommended APIs, with the links on the [Transatel Developer Portal](https://developers.transatel.com/) and API references.

**Which APIs should you integrate?**

Transatel offers many APIs, but you can get started with only a couple of a few calls.  
  
**Required APIs:**  
– [Authentication](https://developers.transatel.com/docs/guides-authentication/)   
Use this API to get access tokens.  
  
– [Connectivity Management API](https://developers.transatel.com/docs/connectivity-management-overview/)  
**These** **are the most important APIs – they include the requests to :**  
– activate SIMs,   
– modify services (called “options”) for your SIMs,   
– suspend or Terminate SIMs,  
– populate information fields such as [Reference](../../sim-management/how-to-group-tag-and-label-your-sims.md) or [Groups](../../sim-management/creating-groups-of-sims.md) to organize your fleet  
– retrieve the information of the services of a specific SIM  
  
***Important Note:** The Pooled bundles and the Pay-per-Use mode of our IoT Connect offers are Rate Plans managed via the Connectivity Management APIs.  
The Services that can be applied to the SIMs are Options that are also managed and modified via the Connectivity Management APIs.*  
For example, here is a call to bar SMS  
It includes the rate plan to identify the offer, then the option to bar all outgoing SMS:  
  
![image](/knowledge-center/assets/image-1.png)
  
– [SIM Search API](https://developers.transatel.com/docs/sim-search-overview/)  
Use this API to search, filter, sort, and paginate SIM data across your fleet.  
Main Use Cases:  
– Build SIM inventory dashboards  
– Integrate SIM data into customer portals or internal tools  
– Retrieve SIMs by account or group  
– Support customer care and troubleshooting workflows.  
  
**Recommended APIs:**– [Network Usage](https://developers.transatel.com/docs/network-overview/#network-usage)  
Use this API to consult the usage made by one or up to 5 SIMs over a period of time.  
You can retrieve network usage in the form of CDRs, or already aggregated for a specific time period.  
Usage can be queried using multiple parameters, including:  
– Usage interval (hourly, daily, monthly)  
– Desired breakdown (by APN, country, or radio access type)  
– Date  
– Country of origin  
– IP address (recommended only for SIMs using a Fixed IP)  
– MCC / MNC  
– Service outcome  
  
– [Webhooks](https://developers.transatel.com/docs/webhooks/)  
Use this API to register an endpoint to receive *webhook events*.  
As many actions are asynchronous (ex: it takes a few minutes to activate a SIM after the activation call is sent), you may want to receive events to let you know when a change has been completed.  
For IoT Connect, the main events are the ones related to Connectivity Management   
The webhooks you can receive are detailed [here](https://developers.transatel.com/docs/connectivity-management-events/).   
  
**Optional APIs**   
  
– **if you are using consumer eSIMs**, you may wish to integrate our [SIM Management API](https://developers.transatel.com/docs/sim-management-overview/)   
In this set of APIs, you should only need “Get eSIM details”  
This API enables you to  
\* retrieve the Activation Code, QR Code download link, and status of an eSIM  
\* retrieve the status of the eSIM on the device – it can help your support with troubleshooting  
*The APIs to “Reserve” and “Release” profiles do not apply to the IoT Connect offer. Your profiles are already reserved and released.*   
  
– [Diagnostic APIs](https://developers.transatel.com/docs/network-overview/)  
If you want to integrate our Network Attach APIs or Data Session API to replicate the features of our portal, you can check our Network APIs.  
**Please note that these APIs are for unitary checks only – they should not, and cannot be used to request the details on your whole fleet in an automated way.**  
To prevent this, we have implemented a higher rate limit on these APIs.   
  
Regarding OCS APIs  
**Our generic IoT Connect offers do not use the Online Charging System (OCS) – Therefore all OCS APIs are not compatible and cannot be used.**

****How to find your service’s specific options for the API calls**?** 

All the options’ values can be found in the Catalogue > Options menu of the SIM management platform  
![image](/knowledge-center/assets/image-2.png)
  
There you will be able to find all the technical names of the offer’s options, to include in your API calls.  
If you have multiple rate plans (for example various pooled bundles) available in your contract, you will find them in a drop down list:  
  
![image](/knowledge-center/assets/image-3.png)
  
Here is an example for one of our generic IoT offers:  
![image](/knowledge-center/assets/image-4.png)
**They are the exact values used to create and modify [Service Profiles](../../services/what-is-a-service-profile.md) when using our SIM Management Portal**  
The API call to activate a SIM will contain the exact same information as a Service Profile:  
– the Rate Plan (which is the link to the offer)  
– the value for each option  
  
Note: At the moment Service Profiles cannot be used with APIs, but you can “re-create” any Service Profile configuration with the options using the Connectivity Management APIs.  
  
Some options have multiple choices, and only one can be selected. In our UI, they correspond to the choices in drop-down lists in our SIM Management Portal  
For example, for “Outgoing SMS”, you can select: “Enabled”, “Disabled” or “Enabled for on-net SMS only”:  
![image](/knowledge-center/assets/image-5.png)
  
Each selection also has a default value – if you do not select one in your call, this is the one that will be implemented. In our SMS example, the default value is to “Enabled”.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
