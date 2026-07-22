---
title: "[New] Role-Based User Management"
---

# [New] Role-Based User Management

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

# [New] Role-Based User Management

Starting in April 2026, we are migrating all SIM Management user to our new Role-Based User Management System.

This article is related to the new system. If your account’s users have not yet been migrated, please refer to the articlers concerning the [old user management system](managing-editing-user-accounts.md)

## Role-based user management (RBUM)

Role-based user management (RBUM) is a system for controlling user access to resources within a network or software application based on the roles assigned to individual users. In this system:

- **Roles** are predefined sets of permissions that define what actions a user can perform and what resources they can access.
- **Users** are assigned one or more roles depending on their responsibilities and needs.
- **Permissions** associated with each role dictate the specific actions and access rights granted to the users.

For example:

- The Customer Care  role includes the permissions required to consult SIM details and perform unitary actions on a line
- The Fleet Manager role includes all the same permissions as the Customer Care, so they can perform unitary actions, but this role also includes permissions to perform bulk actions

## Roles per user and roles per business entity

RBUM simplifies administration by allowing administrators to manage permissions by role rather than individual user, ensuring consistent and scalable access control.

- an user can only be associated **with multiple roles**.
- It is possible for a user to have different role  depending on the business entity

**A business entity can be your account, a group within the account, or a Master Account**

For example, if your account has groups to identify the SIMs of your customers an user can be read only” for the whole account, but “Fleet Manager” for the group of Customer B, that they are responsible for.

## About the roles

**Standard roles** are created and maintained by Transatel, and are constantly updated with new features developed by Transatel.

**Custom roles**  are created by the customer’s admin and are not updated with new features developed by Transatel.

Custom roles are an option. They are created on customer request, please contact your Account Manager for more information.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
