---
title: "Which APIs and interfaces do I need?"
---

# Which APIs and interfaces do I need?

## Getting Started​

## [Auriga User Management](../user-management/README.md)

- [[NEW] Restricted Users](../user-management/new-restricted-users.md)
- [[NEW] Managing Users](../user-management/new-managing-users.md)
- [[NEW] Creating a new user](../user-management/new-creating-a-new-user.md)
- [[NEW] Our Standard User Roles](../user-management/new-our-standard-user-roles.md)
- [[NEW] Role-Based User Management](../user-management/new-role-based-user-management.md)
- [Modifying a user account](../user-management/editing-user-accounts.md)
- [Managing user accounts](../user-management/managing-editing-user-accounts.md)
- [Cloning an existing user account](../user-management/cloning-an-existing-user-account.md)
- [Deactivating or deleting user accounts](../user-management/deactivating-or-deleting-user-accounts.md)
- [User rights](../user-management/user-rights.md)
- [Creating user accounts](../user-management/creating-user-accounts.md)
- [Understanding user account architecture](../user-management/understanding-user-account-architecture.md)

## [SIM Management Platform Basics](../home-page-dashboard-menus/README.md)

- [How to download my invoice from Auriga](../home-page-dashboard-menus/how-to-download-my-invoice-from-auriga.md)
- [Logging in the interface](../home-page-dashboard-menus/how-to-log-into-the-interface.md)
- [Navigating the dashboard page](../home-page-dashboard-menus/the-dashboard.md)
- [Using the filter panel](../how-to-use-the-filter-panel.md)
- [Configuring fields and columns in the tables](../how-to-use-configure-fields-and-columns-in-the-tables.md)

## [IoT Quick Start Guides](../iot-quick-start-guides/README.md)

- [Testing all the features of your IoT Demo account](../iot-quick-start-guides/testing-all-the-features-of-your-iot-demo-account.md)
- [Getting Started with Service Provider Connect](../iot-quick-start-guides/getting-started-with-service-provider-connect.md)
- [Getting Started with IoT Connect](../iot-quick-start-guides/getting-started-with-iot-connect.md)
- [Getting Started with Ubigi for Business](../iot-quick-start-guides/getting-started-with-mobile-workplace-connect.md)

## [API integration](README.md)

- [IoT Connect Capped Plans API Integration](iot-connect-capped-plans-api-integration.md)
- [Ubigi eSIM Reseller API Integration Guide](../ubigi-esim-reseller-api-integration-guide.md)
- [About the Transatel Developer Console](about-the-transatel-developer-console.md)
- [Ubigi for Business API Integration](ubigi-for-business-api-integration.md)
- [Roaming Alerts](../../services/iot-services/raoming-alerts.md)
- [SMS-API and A2P SMS](sms-api-and-a2p-sms.md)
- [IoT Connect API integration](iot-connect-api-integration.md)
- [Which APIs and interfaces do I need?](../which-apis-and-interfaces-do-i-need-3.md)
- [Which APIs should I integrate?](which-apis-and-interfaces-do-i-need-2.md)
- [Which APIs and interfaces do I need?](which-apis-and-interfaces-do-i-need.md)
- [Service Provider Connect API integration](iot-service-provider-connect-api-integration.md)
- [How to integrate our APIs?](how-to-integrate-our-apis.md)

## [Latest coverage updates](../iot-latest-coverage-updates/README.md)

- [3G sunset : what do I need to do as an MVNO?](../iot-latest-coverage-updates/3g-sunset-what-do-i-need-to-do-as-an-mvno.md)

## [Service Provider Connect](https://docs.transatel.com/getting-started/service-provider-connect/)

- [Service Provider Connect API integration](iot-service-provider-connect-api-integration.md)
- [Getting Started with Service Provider Connect](../iot-quick-start-guides/getting-started-with-service-provider-connect.md)

## [Ubigi for Business](https://docs.transatel.com/getting-started/ubigi-for-business/)

- [Ubigi for Business API Integration](ubigi-for-business-api-integration.md)
- [Getting Started with Ubigi for Business](../iot-quick-start-guides/getting-started-with-mobile-workplace-connect.md)

## On this page

# Which APIs and interfaces do I need?

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
