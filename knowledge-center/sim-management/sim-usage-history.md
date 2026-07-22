---
title: "Checking a SIM\u2019s data usage"
---

# Checking a SIM’s data usage

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

# Checking a SIM’s data usage

## Checking a SIM’s usage

To see a SIM’s usage, you have 2 possibilities:

- in the inventory pages, the usage made by the SIM since beginnign of the month will be displayed in the usage column
- and to go further, you can go to the SIM’s detailed page

## SIM monthly usage

in the SIM list (in All Assets, or in any inventory view, you can see the data usage made since the beginning of the month by the SIMs of your fleet.

This is available for data (in GB), voice and SMS.

![image](/knowledge-center/assets/image-1.png)

The field might be hidden to the right – use the “manage columns” button to drag it where you need

![image](/knowledge-center/assets/image-2.png)

You can then sort by SIMs which made the most – or least usage

Additionally, you can use the filter panel to search for SIMs that made a specific volume in GB

for example…between 0.5 and 2.3GB

![image](/knowledge-center/assets/image-3.png)

## In the SIM’s detailed view

Usage can be displayed in table or in graph view:

![image](/knowledge-center/assets/image-4.gif)

## The Graph view

You can now select to display data usage by:

- data session – in line with the device behaviour’s
- Call detail records – for a finer analysis with short intervals of a few minutes

![image](/knowledge-center/assets/image-5.png)

The graph view is the most user-friendly way to display and understand usage.  
Here’s a little use case. Here is the data usage of my SIM over the past months:  
![image](/knowledge-center/assets/image-6.gif)
By hovering my cursor over the bars, the cumulated usage is displayed. I notice that this SIM has had an increased usage in December: 10GB  
By toggling to daily view, I notice a high peak of usage happened on December 18th:  
  
![image](/knowledge-center/assets/image-7.gif)
To go further, I’ll filter down on that very day, and toggle the view to hourly:  
  
![image](/knowledge-center/assets/image-8.gif)
  
I can now see that out of the 10GB usage made on that day, 9.26GB were used just in a one-hour period! That’s good intel to start an investigation!  
So let’s review the commands used:

## The table view

The new table view is a much-enhanced version of old display.  
First, you’ll notice that we now get an aggregated total of the usage

![cumulated usage](/knowledge-center/assets/image-9.png)

Please note that the total may not match 100% the usage amount you’ll find on your invoice. This is raw data, not the final version processed by our billing engine, therefore there can be discrepancies due to rounding, or to end of months CDRs counted in another month’s invoice.  
By default we display usage from the start of the current month, you can easily change the dates in the filter panel.  
You can filter down to one specific month, day or even hour.

![image](/knowledge-center/assets/image-10.png)
  
About time zones: please note that while our interface is matching your computer’s time and displays usage in local time, the timestamps present in the CSV export are in UTC format.  
  
The table has been enriched with additional fields, and its design has been improved.  
![image](/knowledge-center/assets/image-11.png)
  
There are plenty of fields and ways to toggle the view to display exactly what you want to see.  
Here are the commands available to you with the control buttons:  
  
![control buttons of usage](/knowledge-center/assets/image-12.png)

## Fields available to filter usage

The Call Detail Records used to display aggregated usage contain many fields with advanced information.  
In addition to being used as filter, all the fields will be displayed in the table view, and will be in the csv export as well.    
  
**About time zones:** please note that while our interface is matching your computer’s time and displays usage in local time, the timestamps present in the CSV export are in UTC format.  
  
Here is the full detailed list of the fields:  
![image](/knowledge-center/assets/image-13.png)![image](/knowledge-center/assets/image-14.php)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
