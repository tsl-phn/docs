---
title: "[MVNA UK] What is Switching Information?"
---

# [MVNA UK] What is Switching Information?

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

# [MVNA UK] What is Switching Information?

**[MVNA UK] What is Switching Information?**

****What is switching?****

Switching is an Ofcom regulation to facilitate subscribers to change providers with or without keeping their number.   
  
For more information, please go to <https://www.ofcom.org.uk/phones-telecoms-and-internet/advice-for-consumers/costs-and-billing/switching/switching-mobile-phone-provider>   
There are 2 codes that that subscriber can text to switch:   
– **PAC to 65075:** the subscriber wants to change provider and keep their number ([port out](managing-mobile-number-portability-in-the-uk.md))   
– **STAC to 75075:** the subscriber wants to change provider without needing to contact their current provider   
  
In both cases, the subscriber must also receive in the text message their early termination fees: how much they need to pay their current provider if they cancel their subscription before the end of their contract.   
  
Otherwise, if the subscriber is simply considering their options, they can also text   
– **INFO to 85075**: they subscriber will receive a text with their potential early termination fees.

****Who manages this process?****

Rest assured! Transatel receives the text from the subscriber on behalf of its MVNOs and coordinates all the actions to respond correctly, including:   
– Retrieving the PAC or STAC code from Syniverse (the UK portability and switching administrator)   
– Retrieving the switching information according to the method chosen by the MVNO   
– Replying to the subscriber by SMS with all of the above information

****How can I provide switching information to Transatel?****

Transatel provides 3 different methods to provide switching information to MVNOs’ subscribers:   
– **[Computed in Auriga](mvna-uk-how-do-i-enter-switching-information-in-auriga.md):** you can enter the contract details in Auriga. When we receive a switching request, we’ll calculate the remaining fees due to the subscriber and send them a text.   
– **Sw-API**: when we receive a switching request from a subscriber, we’ll fetch the information from your BSS using an API. This way you can customize the text completely and include information on other products and services that may be impacted.   
**–** **Static**: If your subscriber requests a switch and it’s a B2B subscriber, we can return a static message to point them to their fleet manager if they need to port.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
