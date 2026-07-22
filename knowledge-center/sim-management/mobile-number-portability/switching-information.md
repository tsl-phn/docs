---
title: "Switching Information"
---

# Switching Information

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

# Switching Information

**What is switching information?**

As part of Ofcom’s regulation, subscribers should be able to switch mobile phone provider without needing to contact the provider (text to switch), with or without keeping their number.  
  
  
The subscriber can also retrieve the costs associated from leaving their current provider, in or outside of a switch. This information should be provided by the channel of request, but also by SMS to the subscriber.  
  
This switching information is provided alongside the PAC (text “PAC” to 65075) or STAC (text “STAC” to 75075, or outright if the switching information only is requested (text “INFO” to 85075).  
  
Source:  
https://www.ofcom.org.uk/phones-and-broadband/switching-provider/switching-mobile-phone-provider

**How does Transatel help me comply?**

Transatel will not only manage the porting process from A-Z, but it will also provide the switching information when required.   
Attention, in order for Transatel to provide switching information, we need MVNO inputs!

**How can I provide Transatel with Switching Information?**

1. Transatel calculated  
Transatel allows you to enter the contract information required to calculate switching costs:  
– Via Auriga (click [here](mvna-uk-how-do-i-enter-switching-information-in-auriga.md))  
– Via API (click [here](https://api.transatel.com/connectivity-management/subscribers/docs/index.html#tag/Portability-management-UK/operation/putPortabilityEarlyTerminationFees))  
  
2. MVNO provided (Sw-API)  
The MVNO can concatenate and provide the exact text that they wish to display for the Switching Information. They most expose this information via an API which is consumed by Transatel in the case of a switching event.  
For the specification, click [here](sw-api-providing-custom-switching-information.md).  
  
3. Static  
Is some cases (for example where it is a B2B account, and fees are managed on an account level for several SIMs), it may not be pertinent to provide switching information. In which case, Transatel can place a static text, i.e. prompting the business user to contact their account manager.

## What does the subscriber receive?

### Transatel computed

By default, no switching info provided. If no switching information is provided, the SMS received will be the following (alongside the PAC/STAC code if relevant):

*Dear customer, there will be no early termination fees if you decide to change providers. For more information, please visit <https://switch-portal.co.uk/>*

This is the default message if no switching info is added so make sure your Switching Information is up to date!

If the Switching information is provided, the following SMS will be one of the following, depending on the fee information that has been pre-provided to Transatel:

*Dear customer, your current contract ends on [date]. If you decide to change providers before this date, there will be a termination fee of [£x] for each remaining month in your contract (up to [£x]). More info on <https://switch-portal.co.uk/>*

*Dear customer, your current contract ends on [date]. If you decide to change providers before this date, there will be a termination fee of [£x] for each remaining month in your contract (up to [£x]). Your handset contract ends on [date]. If you decide to change providers, there will be a termination fee [£x] for each remaining month in your handset contract. More info on <https://switch-portal.co.uk/>*

*Dear customer, if you request to change providers, there will be a fixed termination fee of [£x].For more information, please visit <https://switch-portal.co.uk/>*

### Sw-API

The text will display exactly how the MVNO outputs via Sw-API.

### Static

The MVNO can choose between the following two standard messages to be configured on their MVNO account

*Thanks for your request. As this is a business account, the registered owner will need to contact the Service Provider for the PAC code and switching information relating to this number.  
Dear customer, for information on costs incurred when changing providers, please contact customer services.*

## Disclaimer

*This article does not constitute as legal advice.* *Transatel makes this information and these methods available to the MVNO, it is up to the MVNO *to ensure compliancy**, *to apply the correct types and/or methods of switching fees provisions according to their commercial relationship with their customer and make their own decisions on how to comply with Ofcom regulation.*

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
