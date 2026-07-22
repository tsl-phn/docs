---
title: "Network attach diagnostic"
---

# Network attach diagnostic

## SIM Management​

## [Checking your SIM card details](checking-your-sim-card-details/README.md)

- [Adding Subscriber Data in Bulk](adding-subscriber-data-in-bulk.md)
- [Using Metadata (custom fields)](metadata-custom-fields.md)
- [eSIM Quickstart Guide](checking-your-sim-card-details/esim-quickstart-guide.md)
- [eSIM FAQs](checking-your-sim-card-details/esim-faqs.md)
- [What are the different types of SIM? (Sales/Swap)](checking-your-sim-card-details/what-are-the-different-types-of-sim-sales-swap.md)
- [Everything you need to know about SIM cards](all-you-want-to-know-about-the-sim-cards.md)
- [SIM page & checkup panel overview](sim-page-overview.md)
- [Adding or editing SIM and subscriber information](how-to-group-tag-and-label-your-sims.md)
- [SIM's history and logs](checking-a-sims-history-and-logs.md)
- [Checking a SIM's data usage](sim-usage-history.md)
- [Finding an eSIM's status and retrieving the activation code](how-to-find-an-esims-status-and-retrieve-the-activation-code.md)
- [Error CDRs](checking-your-sim-card-details/error-cdrs.md)

## [Activate or change SIM status](activate-or-change-sim-status/README.md)

- [Activating a single SIM card](activating-a-single-sim-card-2.md)
- [SIM Swap](activate-or-change-sim-status/sim-swap.md)
- [MSISDN Swap](msisdn-swap.md)
- [SIM Lifecycle](activate-or-change-sim-status/sim-lifecycle.md)
- [Activating a single SIM card](../uncategorized/activating-a-single-sim-card.md)
- [Activating a single IoT SIM card](activate-or-change-sim-status/how-to-activate-a-single-iot-sim-card.md)
- [Activating SIM cards in bulk](activate-or-change-sim-status/how-to-activate-sim-cards-in-bulk.md)
- [Performing actions in bulk](how-to-perform-actions-in-bulk.md)

## [Managing Groups](managing-groups/README.md)

- [Creating groups of SIMs](creating-groups-of-sims.md)
- [Editing, managing or deleting SIM groups](managing-groups/how-to-edit-manage-or-delete-sim-groups.md)
- [Adding multiple SIMs to a group](how-to-add-multiple-sims-to-a-group.md)
- [Removing SIMs from a group](managing-groups/how-to-remove-a-sim-from-a-group.md)
- [Adding a SIM to a group](managing-groups/how-to-add-a-sim-to-a-group.md)

## [Real-time diagnostics](https://docs.transatel.com/sim-management/real-time-diagnostics/)

- [Data session diagnostic tool](../devices-set-up-troubleshooting/diagnostic-tools/data-session-diagnostic-tool.md)
- [Network attach diagnostic](network-attach-diagnostic.md)

## [Mobile Number Portability](mobile-number-portability/README.md)

- [Sw-API: providing custom switching information](mobile-number-portability/sw-api-providing-custom-switching-information.md)
- [Switching Information](mobile-number-portability/switching-information.md)
- [Managing Mobile Number Portability in Belgium](mobile-number-portability/managing-mobile-number-portability-in-belgium.md)
- [Number Portability: everything you need to know](mobile-number-portability/number-portability.md)
- [Managing Mobile Number Portability in France](mobile-number-portability/managing-mobile-number-portability-in-france.md)
- [Managing Mobile Number Portability in the UK](mobile-number-portability/managing-mobile-number-portability-in-the-uk.md)
- [How do I enter switching information in Auriga?](mobile-number-portability/mvna-uk-how-do-i-enter-switching-information-in-auriga.md)
- [[MVNA UK] What is Switching Information?](mobile-number-portability/mvna-uk-switching-information.md)

## On this page

# Network attach diagnostic

## About Network attach

Even if there’s no ongoing data traffic, our interface gives your visibility on the last known network your SIM has attached to.   
  
Cellular-enabled devices are “attached” to a radio antenna and periodically renew the attach to stay connected. This signaling events are “location updates”.  
The last notification received in our system is what we display as the “last attach”.  
  
An update is usually triggered:

- When the device is switched on (but not always in reboots though)
- When the device moves to a new area (and connects to a new cell)
- When the device connects to another bearer type (ex: from LTE to 3G)
- At regular intervals to keep the connection active, as each operator requires devices to do so to stay connected (the duration of these intervals varies from operator to operator)

In addition, we offer you the possibility to force the SIM to detach from the network

**Note:** this tool is not available for customers on MVNO France Light and MVNO UK frameworks

## **How to use this feature?**

In our interface, go to the page of the SIM card you wish to check.  
You’ll find all the details in the Activity section of the check-up panel, on the right side.

- The **last attach’s timestamp**
- The**IMSI**
- The **visited country**
- The visited **operator network – for 4G/LTE connections only**

![image](/knowledge-center/assets/image-1.png)

If the SIM has not attached to the network in the past 3 months, we will display the following:

![image](/knowledge-center/assets/image-2.png)

## Network Attach History

You can check the history of the past 3 months of network attaches by clicking on the history button

![image](/knowledge-center/assets/image-3.png)
![image](/knowledge-center/assets/image-4.png)

the fields available are the following:

|  |  |
| --- | --- |
| **Field name** | **Description** |
| **Timestamp** | Last attach / Last location update notified to Transatel HSS |
| **IMEI** | International Mobile Equipment Identity. Unique identifier of the device embedding the SIM card  when available (only 4G / 5G) |
| **IMSI** | Always primary IMSI |
| **MSISDN** | **M**obile **S**tation **I**nternational **S**ubscriber **D**irectory **N**umber (MSISDN) is a unique identifier of a subscriber in a mobile network. Simply put, it is the telephone number to the SIM card in a device. |
| **RAT** | Radio Access Technology. Can be either “2G/3G” or “4G/5G”. |
| **HSS** | Home Subscriber Server instance which holds the connectivity service subscription. |
| **Operator Name** | PLMN name (HSS resolution) |
| **MCC** | Mobile Country code of the visited country as defined by ITU-T. |
| **Country \*** | Visited country |
| **PLMN Name \*** | PLMN name (HSS resolution) |

\* in the case of IMSI roaming sponsor some information may not be available. The PLMN Name and country shown is the following : Orange France

## **How to use the network detach tool**

Forcing the SIM to reconnect to the cellular network is a simple and effective way to solve connectivity issues as it reboots the SIM on the network.  
If the SIM encountered connectivity issues, after being detached from the network, the SIM can reattach:  
·     Correctly on the network, which solves many roaming connectivity issues  
·     To a stronger signal (new operator, new antenna)  
·     To 4G instead of 3G, or 3G instead of 2G  
And use new connectivity settings if you made a change of configuration (for example, change of footprint).

To launch a request, just click on the “detach button”

![image](/knowledge-center/assets/image-5.png)

You will see confirmation if the request was successfully transmitted to our HSS at the bottom of the screen  
![image](/knowledge-center/assets/image-6.png)
  
A “cancel location” request has been sent to the network, which will then require the equipment to update its location – in simple terms, it will have to reconnect to the network.  
After a minute, you can try to refresh the last attach – if the device has successfully updated its attach to the network, the new attach info will be displayed.

## **A few limits to keep in mind:**

- The feature **does not let you know if the device is connected at this very instant**– just when it re-attached last. It means you can know if there was recent activity.
- The device may have detached since the last attach – for example the device could have been turned off, or left to a no-coverage zone, thus without the network knowing
- We keep records over the past 3 months (starting from the launch of the service) – if a SIM has not attached in the past 3 months, we’ll display that the has no recent attach

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
