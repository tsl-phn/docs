---
title: "Roaming Alerts"
---

# Roaming Alerts

## Getting Started​

## [Auriga User Management](../../getting-started/user-management/README.md)

- [[NEW] Restricted Users](../../getting-started/user-management/new-restricted-users.md)
- [[NEW] Managing Users](../../getting-started/user-management/new-managing-users.md)
- [[NEW] Creating a new user](../../getting-started/user-management/new-creating-a-new-user.md)
- [[NEW] Our Standard User Roles](../../getting-started/user-management/new-our-standard-user-roles.md)
- [[NEW] Role-Based User Management](../../getting-started/user-management/new-role-based-user-management.md)
- [Modifying a user account](../../getting-started/user-management/editing-user-accounts.md)
- [Managing user accounts](../../getting-started/user-management/managing-editing-user-accounts.md)
- [Cloning an existing user account](../../getting-started/user-management/cloning-an-existing-user-account.md)
- [Deactivating or deleting user accounts](../../getting-started/user-management/deactivating-or-deleting-user-accounts.md)
- [User rights](../../getting-started/user-management/user-rights.md)
- [Creating user accounts](../../getting-started/user-management/creating-user-accounts.md)
- [Understanding user account architecture](../../getting-started/user-management/understanding-user-account-architecture.md)

## [SIM Management Platform Basics](../../getting-started/home-page-dashboard-menus/README.md)

- [How to download my invoice from Auriga](../../getting-started/home-page-dashboard-menus/how-to-download-my-invoice-from-auriga.md)
- [Logging in the interface](../../getting-started/home-page-dashboard-menus/how-to-log-into-the-interface.md)
- [Navigating the dashboard page](../../getting-started/home-page-dashboard-menus/the-dashboard.md)
- [Using the filter panel](../../getting-started/how-to-use-the-filter-panel.md)
- [Configuring fields and columns in the tables](../../getting-started/how-to-use-configure-fields-and-columns-in-the-tables.md)

## [IoT Quick Start Guides](../../getting-started/iot-quick-start-guides/README.md)

- [Testing all the features of your IoT Demo account](../../getting-started/iot-quick-start-guides/testing-all-the-features-of-your-iot-demo-account.md)
- [Getting Started with Service Provider Connect](../../getting-started/iot-quick-start-guides/getting-started-with-service-provider-connect.md)
- [Getting Started with IoT Connect](../../getting-started/iot-quick-start-guides/getting-started-with-iot-connect.md)
- [Getting Started with Ubigi for Business](../../getting-started/iot-quick-start-guides/getting-started-with-mobile-workplace-connect.md)

## [API integration](../../getting-started/api-integration/README.md)

- [IoT Connect Capped Plans API Integration](../../getting-started/api-integration/iot-connect-capped-plans-api-integration.md)
- [Ubigi eSIM Reseller API Integration Guide](../../getting-started/ubigi-esim-reseller-api-integration-guide.md)
- [About the Transatel Developer Console](../../getting-started/api-integration/about-the-transatel-developer-console.md)
- [Ubigi for Business API Integration](../../getting-started/api-integration/ubigi-for-business-api-integration.md)
- [Roaming Alerts](raoming-alerts.md)
- [SMS-API and A2P SMS](../../getting-started/api-integration/sms-api-and-a2p-sms.md)
- [IoT Connect API integration](../../getting-started/api-integration/iot-connect-api-integration.md)
- [Which APIs and interfaces do I need?](../../getting-started/which-apis-and-interfaces-do-i-need-3.md)
- [Which APIs should I integrate?](../../getting-started/api-integration/which-apis-and-interfaces-do-i-need-2.md)
- [Which APIs and interfaces do I need?](../../getting-started/api-integration/which-apis-and-interfaces-do-i-need.md)
- [Service Provider Connect API integration](../../getting-started/api-integration/iot-service-provider-connect-api-integration.md)
- [How to integrate our APIs?](../../getting-started/api-integration/how-to-integrate-our-apis.md)

## [Latest coverage updates](../../getting-started/iot-latest-coverage-updates/README.md)

- [3G sunset : what do I need to do as an MVNO?](../../getting-started/iot-latest-coverage-updates/3g-sunset-what-do-i-need-to-do-as-an-mvno.md)

