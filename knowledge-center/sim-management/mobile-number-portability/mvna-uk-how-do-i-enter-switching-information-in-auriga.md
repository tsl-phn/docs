---
title: "How do I enter switching information in Auriga?"
---

# How do I enter switching information in Auriga?

## SIM Management​

## [Checking your SIM card details](../checking-your-sim-card-details/README.md)

- [Adding Subscriber Data in Bulk](../adding-subscriber-data-in-bulk.md)
- [Using Metadata (custom fields)](../metadata-custom-fields.md)
- [eSIM Quickstart Guide](../checking-your-sim-card-details/esim-quickstart-guide.md)
- [eSIM FAQs](../checking-your-sim-card-details/esim-faqs.md)
- [What are the different types of SIM? (Sales/Swap)](../checking-your-sim-card-details/what-are-the-different-types-of-sim-sales-swap.md)
- [Everything you need to know about SIM cards](../all-you-want-to-know-about-the-sim-cards.md)
- [SIM page & checkup panel overview](../sim-page-overview.md)
- [Adding or editing SIM and subscriber information](../how-to-group-tag-and-label-your-sims.md)
- [SIM's history and logs](../checking-a-sims-history-and-logs.md)
- [Checking a SIM's data usage](../sim-usage-history.md)
- [Finding an eSIM's status and retrieving the activation code](../how-to-find-an-esims-status-and-retrieve-the-activation-code.md)
- [Error CDRs](../checking-your-sim-card-details/error-cdrs.md)

## [Activate or change SIM status](../activate-or-change-sim-status/README.md)

- [Activating a single SIM card](../activating-a-single-sim-card-2.md)
- [SIM Swap](../activate-or-change-sim-status/sim-swap.md)
- [MSISDN Swap](../msisdn-swap.md)
- [SIM Lifecycle](../activate-or-change-sim-status/sim-lifecycle.md)
- [Activating a single SIM card](../../uncategorized/activating-a-single-sim-card.md)
- [Activating a single IoT SIM card](../activate-or-change-sim-status/how-to-activate-a-single-iot-sim-card.md)
- [Activating SIM cards in bulk](../activate-or-change-sim-status/how-to-activate-sim-cards-in-bulk.md)
- [Performing actions in bulk](../how-to-perform-actions-in-bulk.md)

## [Managing Groups](../managing-groups/README.md)

- [Creating groups of SIMs](../creating-groups-of-sims.md)
- [Editing, managing or deleting SIM groups](../managing-groups/how-to-edit-manage-or-delete-sim-groups.md)
- [Adding multiple SIMs to a group](../how-to-add-multiple-sims-to-a-group.md)
- [Removing SIMs from a group](../managing-groups/how-to-remove-a-sim-from-a-group.md)
- [Adding a SIM to a group](../managing-groups/how-to-add-a-sim-to-a-group.md)

## [Real-time diagnostics](https://docs.transatel.com/sim-management/real-time-diagnostics/)

- [Data session diagnostic tool](../../devices-set-up-troubleshooting/diagnostic-tools/data-session-diagnostic-tool.md)
- [Network attach diagnostic](../network-attach-diagnostic.md)

## [Mobile Number Portability](README.md)

- [Sw-API: providing custom switching information](sw-api-providing-custom-switching-information.md)
- [Switching Information](switching-information.md)
- [Managing Mobile Number Portability in Belgium](managing-mobile-number-portability-in-belgium.md)
- [Number Portability: everything you need to know](number-portability.md)
- [Managing Mobile Number Portability in France](managing-mobile-number-portability-in-france.md)
- [Managing Mobile Number Portability in the UK](managing-mobile-number-portability-in-the-uk.md)
- [How do I enter switching information in Auriga?](mvna-uk-how-do-i-enter-switching-information-in-auriga.md)
- [[MVNA UK] What is Switching Information?](mvna-uk-switching-information.md)

## On this page

# How do I enter switching information in Auriga?

****How do I enter switching information in Auriga?****

This page explains how to add your [early termination fees](mvna-uk-switching-information.md) in Auriga. It is one of three methods that can be used for Transatel to obtain this information when replying to a subscriber’s switching request by SMS.  
  
1. Select the line that you want to enter the switching fees for   
   
![image](/knowledge-center/assets/image-1.png)
  
2. In the subscriber details screen, select “Other Actions”   
  
![image](/knowledge-center/assets/image-2.png)
   
3. Choose “Enter Termination Fee”   
![image](/knowledge-center/assets/image-3.png) 
Select the termination fee type and fill out the information   
![image](/knowledge-center/assets/image-4.png)

****What are the different types of Early Termination Fees?****

There are three options   
– **None**: the subscriber is out of contract or on a 30-day rolling contract. They will have no sums to pay if they decide to cancel their subscription or change provider.   
– **Monthly Fee**: the subscriber is in a fixed-term contract (I.e. for 12 or 24 months). If the subscriber cancels their contract early they will need to pay early termination fees relating to the time left in-contract.   
– **Fixed Fee**: if the subscriber chooses to leave early, there will be a one-off fixed penalty to terminate their subscription.

****How do I enter the Monthly Fee?****

If the subscriber is in a fixed-term contract (I.e. for 12 or 24 months) and cancels their contract early they will need to pay early termination fees relating to the time left in-contract.   
![image](/knowledge-center/assets/image-5.png) 
– **Contract end date**: the date in which their mobile SIM subscription (contract) ends   
**–** **Monthly fee**: how much the subscriber pays (retail) per month   
**–** **Maximum termination fee**: if the MVNO chooses to have a policy to limit the fee in case of early termination (I.e. maximum of 3 months charges or up to £100), enter the amount in £ here.   
**–** **Mobile device contract end date**: if there is a separate contract for a mobile device or handset, enter the end date of this contract. If it is bundled with the airtime, you can wrap this information together with the contract end date above.   
**–** **Mobile device monthly fee**: if there is a separate contract for a mobile device or handset, enter the monthly (retail) fee here. If it is bundled with the airtime, you can wrap this information together with the contract end date above.

****How do I enter the fixed fee?****

If the subscriber chooses to leave early, the MVNO may choose to charge a one-off fixed penalty to terminate their subscription.   
![image](/knowledge-center/assets/image-6.png) 
– **Contract end date**: the date up until which the fixed penalty fee will apply. This may not be an actual contract date but a contractual obligation. If it is for the lifetime of the subscriber, you can select a date far in the future (such as 2100!)   
**–** **Cancellation fee**: The one-off fixed fee in £ which will be applied if the subscriber requests to switch-out before the above date.

**How do I know which lines have switching fees entered?** 

Transatel will export a snapshot of all of the switching fees entered into the Auriga interface once per month on your sFTP.  
You can use this rapport to check that your contract information and make sure switching fees are up-to-date.  
More information on the report [here](../../analytics-reports/report-files/switching-termination-fees-report.md).

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
