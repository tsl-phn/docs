---
title: "Premium SMS"
---

# Premium SMS

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

# Premium SMS

## Overview

Premium SMS allows subscribers to interact with services provided by third‑party merchants using short numerical shortcodes (typically 3–6 digits). These interactions are commonly used for voting, charity donations, subscriptions, alerts, and other value‑added services.

This article explains what Premium SMS is, how it works, and how charges are triggered at message level. It does not describe monthly spend caps, transaction limits, warnings, blocking rules, or reset logic. All spend limits, thresholds, notifications, and blocking behaviour are documented exclusively in the Payment Safeguarding article.

## How Premium SMS Works

A Premium SMS interaction usually consists of two distinct steps:

### MO SMS (Mobile Originated)

The subscriber sends an SMS to a shortcode.

- The SMS may be free, or
- Charged at the standard network SMS rate (not usually included in bundles)

### MT SMS (Mobile Terminated)

The merchant sends one or more reply messages containing the paid service.

- Each MT SMS may carry a service charge set by the merchant
- Multiple MT messages may generate multiple charges

Charges are applied in real time as the messages are sent or received.

## Typical Use Cases

- TV and media voting
- Charity donations
- One‑off purchases
- Subscriptions and recurring services
- Alerts and informational content
- Marketing campaigns
- Authentication (OTP / MFA)

## Key Characteristics

- Uses short numerical codes (typically 3–6 digits)
- Supports one‑off and recurring charging models
- Charges are initiated by the merchant, not the network
- Detailed Premium SMS records are generated for billing and support

## Opt‑In, Opt‑Out & Consumer Protection

Premium SMS services are regulated under UK Premium Rate Services rules and must provide clear mechanisms for consent, stopping services, dispute resolution, and escalation.

A subscriber can stop an individual Premium SMS service at any time by sending STOP to the shortcode that is charging them. Where supported by the merchant and aggregator, a subscriber may also be able to send STOP ALL to the provider’s dedicated opt‑out shortcode, which is separate from the charging shortcode, to stop all Premium SMS services associated with that provider.

Merchants are fully responsible for managing opt‑in flows, subscription life‑cycles, pricing transparency, and compliance with Ofcom and PSA consumer‑protection requirements. This includes ensuring that subscribers are clearly informed of charges, whether services are recurring, and how to stop them.

In the event of a dispute, the subscriber must first attempt to resolve the issue directly with the merchant providing the Premium SMS service. If the subscriber is unable to resolve the dispute with the merchant, they may escalate the complaint through Ofcom’s Premium Rate Services complaints process.

Independently of merchant controls and dispute processes, the MVNO must be able to bar Premium SMS services at network level upon subscriber request. When Premium SMS is barred by the MVNO, no further Premium SMS charges can be generated for that subscriber, regardless of merchant behaviour.

## Finding Retail Charges (NRT CDRs)

Retail charges for Premium SMS are exposed in Near Real‑Time (NRT) Call Detail Records (CDRs). These records are the authoritative source for the retail price charged to the subscriber, including any applicable VAT.

For Premium SMS, the NRT CDRs contain:

- A record for the MO SMS, showing whether the outbound message was free or charged at the standard network SMS rate.
- One or more records for the MT Premium SMS, each containing the service charge applied by the merchant.

NRT CDRs are delivered to dedicated sFTP directories and can be used directly by the MVNO to generate subscriber billing, perform charge validation, and handle customer queries.

Wholesale CDRs should not be used to determine retail charges, as they are designed for wholesale reconciliation and exclude VAT.

## Refunds

Refunds are rare but can occur in limited circumstances, for example:

- The subscriber is unreachable and the charged MT SMS cannot be delivered
- A merchant explicitly issues a refund

Refunds appear as negative charges in billing records. Refunds do not re‑credit any monthly spend limits.

## Availability & Limitations

- UK domestic usage only (not supported in roaming)
- Compatible with prepaid services, Voice Convergence & SMS recording

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
