---
title: "Which APIs and interfaces do I need?"
---

**Which APIs and interfaces do I need?**

This article will explain which API methods I can integrate as a Full MVNO in France.  
This explanations will be based on Transatel’s developers portal, which holds all our API references.

**How can I integrate Transatel’s APIs ?** 

In order to get started on your France Full MVNO, first you can integrate Transatel’s APIs by obtaining access tokens using our [Authentication API](https://developers.transatel.com/docs/guides-authentication/).  
  
The access tokens can be obtained by sending a request using the login and password that were given to you by your Project Manager, during the launch of your MVNO.

**Which APIs should I integrate?**

Once this is done, you can then integrate multiple Transatel APIs.   
  
1. The [Connectivity Management API](https://developers.transatel.com/docs/connectivity-management-overview/):  
The integration of this API will allow you to correctly manage your offer.   
It will allow you, amongst other things, to activate and deactivate your SIMs and eSIMs.  
  
\* [Subscriber management](https://developers.transatel.com/docs/connectivity-management-overview/#subscriber-management): activate/deactive a SIM, modify its rateplan or options, retrieve information about a SIM,…  
  
\* [Portability management](https://developers.transatel.com/docs/connectivity-management-portability-fr/): manage the numbers of your end users.  
  
\* [Event management](https://developers.transatel.com/docs/connectivity-management-events/): generate events related to your subscribers lifecycle and their portability.  
They can then be pushed to your platform by creating webhooks, using our [Webhook API](https://api.transatel.com/webhooks/docs/index.html), that will allow you to send end-user notifications or facilitate your workflow.  
  
2. The [SIM Management API](https://developers.transatel.com/docs/sim-management-overview/):  
   
This API is used for any [information related to your eSIMs](https://api.transatel.com/sim-management/sims/docs/index.html#operation/getEsimDetailsUsingGET), once they’re in an Active state (that you’ll have completed using the [Connectivity Management](https://api.transatel.com/connectivity-management/subscribers/docs/index.html#tag/Subscriber-management/operation/activateUsingPOST) API).   
  
This API enables you to  
\* retrieve the Activation Code, QR Code download link, and status of an eSIM  
\* retrieve the status of the eSIM on the device – it can help your support with troubleshooting  
  
The APIs to “Reserve” and “Release” profiles do not currently apply to this offer.   
  
IMPORTANT: the activation code for the eSIM cannot be downloaded more than once. Your subscriber must make sure they are in an environnement with a stable wifi connexion. After the installation, they’ll be able to deactivate the wifi and use the eSIM data, voice and SMS.  
  
  
3. The [Online Charging System (OCS) API](https://developers.transatel.com/docs/ocs-overview/):  
  
 This will allow you to manage and control the usage of your SIMs in real-time. This API is only available if you have subscribed to the Real-time Data Control option.   
  
4. The [Network API](https://developers.transatel.com/docs/network-overview/), which includes:  
  
– Network attach: gain the history of location updates and the ability to trigger a network detach.   
– Data session: access information on current active data session of your SIMs  
– [SMS-A2P](https://developers.transatel.com/docs/network-guides-send-sms/): send on-net SMS to your subscribers, for example to let them know of a promotional offer.

**Why choose APIs?**

All of Transatel’s offers can be managed via our SIM Management Platform. However, you may want to connect your MVNO SIMs to your own systems (or your BSS).  
  
This will allow you to:  
– centralise all your internal interfaces in one place and using a unique tool  
– automate actions and processes, such as automatically sending an SMS to the end-user when a bundle has been renewed

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
