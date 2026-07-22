---
title: "Smart Barring"
---

# Smart Barring

## Services

## [Service profiles](../service-profiles/README.md)

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

## [Services & features](README.md)

- [Premium Services](premium-services.md)
- [NGCS Voice (Non‑Geographic Call Services)](ngcs-voice-non-geographic-call-services.md)
- [Shortcode Voice](shortcode-voice.md)
- [Premium SMS](premium-sms.md)
- [About SMS Recording](about-sms-recording.md)
- [Roaming Alerts](raoming-alerts.md)
- [SIM Card Artwork](sim-card-artwork.md)
- [How to use the IMEI Lock feature](how-to-use-the-imei-lock-feature.md)
- [Default Services](default-services.md)
- [The Sleep Mode (Tariff Holiday) - IoT optional status](../../glossary/sim-lifecycle-glossary/the-sleep-mode-tariff-holiday-iot-optional-status.md)
- [the Test Mode for IoT SIMs](the-test-mode.md)
- [Data Safeguarding](../data-safeguarding.md)
- [Key shortcodes](key-shortcodes.md)
- [Smart Barring](smart-barring.md)
- [Select the radio types (2G, 3G, LTE) of your SIMs](../iot-select-the-radio-types-2g-3g-lte-of-your-sims.md)
- [Network Coverage Selection](iot-network-coverage-selection.md)

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

## [VoLTE / VoWIFI](../volte-vowifi/README.md)

- [Voicemail Notifications](../volte-vowifi/voicemail-notifications.md)
- [VoLTE Roaming Footprint](../data-coverage/volte-roaming-footprint.md)
- [IMS service (VoLTE/VoWiFi/SMSoIP)](../volte-vowifi/ims-services-volte-vowifi-smsoip.md)
- [Roaming IMS Services](../volte-vowifi/roaming-ims-services.md)

## On this page

# Smart Barring

**Smart Barring**

**What is Smart Barring?**

Smart barring is a feature from Transatel which blocks all subscriber communications apart from oubound calls. These can be routed to a number of the MVNO’s choice.

**Which services are blocked?**

Smart barring does the following  
– National data: blocked  
– National outbound SMS: blocked  
– National inbound SMS: open (so you can still notify your subscriber!)  
– National outbound calls: re-routed  
– National inbound calls: blocked  
– Roaming services: blocked

**What can it be used for?**

Smart barring’s main purpose is for debt recovery purposes. For example, if a subscriber hasn’t paid their bill, their services are blocked and if they try to make a call, they will be redirected to the payments team.  
However, each MVNO is unique, and you can design your own use-cases and purposes for the smart barring feature.

**How do I configure my smart barring long number?**

The number to which we route the outbound call must be a long number (geographic, mobile or business number) managed by the MVNO.  
During the setup phase, we request your desired Smart Barring long number to configure for your MVNO account.  
If you want to change this or hadn’t requested it, simply log a ticket on the service desk.

**How do I provision Smart Barring?**

Smart Barring can be provisioned per subscriber on Auriga under “Network Barrings”:  
![image](/knowledge-center/assets/image-1.png)
It can also be provisioned using the Connectvity Management API. Check out your options in Auriga under Catalogue > Options:  
![image](/knowledge-center/assets/image-2.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
