---
title: "Voicemail Notifications"
---

# Voicemail Notifications

## Services

## [Service profiles​](../service-profiles/README.md)

- [Changing Service Profiles](../service-profiles/changing-service-profiles.md)
- [What is a Service Profile](../what-is-a-service-profile.md)
- [Creating a Service Profile](../how-to-create-a-service-profile.md)
- [What is a deviation from a Service Profile](../what-is-a-deviation-from-a-service-profile.md)

## [Plans & Bundles](../plans-bundles/README.md)

- [Adding Capped Bundles in Bulk](../../uncategorized/adding-capped-bundles-in-bulk.md)
- [IoT Connect Capped Bundles](../plans-bundles/iot-connect-capped-bundles.md)
- [Bundles with delayed activation](../plans-bundles/bundles-with-delayed-activation.md)
- [How to subscribe to an Add-On Bundle](../plans-bundles/how-to-subscribe-to-an-add-on-bundle.md)
- [Switching bundles during a month cycle](../plans-bundles/i-want-to-switch-the-bundle-of-a-subscriber-during-the-month.md)
- [Managing Bundles from the SIM Management platform](../plans-bundles/mvno-managing-bundles-from-the-sim-management-platform.md)
- [Pricing models of our IoT offers](../plans-bundles/types-of-plans-and-bundles.md)
- [Understanding Pooled Bundles](../plans-bundles/iot-understanding-pooled-bundles.md)
- [Adding SIM cards to a pooled bundle](../iot-adding-sim-cards-to-a-pooled-bundle.md)
- [Understanding Capped bundles](../iot-understanding-capped-bundles.md)
- [Adding a capped bundle to a SIM](../iot-adding-a-capped-bundle-to-a-sim.md)
- [Managing capped bundles](../iot-managing-capped-bundles.md)

## [High Usage and Subscriber protection](../high-usage-and-subscriber-protection/README.md)

- [Alerting Cutoff](../high-usage-and-subscriber-protection/alerting-cutoff.md)

- [Overspend Safeguarding](../high-usage-and-subscriber-protection/overspend-safeguarding-osg.md)
- [All about Hiya protect](../high-usage-and-subscriber-protection/all-about-hiya-protect.md)
- [SMS Spam Solution and Fraud Prevention](../high-usage-and-subscriber-protection/sms-spam-solution-and-fraud-prevention.md)
- [Managing High Usage Rules](../managing-high-usage-rules.md)
- [Creating High Usage Alerts](../how-to-create-manage-high-usage-alerts-in-our-sim-management-platform.md)
- [High Usage File Report & Alert emails](../high-usage-file-report-alert-emails.md)
- [New High Usage Alert Menu](../high-usage-and-subscriber-protection/iot-new-high-usage-alert-menu.md)

## [Services & features](../iot-services/README.md)

- [Premium Services](../iot-services/premium-services.md)
- [NGCS Voice (Non‑Geographic Call Services)](../iot-services/ngcs-voice-non-geographic-call-services.md)
- [Shortcode Voice](../iot-services/shortcode-voice.md)
- [Premium SMS](../iot-services/premium-sms.md)
- [About SMS Recording](../iot-services/about-sms-recording.md)
- [Roaming Alerts](../iot-services/raoming-alerts.md)
- [SIM Card Artwork](../iot-services/sim-card-artwork.md)
- [How to use the IMEI Lock feature](../iot-services/how-to-use-the-imei-lock-feature.md)
- [Default Services](../iot-services/default-services.md)
- [The Sleep Mode (Tariff Holiday) - IoT optional status](../../glossary/sim-lifecycle-glossary/the-sleep-mode-tariff-holiday-iot-optional-status.md)
- [the Test Mode for IoT SIMs](../iot-services/the-test-mode.md)
- [Data Safeguarding](../data-safeguarding.md)
- [Key shortcodes](../iot-services/key-shortcodes.md)
- [Smart Barring](../iot-services/smart-barring.md)
- [Select the radio types (2G, 3G, LTE) of your SIMs](../iot-select-the-radio-types-2g-3g-lte-of-your-sims.md)
- [Network Coverage Selection](../iot-services/iot-network-coverage-selection.md)

## [Data & coverage](../data-coverage/README.md)

- [VoLTE Roaming Footprint](../data-coverage/volte-roaming-footprint.md)
- [Data Content Filtering/Parental Controls](../data-coverage/data-content-filtering-parental-controls.md)
- [How to activate 5G for my SIM base?](../how-to-activate-5g-for-my-sim-base.md)
- [How do I include a coverage checker on my website?](../data-coverage/mvna-uk-how-do-i-include-a-coverage-checker-on-my-website.md)
- [Our 5G roaming footprint](../data-coverage/mvno-uk-our-5g-roaming-footprint.md)
- [Access to the 5G network](../data-coverage/access-to-the-5g-network.md)

## [Static IP solutions](https://docs.transatel.com/services/static-ip-solutions/)

- [All about Static IP](../../uncategorized/all-about-public-static-ip.md)
- [How to find your SIMs' static IP?](../how-to-find-your-sims-static-ip.md)
- [How to activate the Static Public IP option on a SIM?](../mvno-how-to-activate-the-static-public-ip-option-on-a-sim.md)

## [VoLTE / VoWIFI](README.md)

- [Voicemail Notifications](voicemail-notifications.md)
- [VoLTE Roaming Footprint](../data-coverage/volte-roaming-footprint.md)
- [IMS service (VoLTE/VoWiFi/SMSoIP)](ims-services-volte-vowifi-smsoip.md)
- [Roaming IMS Services](roaming-ims-services.md)

## On this page

# Voicemail Notifications

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

## On this page
