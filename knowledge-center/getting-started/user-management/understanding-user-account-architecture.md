---
title: "Understanding user account architecture"
---

# Understanding user account architecture

## Getting Started​

## [Auriga User Management](README.md)

- [[NEW] Restricted Users](new-restricted-users.md)
- [[NEW] Managing Users](new-managing-users.md)
- [[NEW] Creating a new user](new-creating-a-new-user.md)
- [[NEW] Our Standard User Roles](new-our-standard-user-roles.md)
- [[NEW] Role-Based User Management](new-role-based-user-management.md)
- [Modifying a user account](editing-user-accounts.md)
- [Managing user accounts](managing-editing-user-accounts.md)
- [Cloning an existing user account](cloning-an-existing-user-account.md)
- [Deactivating or deleting user accounts](deactivating-or-deleting-user-accounts.md)
- [User rights](user-rights.md)
- [Creating user accounts](creating-user-accounts.md)
- [Understanding user account architecture](understanding-user-account-architecture.md)

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

## [API integration](../api-integration/README.md)

- [IoT Connect Capped Plans API Integration](../api-integration/iot-connect-capped-plans-api-integration.md)
- [Ubigi eSIM Reseller API Integration Guide](../ubigi-esim-reseller-api-integration-guide.md)
- [About the Transatel Developer Console](../api-integration/about-the-transatel-developer-console.md)
- [Ubigi for Business API Integration](../api-integration/ubigi-for-business-api-integration.md)
- [Roaming Alerts](../../services/iot-services/raoming-alerts.md)
- [SMS-API and A2P SMS](../api-integration/sms-api-and-a2p-sms.md)
- [IoT Connect API integration](../api-integration/iot-connect-api-integration.md)
- [Which APIs and interfaces do I need?](../which-apis-and-interfaces-do-i-need-3.md)
- [Which APIs should I integrate?](../api-integration/which-apis-and-interfaces-do-i-need-2.md)
- [Which APIs and interfaces do I need?](../api-integration/which-apis-and-interfaces-do-i-need.md)
- [Service Provider Connect API integration](../api-integration/iot-service-provider-connect-api-integration.md)
- [How to integrate our APIs?](../api-integration/how-to-integrate-our-apis.md)

## [Latest coverage updates](../iot-latest-coverage-updates/README.md)

- [3G sunset : what do I need to do as an MVNO?](../iot-latest-coverage-updates/3g-sunset-what-do-i-need-to-do-as-an-mvno.md)

## [Service Provider Connect](https://docs.transatel.com/getting-started/service-provider-connect/)

- [Service Provider Connect API integration](../api-integration/iot-service-provider-connect-api-integration.md)
- [Getting Started with Service Provider Connect](../iot-quick-start-guides/getting-started-with-service-provider-connect.md)

## [Ubigi for Business](https://docs.transatel.com/getting-started/ubigi-for-business/)

- [Ubigi for Business API Integration](../api-integration/ubigi-for-business-api-integration.md)
- [Getting Started with Ubigi for Business](../iot-quick-start-guides/getting-started-with-mobile-workplace-connect.md)

## On this page

# Understanding user account architecture

**Understanding user account architecture**

User accounts in our interface are based on 3 foundations:  
– which **customer account** they can access  
– which **scopes** the user has  
– which **rights** the user has  
  
Let’s see how this works  
– A **Customer Account** is a fleet of SIM – most of our customers only have one, but some, requiring services on very different technical frameworks, have multiple accounts.   
  
– A **Scope** – the user at least needs ROLE\_USER for the account to work  
  
– Finally, a **Right** is the access to a minor feature or action. For example Activating a SIM card.  
There are many rights, as we let you decide exactly what each user should or should not be able to do.  
This is why critical actions such as terminating a SIM card (an action that cannot be reversed) is a separate from other rights, so that only the right people in your organization have this power.  
For further details on user rights, [click here](https://docs.transatel.com/user-management/user-rights/).  
  
To sum thing up, to be able to perform an action on a SIM, the user account must have:  
– access to the customer account of the SIM  
– at least one scope  
– the right to which the action corresponds  
  
Let’s take the example of activating SIM cards in bulk.  
The user who wants to perform an activation in bulk will require a user account with:  
– access to the customer accounts the SIMs belong to  
– the USER scope  
– the specific right to manage SIMs in bulk

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
