---
title: "The Test Mode"
---

# The Test Mode

## SIM Management​

## [Checking your SIM card details](../../sim-management/checking-your-sim-card-details/README.md)

- [Adding Subscriber Data in Bulk](../../sim-management/adding-subscriber-data-in-bulk.md)
- [Using Metadata (custom fields)](../../sim-management/metadata-custom-fields.md)
- [eSIM Quickstart Guide](../../sim-management/checking-your-sim-card-details/esim-quickstart-guide.md)
- [eSIM FAQs](../../sim-management/checking-your-sim-card-details/esim-faqs.md)
- [What are the different types of SIM? (Sales/Swap)](../../sim-management/checking-your-sim-card-details/what-are-the-different-types-of-sim-sales-swap.md)
- [Everything you need to know about SIM cards](../../sim-management/all-you-want-to-know-about-the-sim-cards.md)
- [SIM page & checkup panel overview](../../sim-management/sim-page-overview.md)
- [Adding or editing SIM and subscriber information](../../sim-management/how-to-group-tag-and-label-your-sims.md)
- [SIM's history and logs](../../sim-management/checking-a-sims-history-and-logs.md)
- [Checking a SIM's data usage](../../sim-management/sim-usage-history.md)
- [Finding an eSIM's status and retrieving the activation code](../../sim-management/how-to-find-an-esims-status-and-retrieve-the-activation-code.md)
- [Error CDRs](../../sim-management/checking-your-sim-card-details/error-cdrs.md)

## [Activate or change SIM status](../../sim-management/activate-or-change-sim-status/README.md)

- [Activating a single SIM card](../../sim-management/activating-a-single-sim-card-2.md)
- [SIM Swap](../../sim-management/activate-or-change-sim-status/sim-swap.md)
- [MSISDN Swap](../../sim-management/msisdn-swap.md)
- [SIM Lifecycle](../../sim-management/activate-or-change-sim-status/sim-lifecycle.md)
- [Activating a single SIM card](../../uncategorized/activating-a-single-sim-card.md)
- [Activating a single IoT SIM card](../../sim-management/activate-or-change-sim-status/how-to-activate-a-single-iot-sim-card.md)
- [Activating SIM cards in bulk](../../sim-management/activate-or-change-sim-status/how-to-activate-sim-cards-in-bulk.md)
- [Performing actions in bulk](../../sim-management/how-to-perform-actions-in-bulk.md)

## [Managing Groups](../../sim-management/managing-groups/README.md)

- [Creating groups of SIMs](../../sim-management/creating-groups-of-sims.md)
- [Editing, managing or deleting SIM groups](../../sim-management/managing-groups/how-to-edit-manage-or-delete-sim-groups.md)
- [Adding multiple SIMs to a group](../../sim-management/how-to-add-multiple-sims-to-a-group.md)
- [Removing SIMs from a group](../../sim-management/managing-groups/how-to-remove-a-sim-from-a-group.md)
- [Adding a SIM to a group](../../sim-management/managing-groups/how-to-add-a-sim-to-a-group.md)

## [Real-time diagnostics](https://docs.transatel.com/sim-management/real-time-diagnostics/)

- [Data session diagnostic tool](../../devices-set-up-troubleshooting/diagnostic-tools/data-session-diagnostic-tool.md)
- [Network attach diagnostic](../../sim-management/network-attach-diagnostic.md)

## [Mobile Number Portability](../../sim-management/mobile-number-portability/README.md)

- [Sw-API: providing custom switching information](../../sim-management/mobile-number-portability/sw-api-providing-custom-switching-information.md)
- [Switching Information](../../sim-management/mobile-number-portability/switching-information.md)
- [Managing Mobile Number Portability in Belgium](../../sim-management/mobile-number-portability/managing-mobile-number-portability-in-belgium.md)
- [Number Portability: everything you need to know](../../sim-management/mobile-number-portability/number-portability.md)
- [Managing Mobile Number Portability in France](../../sim-management/mobile-number-portability/managing-mobile-number-portability-in-france.md)
- [Managing Mobile Number Portability in the UK](../../sim-management/mobile-number-portability/managing-mobile-number-portability-in-the-uk.md)
- [How do I enter switching information in Auriga?](../../sim-management/mobile-number-portability/mvna-uk-how-do-i-enter-switching-information-in-auriga.md)
- [[MVNA UK] What is Switching Information?](../../sim-management/mobile-number-portability/mvna-uk-switching-information.md)

## On this page

# The Test Mode

**The Test Mode for IoT SIMs**

The Test mode is an optional mode that can be enabled for your account.  
  
The test mode is a temporary status meant to be used for tests before the device is deployed.  
It delays the SIM’s activation – and therefore monthly fees, while allowing a quota of data and SMS for internal tests.  
While in Test Mode, monthly SIM fees or minimum revenue per SIM are not applied.  
  
The test mode’s configuration is based on:  
– a **quota of data and SMS** allowed  
– a **maximum number of days** in the status  
– the **status** the SIM should switch to when exiting test mode  
  
The default configuration is that the SIM should switch to Active status after exiting Test Mode, but it is also possible to transition into Sleep Mode to further delay the activation and the start of the billing.   
  
For example if you have a test mode enabled with the following configuration  
– 1MB   
– 30 days   
– Switch to Active status when exiting Test Mode  
  
When you activate the SIM (via API or our interface), it will go into Test Mode.  
Then, when the 1MB is used, or 30 days have passed, the SIM will automatically switch to Active.  
  
![image](assets/image-1.png)

**Managing SIMs in Test Mode**

In the interface, the test mode is clearly displayed.  
  
![image](assets/image-2.png)  
  
A SIM car in Test mode can be switched to the following statuses:  
– Activated – forcing the activation is possible at any time  
– Suspended – the SIM will exit test mode definitely, will become chargeable, but will not be able to make any traffic  
– Terminated – the final and irreversible status  
  
Please note that exiting Test Mode is a final action, the SIM cannot go back to Test Mode.  
  
![image](assets/image-3.png)

**How to track usage and remaining days of the SIMs in Test Mode?**

When test mode is enabled for your account, a new type of report file will be generated daily to track the SIMs in test mode.  
The Test Mode reports can be accessed:  
– in the interface, in Tracking & Reports > File Reports > Test mode reports  
– on your Transatel SFTP account  
  
The daily report lists for each SIM in test mode:  
– the SIM details  
– inital and remaning data, SMS and voice allowances  
– initial and remaning days in test mode  
  
Here is an example for 2 SIMs :   
![image](assets/image-4.png)  
  
Below is the list of fields of the report:  
ICCID  
Msisdn  
Tariff  
Activation\_Date  
Initial\_Period  
Remaining\_Period  
Initial\_PSD\_Allowance  
Remaining\_PSD\_Allowance  
Initial\_SMS\_Allowance  
Remaining\_SMS\_Allowance  
Initial\_Voice\_CSD\_Allowance  
Remaining\_Voice\_CSD\_Allowance

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
