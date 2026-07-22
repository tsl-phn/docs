---
title: "Managing Mobile Number Portability in France"
---

# Managing Mobile Number Portability in France

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

# Managing Mobile Number Portability in France

******Managing Mobile Number Portability in France******

**General terms to understand**:  
  
**RIO – Relevé d’identité opérateur**: French portability authorisation code that allows you to keep your number when you change mobile operators  
  
**MSISDN**: is a unique mobile number attached to each SIM card.  
  
**Donor**: operator hosting the MSISDN at the beginning of a portability process.  
  
**Recipient**: operator initiating the portability request to host a MSISDN from another operator.  
  
See our other articles for more information on portability for the [UK market](managing-mobile-number-portability-in-the-uk.md) or the [Belgium market](managing-mobile-number-portability-in-belgium.md).  
  
Follow our [step-by-step guide](https://papyrus-dev.priv.transatel.net/docs/connectivity-management-guides-fr-portin/) to SIM card activation on our **Developer’s Portal**.

**What is the portability process in France?  
  
![image](/knowledge-center/assets/image-1.png)**

It is a 3-step process: requesting the RIO, eligibility, execution.  
The subscriber who wishes to keep their number must first call their current provider to obtain an RIO. Eligibility is then validated by the national portability body, the EGP. Then, the portability execution will be completed.

**How can my subscriber retrieve his RIO code in complete autonomy ?**

A subscriber who wants to keep his number has two possibilities to retrieve his RIO: he can receive his code via SMS from the MVNO or by calling the IVR that can be reached on 3179.  
The MVNO can then retrieve the RIO via our SIM management platform or via its own platform using our APIs.  
The subscriber does not have to cancel their line with their current operator, this will be done through the portability process.

**What do I need to do as a MVNO?**

When a new subscriber wants to move to your services, you must make a portability request via our SIM management platform or via API. The information required for portability includes the MSISDN, the RIO and the portability date. In France, this date must be between 3 and 59 days after the request, between 11H and 15H, and cannot fall on a weekend or bank holiday.  
  
The portability will be eligible if:  
– The subscriber is active when the portability is made  
– There is no other portability on the Transatel line and on the number  
– A valid portability date  
  
Once the eligibility has been validated, the portability will be executed.   
  
The portability MSISDN is completed on the donor side and is now used on the recipient side. All routing tables are updated for all French operators.  
  
**NB: portability on an active line is not available for customers on the Light architecture.**

**What portability measures can I take as a service provider?**

–          Cancelling a portability request  
If the subscriber wants to cancel his portability request, you can make the request directly to Transatel.  
The cancellation can only be done during the eligibility period, until the day before the portability is done. The MVNO will then be notified by Transatel when the cancellation of the portability is done.  
  
–          Cancelling a portability date and request another date  
You can cancel the date of portability up until the day before the execution.

**How do I provide the RIO code to a subscriber?**

You need to send the RIO to your subscriber. You can retrieve it via our API or our platform and send it via SMS.  
  
Via our SIM management platform, the RIO can be retrieved by using the ‘Other actions’ tab to the right of your screen:  
  
![image](/knowledge-center/assets/image-2.png)
  
Transatel will send you a notification once the outgoing portability is executed.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
