---
title: "[MVNA UK] What is Switching Information?"
---

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
