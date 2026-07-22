---
title: "Which APIs and interfaces do I need?"
---

**Which APIs and interfaces do I need?**

****About APIs****

All of Transatel’s offers can be managed via the Auriga Platform. However, you may want to connect your MVNO SIMs to your own systems (or your BSS) to do many things:  
  
–        **Fluidify sales and customer services by using one tool**  
Your teams can manage everything from your internal tools, rather than having to flick between your CRM, Auriga and any other systems you may use. This helps you to keep everything in one central place, and means that there is one truth: the information is fed down from your internal tool into Transatel’s systems (and others).  
  
–        **Automate actions and processes**  
You may want to automatically activate a SIM as soon as it has been received, or send an SMS upon bundle renewal every month.  
  
–        **Billing processes and capping**  
You may offer a bill limit where you turn off different services when the customer’s personal monetary cap has been reached, or to reset services at the beginning of a billing cycle. The customer may decide to upgrade their bundle at any time, which may require several actions across several systems.  
  
What’s more, all of our APIs come with Webhook events – they give you real-time notifications when an action has completed (such as: a provisioning action has finished, a bundle has been purchased or a subscriber has hit their data safeguarding threshold)!

****All of this is possible using Transatel’s APIs! Now which ones do you need…?****

*Recommended* -> this interface is required if you want to integrate into your internal systems  
  
*Optional* -> this interface can help manage extra functionalities, but these can be managed autonomously with Transatel without the intervention from the MVNO  
  
*Extra* -> this interface is only needed in certain cases where MVNOs want to bring a an additional service or functionality, but is otherwise not essential for the general management of the retail offer

****My offer is…****

****PAYM Mobile-Only** or FMC**

*Connectivity Management API* -> recommended  
·        to activate, suspend or terminate SIMs  
·        add or remove different services (such as barrings)  
   
*OCS-API* -> extra  
·        to manage data safeguarding options  
   
*SMS-API* -> extra  
·        send SMS to your subscribers

****PAYM RTCP****

*Connectivity Management API* -> recommended  
·        to activate, suspend or terminate SIMs  
   
*OCS-API* -> recommended  
·        to manage recurring bundles  
·        to manage upgrades  
·        to manage to add-ons  
   
*SMS-API* -> extra  
·        send SMS to your subscribers (certain notifications are managed by Transatel in the RTCP offer)

****PAYM RTCP+****

*Connectivity Management API* -> recommended  
·        to activate, suspend or terminate SIMs  
  
*OCS-API* -> recommended  
·        to create your bundle offering (bundle factory)  
·        to manage recurring bundles  
·        to manage upgrades  
·        to manage to add-ons  
   
*SMS-API* -> extra  
·        send SMS to your subscribers (certain notifications are managed by Transatel in the RTCP+ offer)

****PAYG (Pay-as-you-go)****

*sFTP* -> recommended  
·        to pre-activate your SIMs  
·        to pre-load bundles or credit  
  
*OCS-API* -> recommended  
·        to create your bundle offering (bundle factory)  
·        to manage one-off or recurring bundles  
·        to manage top-ups  
·        to preload bundles  
   
*SMS-API* -> extra  
·        send SMS to your subscribers (selfcare SMS is managed by Transatel in the prepaid offer)  
  
*Connectivity Management API* -> extra  
·        to suspend or terminate SIMs (the SIM lifecycle is automated by Transatel’s prepaid systems)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
