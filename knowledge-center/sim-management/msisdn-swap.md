---
title: "MSISDN Swap"
---

# MSISDN Swap

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

# MSISDN Swap

****MSISDN Swap****

****What is MSISDN Swap ?****

MSISDN Swap is a feature that allows the MVNO to change the current MSISDN for a given subscriber without needing to replace the their SIM card. The subscribers’ bundles and services remain unchanged. It can be performed exclusively on Active SIMs.  
This feature is available through Auriga and via API. When using the connectivity management API, a Webhook event will be received.

**/!\ Important Notes /!\**

- The MSISDN Swap is irreversible, once done the old MSISDN cannot be retrieved.
- The MSISDN Swap can be done only on an active SIM.

****When is the MSISDN Swap used for?****

The MSISDN Swap can be used in various scenarios, typically upon the request of the subscriber. Some common use-cases include:  
**Spam Calls/SMSs:** If a subscriber frequently receives spam calls and messages, an MSISDN swap can help mitigate this issue by providing a new number.  
**Harassment Calls/SMSs:** In cases where a subscriber receives threats or harassment via calls and messages to their mobile phone, an MSISDN swap can provide immediate relief by changing their number.

By offering this service, MVNOs can enhance customer satisfaction and provide a safer communication environment for their subscribers.

****How can I use the MSISDN feature?****

The following video shows how to perform an MSISDN swap via Auriga:

![image](/knowledge-center/assets/image-1.gif)

**What’s next?**

After the MSISDN replacement, the end-user receives an SMS requesting them to restart their device. As in the screen capture below :

![image](/knowledge-center/assets/image-2.jpg)

Once the operation has completed, the new MSISDN can be retrieved via Auriga, also can be retrieved from the Webhook event sent to the MVNO.

/!\ MVNOs are strongly advised to note the SIM ICCID (serial number) before performing the SIM swap in order to search for the subscriber on Auriga

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
