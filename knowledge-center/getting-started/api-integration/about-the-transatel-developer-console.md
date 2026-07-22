---
title: "About the Transatel Developer Console"
---

# About the Transatel Developer Console

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

# About the Transatel Developer Console

## What is the Developer Console?

The Developer’s Console is a tool that Transatel makes available to help clients integrate their APIs as seamlessly as possible, giving your developers the tools to be able to check in real-time the success of their integration autonomously. This tool helps you to debug any anomalies that may occur in your API integration, including failed requests or broken webhooks. As such, it only pertains to API request, and not human actions through the Auriga Platform.

The Developer Console is also the new interface to be used to create datastreams to receive our webhook events. The webhook API previously made available will be deprecated and replaced by this new UI.

It can be used in conjunction with the Developer’s Portal which equips Developers with all the knowledge necessary to integrate Transatel’s APIs.

## What can I do in the Developer Console?

**Dashboard**

![image](assets/image-1.png)

The dashboard provides users with a comprehensive overview of API usage, making it easy to spot and resolve any integration issues. Analytics can be filtered by 4 hours, 12 hours, 24 hours, or 1 week. The available analytics include:

- **API requests**

Volume of successful and failed requests

- **Success Rate**

Percentage of requests with 2xx response codes

- **API Distribution**

Distribution of request per API type (volume and percentage)

- **Errors Distribution**

Shows the errors for each API (Connectivity Management, OCS, SIM Management…)

- **Recent Errors**

On the right side of the screen, users can view a list of the 20 most recent errors. Errors can be filtered by integration issues (4xx errors) or technical problems (5xx errors)

**Data streams**

Data Streams allows you to manage your webhook events that can either be pushed to an endpoint or to a cloud platform.

![image](assets/image-2.png)

You will be able to

- Add or remove events
- Enable or disable the data stre am
- Change the endpoint
- Send a test event
- See the events sent to this stream

Please check the detailed article on creating and managing datastreams for further details.

**Logs**

![image](assets/image-3.png)

The log section allows users to view all API and event logs to easily identify API error, with a retention period of 30 days.

The Logs tab offers a filterable list of API requests, enabling users to quickly locate specific entries based on:

- Date
- Requests status (successful, failed or all)
- The HTTP method used
- The API endpoint path which also allows a wildcard (\*)
- An error code

For each request log, the following information is available:

- HTTP method and path
- Status
- Request ID
- Timestamp
- API name and version
- Source user agent
- Source IP

## How do I access the Developer console?

You can use your Auriga User Login to access the Developer’s console, as long as it has been given the rights permission to access the Developer’s Console.

## What should I do if my Auriga Login doesn’t work?

Contact your account manager, they will be able to attribute the required rights for you to be able to connect to the Developer’s Console.

## Webhook API Decomissioning

As of February 2026, you will no longer be able to subscriber to webhooks via API. From this point, all webhooks can be subscribed to using the Developer’s console. This will make the process slicker and simpler, as well as avoid any errors in the API request. Furthermore, it will give instant visibility of the webhooks you are implementing.

## Can I manage more than one account using the Developer Console?

All the accounts that are linked to your Auriga login will be displayed in the Developer’s Console.

## How can I have more information about APIs integration?

For more information on API integration, the Transatel Developer Portal offers detailed, up-to-date documentation for all available APIs to support efficient development and implementation. Access the documentation: [**here**](https://developers.transatel.com/) How to create a datastream to receive events?

## Managing your datastreams in the Console

Data Streams allows you to manage your webhook events that can either be pushed to an endpoint or to a cloud platform.

## How to create a new datastream?

![image](assets/image-4.png)

Click on a data stream to display the events that were sent to it

![image](assets/image-5.png)

There is also the ability to simulate events on the datastream to check the integration (however, just tests will not appear in the logs).

To create a new datastream, click on Add a Datastream.

![image](assets/image-6.png)

You will be then asked to select an MVNO account (if multiple are linked to your user), and in the following screen, you will be able to select the events you wish to receive in this stream

![image](assets/image-7.png)

Please refer to the list of events detailed for each API in the Developer Portal.

You can search for a specific event

![image](assets/image-8.png)

Once your configuration is complete, you can send a test event to validate your setup.

![image](assets/image-9.png)

The test event is only sent to your endpoint, it will not appear in the dashbaord log.

## How to manage your datastreams?

All of the webhooks that you have previously subscribed to via API will be displayed here.

![image](assets/image-10.png)

To check or edit a data stream, click on it to display its configuration

You will be able to

- Add or remove events
- Enable or disable the data stre am
- Change the endpoint
- Send a test event
- See the events sent to this stream

![image](assets/image-11.png)
![image](assets/image-12.png)

If a datastream is suspended, it either means that the endpoint is no longer valid or the event is longer available.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
