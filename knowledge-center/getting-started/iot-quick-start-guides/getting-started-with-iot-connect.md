---
title: "Getting Started with IoT Connect"
---

# Getting Started with IoT Connect

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

## [IoT Quick Start Guides](README.md)

- [Testing all the features of your IoT Demo account](testing-all-the-features-of-your-iot-demo-account.md)
- [Getting Started with Service Provider Connect](getting-started-with-service-provider-connect.md)
- [Getting Started with IoT Connect](getting-started-with-iot-connect.md)
- [Getting Started with Ubigi for Business](getting-started-with-mobile-workplace-connect.md)

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
- [Getting Started with Service Provider Connect](getting-started-with-service-provider-connect.md)

## [Ubigi for Business](https://docs.transatel.com/getting-started/ubigi-for-business/)

- [Ubigi for Business API Integration](../api-integration/ubigi-for-business-api-integration.md)
- [Getting Started with Ubigi for Business](getting-started-with-mobile-workplace-connect.md)

## On this page

# Getting Started with IoT Connect

This page contains the Quick Start Guide to our IoT Connect service.  
  
In this Quick Start Guide you will learn:  
1) What are the SIM statuses of a SIM’s lifecycle  
2) What are Service Profiles  
3) How to create your first Service Profile  
4) Activating your first SIM cards – unitarily or in bulk  
5) How to set up your IoT Connect SIM in the device

## 1) What are the statuses of a SIM’s lifecycle?

![image](assets/image-1.png)

## 2) Service Profiles

A Service Profile is a configuration that will be applied to your SIMs to:  
– Define the Service Pack & Rate Plan to be used  
– Allow or deny certain types of usages, select services…  
– Set usage limits & decide what should happen if they’re reached  
  
To activate a SIM card, you must select a Service Profile but you can change the profile during the SIM’s lifecycle.

**For IoT customers, to activate a SIM card in the interface, you must select a Service Profile – but you can change the Prfile during the SIM’s lifecycle.**

**All you must know regarding the modification Service Profiles, Rate plans or options:**  
• You can change the connectivity services of the Service Profile anytime, and it will apply to all the SIMs using this profile (ie: allow or bar SMS… )  
• The rate plan and Service Pack of a Service Profile cannot be changed. If you want to change the rate plan or Service Pack of your SIM, you must apply another Service Profile  
• When switching a SIM card to a Service Profile with a different Rate Plan, the connectivity settings and options of the new Profile will be applied immediately (ie data enabled, SMS disabled), but the rate plan change will only be effective the following month.

## 3) How to create a Service Profile ?

Go to Catalogue > Service Profile

![image](assets/image-2.png)

click on the button at the top on the right “Create a profile”

![image](assets/image-3.png)

In the new window, to create a Service Profile, you’ll need to:  
– choose a name (it has to be unique to your account)  
– select the **Service Pack**  
– select the **Rate Plan**  
For most customers, your account probably has a single service and a single rate plan to choose from.  
  
Once you have selected a Service pack, the options and services you can configure will be displayed below.  
The options that appear are the ones that are available for your contract. Here is an example for one of our standard IoT offers. Customers of our MVNO offers will see very different options.

![image](assets/image-4.png)

Once you have selected the required options, click on **Create**.  
That’s it!  
  
**Tip!**  
You can assign High Usage Rules to a Service Profile.  
To learn how to create and set up rules, [click here](../../services/how-to-create-manage-high-usage-alerts-in-our-sim-management-platform.md).

## 3) Activating your SIMS

Now that you have a Service Profile, you can activate SIM cards, either unitarily, or in bulk.  
  
**Activating a Single SIM card**  
  
To be activated, a SIM card must be in available or preactivated status.  
  
1. Go to the SIM card’s page and click on the **Activate**button at the top right of the screen

![image](assets/image-5.png)

2. Select the **[Service Profile](https://docs.transatel.com/services-setup/what-is-a-service-profile/) to apply to the SIM** and click on **Next**

![image](assets/image-6.png)

3 & 4. (Optional Steps) Add a [**reference**, **line & subscriber details**](../../sim-management/how-to-group-tag-and-label-your-sims.md), and add the SIM to a **group**  
The next steps are optional – at this point you can already activate the SIM.  
But if you wish, you can go through the last steps, where you can enter a reference, add the SIM to a group, and add line details.

![image](assets/image-7.png)

You can now launch the activation order.  
SIM card activations are processed extremely quickly for IoT customers.  
  
**Activating SIMs in bulk**  
  
1. Go to **All Assets > Activate in Bulk**

![image](assets/image-8.png)

2. **Select the SIMs** to activate.  
The list of all your SIMs in available status will be displayed.  
You can use the fields of search panel to find specific SIMs, upload a list of SIMs with a CSV file, or search for SIMs with consecutive IDs with the range search.  
For further details on the possibilities of the search panel, [check this article](https://docs.transatel.com/getting-started/groups-filters/how-to-use-the-filter-panel/).  
Check the boxes of the SIMs and click on next.

![image](assets/image-9.png)

3. Select the **Service Profile to apply to the SIM**

![image](assets/image-10.png)

4. (Optional Step) Add a **reference**, and add the SIMs to a **group**  
This step is optional – at this point you can already launch the activation request.  
But if you wish, you can go through the last steps, where you can enter a reference (the same reference will be applied to all the SIMs), add the SIMs to a group.

![image](assets/image-11.png)

**You can now launch the activation order.**  
SIM card activations are processed extremely quickly for IoT customers.

![image](assets/image-12.png)

## 5) Device Setup

**First, make sure that the SIM is active!, if not, go back to step 4!**  
If you are using consumer device under iOS, Android or Windows, the OS should apply the settings automatically.  
  
If not, or for industrial devices, proceed as follows:  
  
1.**Allow roaming connectivity**  
2. **Set APN (Access Point Name) settings:**  
Enter our generic APN ‘**mobiledata**’ (or your private APN if included in your offer)  
Leave the login and password fields empty  
  
That’s it!

## Going further

Now that your first SIMs are up and running, you may want to go further.  
We recommend you take a look at some of the following articles:  
– [how to check a SIM’s card details](https://docs.transatel.com/sim-management/checking-your-sim-cards-details/)  
– [how to retrieve an eSIM’s activation code](../../sim-management/how-to-find-an-esims-status-and-retrieve-the-activation-code.md)  
– [how to set high usales rules](../../services/how-to-create-manage-high-usage-alerts-in-our-sim-management-platform.md)  
– [our analytics reports](../../analytics-reports/business-intelligence-reports/how-to-access-the-bi-reports-for-iot-customers.md)  
– [how to create additional users](../user-management/creating-user-accounts.md)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