## [Service Provider Connect](https://docs.transatel.com/getting-started/service-provider-connect/)

- [Service Provider Connect API integration](../../getting-started/api-integration/iot-service-provider-connect-api-integration.md)
- [Getting Started with Service Provider Connect](../../getting-started/iot-quick-start-guides/getting-started-with-service-provider-connect.md)

## [Ubigi for Business](https://docs.transatel.com/getting-started/ubigi-for-business/)

- [Ubigi for Business API Integration](../../getting-started/api-integration/ubigi-for-business-api-integration.md)
- [Getting Started with Ubigi for Business](../../getting-started/iot-quick-start-guides/getting-started-with-mobile-workplace-connect.md)

## On this page

# Roaming Alerts

## What are roaming alerts?

When a subscriber roams onto a foreign network, they will automatically receive an SMS informing them that they are roaming and charges may be incurred. Furthermore, MVNOs should complete this alert by sending the subscriber complementary information, such as which allowances are available on their current plan, what charges they can expect, and whether any roaming plans are available to them. A webhook is provided by Transatel when the first SMS is sent so that the MVNO is triggered to send the complementary information.

More information can be found here: <https://www.ofcom.org.uk/phones-and-broadband/bills-and-charges/new-roaming-alerts-for-uk-holidaymakers>

## What is the content of the SMS automatically sent to subscribers?

**Inside EU**

*“You are currently roaming. Mobile calls, SMS and data may be chargeable.*

*Call 789 from your mobile for free for more information on roaming, monitoring your usage and spend, and how to avoid unexpected charges.*

*You can manage* *your* *spend by setting or amending a mobile spend cap. To do this, dial 789 from your mobile for free.”*

**Outside EU**

*“You are currently roaming. Mobile calls, SMS and data may be chargeable and may be expensive.*

*Call 789 from your mobile for free for more information on roaming, monitoring your usage and spend, and how to avoid unexpected charges.*

*You can manage* *your* *spend by setting or amending a mobile spend cap. To do this, dial 789 from your mobile for free.”*

**Russia**: temporary warning message

Due to recent restrictions put into place by the Russian government, data and SMS will be barred for the first 24 hours upon network attach. If no activity is detected, the bar will be reinstated. Voice calls are not affected. Until futher notice, subscribers will receive an additional message:

*“Due to changes introduced by Russian mobile networks, there will be an automatic 24-hour bar on mobile data and SMS upon first connection. The bar lifts automatically after 24 hours provided there is subsequent activity within three days of the unbar. The 24-hour bar is reapplied If there is no activity. Voice calls remain unaffected. These restrictions are implemented by the Russian networks and cannot be overridden by your provider.”*

It is **not** recommended for Subscribers to switch networks, as this will start the process again with the subsequent Russian operator.

## How do I send complementary information to a subscriber?

1. Subscribe to the roaming alert Webhook: <https://developers.transatel.com/api/connectivity-management/events/#tag/Subscribers/paths/CONNECTIVITY-MANAGEMENT~1SUBSCRIBER~1ROAMING~1ALERT/post>
2. Compose the complementary information
3. Send the complementary information via Transatel’s SMS-API: <https://developers.transatel.com/docs/network-guides-send-sms/>

Transatel whitelists the on-net originator “WelcomeSMS” for all of its MVNOs. Use this originator to prove legitimacy and so that the subscriber receives both roaming alerts from the same sender.

## How to check if a Welcome SMS has been sent/received?

You can check if a welcome SMS has been sent to the Subscriber in Auriga under the *Voice & SMS Usage* tab. The *Roaming Alert* is sent from the sender (ANumber) **44WelcomeSMS**.

![image](/knowledge-center/assets/image-1.png)

## How to opt out a Subscriber from Welcome SMS?

If a Subscriber no longer wishes to receive roaming alerts, they can be opted out via API or Auriga (under the Configured Services tab, Roaming Service Options):

![image](/knowledge-center/assets/image-2.png)

If the option is enabled: the Advice of Charge/roaming alert message is barred (blocked) and will not be sent to the subscriber. In the above image, the bar is disabled (grey) and the messages are sent.

## Disclaimer

*This article does not constitute as legal advice. Transatel makes the above tools and information available to the MVNO, it is up to the MVNO to ensure compliancy and make their own decisions on how to comply with Ofcom regulation.*

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
