---
title: "Voicemail Notifications"
---

# **Overview**

Voicemail notifications ensure subscribers are promptly and clearly informed when a new message is waiting.  
Transatel provides a range of notification options so Service Providers can tailor the voicemail experience to their product positioning and customer expectations. Configuration is managed in **Auriga**, or via API, either per subscriber (Configured Services) or centrally through **Service Profiles** (see [Service Profiles documentation](../service-profiles/README.md)).

# **Available Notification Types**

- **MWI (Message Waiting Indicator)**  
  A discreet, device‑native icon that appears when a voicemail is received.
- **SMS Notification**  
  A clear, user‑friendly text message automatically displayed in the subscriber’s selected language.
- **MWI + SMS Notification**  
  Provides both a visual device alert and an SMS message.
- **No Notification**  
  For use cases where silent behaviour is required.

# **Subscriber Behaviour**

New activations default to **MWI**, unless another option is selected.

# **Language Handling**

If a subscriber’s voicemail language is changed through provisioning, all SMS notifications automatically update to the new language — no additional configuration required.

# **SMS Notification Details**

**Originating number:** **555**

**Message text:**

**“You’ve received a new voicemail<#if callerMsisdn != ‘anonymous’> from +${callerMsisdn}</#if> on ${depositDate?datetime(‘yyyy‑MM‑dd HH:mm’)?string.short}.  
You now have ${messageCount} new message<#if messageCount gt 1>s</#if>.  
Dial 555 to listen to your voicemail.”**

#### **Where:**

- **Caller’s number** appears only if the caller is not anonymous.
- **Date and time** show when the voicemail was left, using the subscriber’s language and regional format.
- **Message count** updates automatically and uses the correct singular/plural form.
- **Dial 555** is a fixed voicemail access number.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
