---
title: "[NEW] Our Standard User Roles"
---

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
