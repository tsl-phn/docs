---
title: "Managing Mobile Number Portability in Belgium"
---

# Managing Mobile Number Portability in Belgium

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

# Managing Mobile Number Portability in Belgium

**Managing Mobile Number Portability in Belgium** 

**General terms to understand:**  
  
MNP – Mobile Number Portability: The process that allows a subscriber to keep their mobile number when they change service providers.  
  
CRDC – Common Reference Database Centre: Central management system for mobile and fixed line portability in Belgium. Provides a public site to find out the current operator of a mobile or fixed line.  
  
MSISDN: a unique mobile number attached to each SIM card.  
  
Donor: Operator hosting the MSISDN at the beginning of a portability process.  
  
Recipient: Operator initiating the portability request to host a MSISDN from another operator.  
  
See our other articles for more information on portability for the [UK market](managing-mobile-number-portability-in-the-uk.md) and the [French market](managing-mobile-number-portability-in-france.md).

**What is the portability process in Belgium?  
  
![image](/knowledge-center/assets/image-1.png)**

It is a 3-step process: eligibility request, execution, and diffusion.  
  
An operator may request to port mobile numbers by sending an MNP request message to the operator currently servicing the mobile number. If the request is found valid by the main porting provider, CRDC, the MNP request can then be validated by the operator servicing the number so that the portability can be completed.

**What do I have to do as an MVNO?**

When a new subscriber wants to move to your services, you must apply for portability with Transatel. The information required for portability is the Sim Serial or the Customer Account.  
  
The portability will be eligible if:  
– The subscriber is active when the portability is done  
– There is no other portability on the Transatel line and on the number.  
  
Once the eligibility is validated, the portability will be executed. The portability MSISDN is completed on the donor side and is now used on the recipient side.

**How to cancel a portability request?**

If the subscriber wants to cancel his portability request, you can make the request directly to Transatel.  
  
The cancellation can only be done during the eligibility period. The MVNO will then be notified by Transatel when the cancellation of the portability is done.

**What if my subscriber wants to take his number with him to another operator?**

Transatel will send you a notification once the outgoing portability is executed.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
