---
title: "SMS-API and A2P SMS"
---

# SMS-API and A2P SMS

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

# SMS-API and A2P SMS

## **What is SMS A2P?**

In the world of IoT, it can be used for many other things, including triggering devices to upload information or to code new configurations into devices.

A2P means “Application to Person”, and this is the concept of the SMS-API. For MVNOs, it means sending messages from your MVNO to the subscriber, to inform them of all sorts of things, such as their bill payment, they have reached a spend cap or they are eligible for a new offer!

## **Can I send SMS to my subscribers?**

Yes, Transatel’s MVNOs can send SMS to their subscriber base using the SMS-API.

Documentation can be found here: <https://developers.transatel.com/docs/network-overview/#sms>

## **How do I automate selfcare?**

On some of Transatel’s offers and services, we automatically generate SMS to subscribers. For example, to tell them that they are in roaming, have used their bundle allowance or have hit their Data Safeguarding threshold.

However, MVNOs can automate SMS messages based on other events. MVNOs can subscribe to webhook events via Transatel’s API suite and use these triggers to send SMS via the API.

## **What is the sender name?**

The sender of the SMS is also called the “originator”. By default, all MVNOs have access to a few generic originators for ***onnet*** A2P SMS:

- 1250 (also used form many of Transatel’s selfcare SMS)
- 65075 (to reply to “info” switching messages)
- 75075 (to reply to “port request” switching requests)
- 85075 (to reply to “switch request” switching requests)
- WelcomeSMS (to provide roaming advice of charge)

You can contact your account manager if you want to if you’re having problems using any of these. They can also help if want to know if any other originators are available for you, or if you would like to declare a new originator.

For ***offnet*** SMS, each originator must be pre-registered (there are no default originators).

## **Can I brand the sender name?**

Indeed, you can have your MVNO name appear as the sender of the SMS sent using the SMS-API. Contact your account manager to find out how.

Please note, originator request must be validated and cannot be guaranteed.

If you request the originator to be a shortcode number, you will need to provide evidence that this shortcode belongs to you.

## **What CDRs are generated?**

You will see a new CDR type generated for SMS sent via the SMS-API. To note:

- AOSO: “A2P Originated SMS to Onnet”
- AOSD: “A2P Originated SMS Delivery Report”
- AOSxx: “A2P Originated SMS to xx” where xx represents the 2-digit ISO code for the country of the SIM that the SMS was sent to. These are for “offnet” SMS.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
