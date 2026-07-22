---
title: "About SMS Recording"
---

# About SMS Recording

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

# About SMS Recording

## **What is SMS Recording?**

SMS Recording is a feature that provides Service Providers with a **near real‑time copy** of their subscribers’ incoming and outgoing SMS messages. These copies are delivered securely via **SMPP** and allow for compliance, analysis, or integration into broader communication tools.

## **How does SMS Recording work?**

Once activated for a subscriber, Transatel receives a copy of each eligible SMS after it has been delivered by the network and forwards it to the Service Provider through a secure SMPP connection. The original SMS delivery is *not* affected.

## **Why would a Service Provider use SMS Recording?**

Common use cases include:

- **Regulatory compliance**, especially in sectors such as finance
- **Multi‑device access**, enabling SMS copies to appear on desktops or unified comms apps
- **Enhanced FMC services**, integrating SMS history into communication platforms

## **Which SMS types are included?**

The feature covers most **P2P SMS traffic**, including:

- On‑net & off‑net SMS
- Super on‑net SMS
- International SMS
- Network and premium/shortcode SMS
- A2P SMS

## **Which SMS types are *not* included?**

Some messages cannot be copied, including:

- Emergency SMS (999 / 112)
- Silent SMS (e.g., RCS activation, AML location, SPN updates)
- SMS sent using RCS instead of the traditional SMS protocol
- OTA SMS
- MMS
- OTT messages (WhatsApp, iMessage, etc.)

## **What do I need to activate SMS Recording?**

A Service Provider must have:

- A **secure SMPP 3.1/3.4/5.0 connection** with Transatel
- The feature **activated per SIM** via Auriga or the Connectivity Management API

## **Is subscriber consent required?**

Yes. The MVNO must ensure that it has the appropriate **lawful basis** (such as consent or regulatory obligation) before activating SMS Recording.

## **Will SMS Recording impact CDRs or generate extra charges?**

No changes occur to CDRs, and there is **no additional wholesale charge** for SMS copies.

## **Will I receive SMS copies in real time?**

Yes. SMS Records are delivered in **near real‑time** over the SMPP link, typically at the same moment the original SMS reaches the end user.

## **Why might I not be receiving SMS copies?**

Common causes include:

- **RCS is enabled** on the end‑user device (SMS is then sent as data rather than via the SMSC)
- The subscriber **does not have SMS Recording activated**
- The **SMPP link is unavailable**

## **Can the same SMS be copied twice?**

No. If both sender and receiver are on the same fleet, Transatel sends **only one SMS copy** to avoid duplication.

## **Can I use an API instead of SMPP?**

Not currently. SMPP is the standard supported interface, but alternative methods can be evaluated via Change Request.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
