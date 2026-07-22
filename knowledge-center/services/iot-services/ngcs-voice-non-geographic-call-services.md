---
title: "NGCS Voice (Non\u2011Geographic Call Services)"
---

# NGCS Voice (Non‑Geographic Call Services)

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

# NGCS Voice (Non‑Geographic Call Services)

## Overview

NGCS Voice (Non‑Geographic Call Services) allows subscribers to access premium voice services using long, non‑geographic numbers rather than shortcodes. In the UK, these services typically use number ranges such as 084, 087, 09, and 118, as defined in Ofcom’s National Numbering Plan.

NGCS Voice calls are routed to merchant‑operated platforms such as call centres, IVRs, or information services and are billed at premium rates.

This article explains what NGCS Voice is, how it works, and how charges are triggered at call level. It does not describe monthly spend caps, transaction limits, warnings, blocking rules, or reset logic. All spend limits, thresholds, notifications, and blocking behaviour are documented exclusively in the Payment Safeguarding article.

## How NGCS Voice Works

An NGCS Voice interaction consists of a voice call initiated by the subscriber to a non‑geographic number:

1. MO Voice Call (Mobile Originated)

The subscriber dials a non‑geographic premium number (for example, starting with 084, 087, 09, or 118).

- A voice access charge may be applied when the call is connected.
- A voice service charge may be applied either:
  - per call setup, and/or
  - per minute for the duration of the call.

Charges are typically billed per started minute, with no pro‑rata.

All charges are applied in real time while the call is in progress.

## Typical Use Cases

- Customer support and help lines
- Professional or technical advice services
- Directory enquiries (118 services)
- Information lines (travel, transport, or schedules)
- Entertainment or content services

## Key Characteristics

- Uses long non‑geographic numbers as defined by Ofcom
- Charges may include both access and service components
- Charging may be per call, per minute, or a combination of both
- Charges are initiated by the merchant’s service, not by the network
- Detailed voice call records are generated for billing and support

## Consumer Protection & Disputes

NGCS Voice services are regulated under UK Premium Rate Services rules and the Ofcom National Numbering Plan.

Merchants are responsible for presenting clear pricing information, managing call flows, and complying with Ofcom and PSA consumer‑protection requirements.

In the event of a dispute, the subscriber must first attempt to resolve the issue directly with the merchant operating the NGCS Voice service. If the dispute cannot be resolved with the merchant, the subscriber may escalate the complaint through Ofcom’s Premium Rate Services complaints process.

Independently of merchant processes, the MVNO must be able to bar NGCS premium voice services at network level upon subscriber request. When NGCS Voice is barred, no further NGCS calls can be made by that subscriber.

## Finding Retail Charges (NRT CDRs)

Retail charges for NGCS Voice calls are exposed in Near Real‑Time (NRT) Call Detail Records (CDRs). These records are the authoritative source for the retail price charged to the subscriber, including any applicable VAT.

For NGCS Voice, the NRT CDRs contain:

- A record for the voice access charge, if applicable
- One or more records representing the service charge, either per call or per minute

NRT CDRs are delivered to dedicated sFTP directories and can be used by the MVNO to generate subscriber billing, validate charges, and handle customer queries.

Wholesale CDRs should not be used to determine retail charges, as they are intended for wholesale reconciliation and exclude VAT.

## Refunds

Refunds for NGCS Voice services are uncommon. Where refunds do occur, they are typically initiated by the merchant and appear as negative charge entries in billing records.

Refunds do not re‑credit any monthly spend limits or cumulative usage controls.

## Availability & Limitations

- UK domestic usage only (not supported in roaming)
- Not compatible with Voice Convergence unless the MVNO provides its own termination and billing logic
- Compatible with prepaid services
- Call forwarding to NGCS premium numbers is not supported

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
