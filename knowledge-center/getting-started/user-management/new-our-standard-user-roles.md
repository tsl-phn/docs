---
title: "[NEW] Our Standard User Roles"
---

# [NEW] Our Standard User Roles

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

# [NEW] Our Standard User Roles

Starting in April 2026, we are migrating all SIM Management user to our new Role-Based User Management System.

This article is related to the new system. If your account’s users have not yet been migrated, please refer to the articlers concerning the [old user management system](managing-editing-user-accounts.md)

This article details the Standard User Roles available in our SIM Management Portal

You will see that certain roles have “Group” version and an **Restricted** “Account” version:

![image](/knowledge-center/assets/image-1.png)

If you choose Account, the role will be applied to the whole account.

If you select the Restricted “Group” version, you will have the possibility to select groups in the account to which this role will apply – instead of the whole account.

## Read-only

|  |  |
| --- | --- |
| Can do | Cannot do |
| Has read-only access to all relevant subscriber, and fleet information, including SIM details, diagnostics, usage information, analytics, and file reports. | Cannot perform provisioning actions or modifications. Nor access financial information such as invoices and billing reports. |

This Role is meant for : Auditors, basic users who need visibility only.

## Customer Care

|  |  |
| --- | --- |
| Can do | Cannot do |
| Can access SIM details, diagnostics, usage information, and analytics and file reports.Authorized to perform individual provisioning actions (activate, suspend, terminate, modify) and manage bundles for a single subscriber. | Cannot access financial data (invoices, billing reports).Cannot perform bulk provisioning actions. |

This role is meant for : Call center agents, helpdesk staff.

## Fleet Manager

|  |  |
| --- | --- |
| Can do | Cannot do |
| Can access SIM details, diagnostics, usage information, analytics, and file reports.Authorized to perform bulk provisioning actions (activate, suspend, modify, terminate lines), manage bundles, options, groups, and service profiles for the whole fleet.Can manage automation rules. | Cannot access financial data (invoices, billing reports).Cannot manage or create users. |

This role is meant for: Account managers, fleet managers.

## Finance Manager

|  |  |
| --- | --- |
| Can do | Cannot do |
| Has read-only access to the fleetCan consult financial information such as invoices and billing reports, as well as finance-related reports and validate SIM orders. | Cannot perform any modification (unitary or bulk) on the fleet |

This role is meant for : Accounting, finance department staff

## Developer

|  |  |
| --- | --- |
| Can do | Cannot do |
| Can use technical tools and the Developer Console for integration, API testing, and monitoring the provisioning lifecycle.Has read-only access to the fleet and options catalog for Transatel Connectivity Management API integration | Limited access to other management functions. |

This role is meant for : IT staff, technical integrators.

## Admin

|  |
| --- |
| Can do |
| Has the highest level of permissions, combining all capabilities from Fleet Manager, Finance Manager, Customer Care, Developer, and Read Only roles.The Admin can view and manage all SIMs, account, and fleet data; perform bulk and individual provisioning actions; access financial reports and invoices; manage automation rules and analytics; and use all technical tools.Additionally, the Admin can create and manage users, configure advanced system settings, and access internal-only features. |

This role is meant for : Fleet administrators, super-users responsible for setup, configuration, and management.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
