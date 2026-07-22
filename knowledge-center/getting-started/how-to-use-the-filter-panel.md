---
title: "Using the filter panel"
---

# Using the filter panel

## Getting Started​

## [Auriga User Management](user-management/README.md)

- [[NEW] Restricted Users](user-management/new-restricted-users.md)
- [[NEW] Managing Users](user-management/new-managing-users.md)
- [[NEW] Creating a new user](user-management/new-creating-a-new-user.md)
- [[NEW] Our Standard User Roles](user-management/new-our-standard-user-roles.md)
- [[NEW] Role-Based User Management](user-management/new-role-based-user-management.md)
- [Modifying a user account](user-management/editing-user-accounts.md)
- [Managing user accounts](user-management/managing-editing-user-accounts.md)
- [Cloning an existing user account](user-management/cloning-an-existing-user-account.md)
- [Deactivating or deleting user accounts](user-management/deactivating-or-deleting-user-accounts.md)
- [User rights](user-management/user-rights.md)
- [Creating user accounts](user-management/creating-user-accounts.md)
- [Understanding user account architecture](user-management/understanding-user-account-architecture.md)

## [SIM Management Platform Basics](home-page-dashboard-menus/README.md)

- [How to download my invoice from Auriga](home-page-dashboard-menus/how-to-download-my-invoice-from-auriga.md)
- [Logging in the interface](home-page-dashboard-menus/how-to-log-into-the-interface.md)
- [Navigating the dashboard page](home-page-dashboard-menus/the-dashboard.md)
- [Using the filter panel](how-to-use-the-filter-panel.md)
- [Configuring fields and columns in the tables](how-to-use-configure-fields-and-columns-in-the-tables.md)

## [IoT Quick Start Guides](iot-quick-start-guides/README.md)

- [Testing all the features of your IoT Demo account](iot-quick-start-guides/testing-all-the-features-of-your-iot-demo-account.md)
- [Getting Started with Service Provider Connect](iot-quick-start-guides/getting-started-with-service-provider-connect.md)
- [Getting Started with IoT Connect](iot-quick-start-guides/getting-started-with-iot-connect.md)
- [Getting Started with Ubigi for Business](iot-quick-start-guides/getting-started-with-mobile-workplace-connect.md)

## [API integration](api-integration/README.md)

- [IoT Connect Capped Plans API Integration](api-integration/iot-connect-capped-plans-api-integration.md)
- [Ubigi eSIM Reseller API Integration Guide](ubigi-esim-reseller-api-integration-guide.md)
- [About the Transatel Developer Console](api-integration/about-the-transatel-developer-console.md)
- [Ubigi for Business API Integration](api-integration/ubigi-for-business-api-integration.md)
- [Roaming Alerts](../services/iot-services/raoming-alerts.md)
- [SMS-API and A2P SMS](api-integration/sms-api-and-a2p-sms.md)
- [IoT Connect API integration](api-integration/iot-connect-api-integration.md)
- [Which APIs and interfaces do I need?](which-apis-and-interfaces-do-i-need-3.md)
- [Which APIs should I integrate?](api-integration/which-apis-and-interfaces-do-i-need-2.md)
- [Which APIs and interfaces do I need?](api-integration/which-apis-and-interfaces-do-i-need.md)
- [Service Provider Connect API integration](api-integration/iot-service-provider-connect-api-integration.md)
- [How to integrate our APIs?](api-integration/how-to-integrate-our-apis.md)

## [Latest coverage updates](iot-latest-coverage-updates/README.md)

- [3G sunset : what do I need to do as an MVNO?](iot-latest-coverage-updates/3g-sunset-what-do-i-need-to-do-as-an-mvno.md)

## [Service Provider Connect](https://docs.transatel.com/getting-started/service-provider-connect/)

- [Service Provider Connect API integration](api-integration/iot-service-provider-connect-api-integration.md)
- [Getting Started with Service Provider Connect](iot-quick-start-guides/getting-started-with-service-provider-connect.md)

## [Ubigi for Business](https://docs.transatel.com/getting-started/ubigi-for-business/)

- [Ubigi for Business API Integration](api-integration/ubigi-for-business-api-integration.md)
- [Getting Started with Ubigi for Business](iot-quick-start-guides/getting-started-with-mobile-workplace-connect.md)

## On this page

# Using the filter panel

## About the filter panel

The filter panel can be used in any screen/menu where you can search through your fleet.  
It is displayed in a panel on the right side of the screen.   
If hidden, you can click on the filter icon to get it displayed again

![image](assets/image-1.png)

And if you wish to hide it to keep all the screen space to display the fields of a table, you can hide it by clicking on the arrows icon.

![image](assets/image-2.png)

Here are the search possibilities at your disposal:

## Advanced Search

This enables you to search with a partial reference (ICCID or MSISDN)

Type \* in front or before of at least 4 characters  
For example: \*123475 for a SIM ending with 123456, or 123456\* for a reference starting with these numbers.

![image](assets/image-3.png)

## Search by usage volume

You can use the filter panel to search for SIMs that made a specific volume in GB, voice or SMS

for example…between 0.5 and 2.3GB

![image](assets/image-4.png)

## Search by last seen date

You can search SIMs by the date they were the last active on the network.

“Last seen date” is when the SIM last made any network event – it can be a network attach, usage…

You can enter dates, or use a pre-defined period in the drop-down list.

![image](assets/image-5.png)

## Search by metadata

You can search by metadata – custom fields, in the filter panel

To learn more about metadata, [click here](../sim-management/metadata-custom-fields.md)

## Search by range

Search by range of ICCID, MSISDN, IMEI… – very useful for SIMs with consecutive references (which is usually the case of SIM orders)  
Click on **range** and enter the 1st and last of the SIMs of your range

![image](assets/image-6.png)

Here is the full list of range filters:

![image](assets/image-7.png)

## CSV upload

You can upload a CSV containing lists of ICCID, MSISDN or serial numbers.  
The file must comply with the following criteria:  
– It must be in .csv format.  
– The first line must contain the type of reference used, for example, ICCID. The subsequent lines must contain your numbers.  
– The types of numbers permitted are: **ICCID, MSISDN, serial number.**  
– The numbers must be between single quotation marks (‘) to prevent data loss with long numbers in case the .csv file is opened in Excel.  
You have the possibility to download the template, which contains an example, to help create your file.  
After that, just drag & drop your file or use the file explorer.

![image](assets/image-8.png)

## Other search criteria

You can also use the following fields – some may not be applicable to your business

![image](assets/image-9.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
