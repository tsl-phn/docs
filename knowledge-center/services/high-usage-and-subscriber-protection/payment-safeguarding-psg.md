---
title: "Payment Safeguarding (PSG)"
---

# Payment Safeguarding (PSG)

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

## [High Usage and Subscriber protection](README.md)

- [Alerting Cutoff](alerting-cutoff.md)

- [Overspend Safeguarding](overspend-safeguarding-osg.md)
- [All about Hiya protect](all-about-hiya-protect.md)
- [SMS Spam Solution and Fraud Prevention](sms-spam-solution-and-fraud-prevention.md)
- [Managing High Usage Rules](../managing-high-usage-rules.md)
- [Creating High Usage Alerts](../how-to-create-manage-high-usage-alerts-in-our-sim-management-platform.md)
- [High Usage File Report & Alert emails](../high-usage-file-report-alert-emails.md)
- [New High Usage Alert Menu](iot-new-high-usage-alert-menu.md)

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

## [VoLTE / VoWIFI](../volte-vowifi/README.md)

- [Voicemail Notifications](../volte-vowifi/voicemail-notifications.md)
- [VoLTE Roaming Footprint](../data-coverage/volte-roaming-footprint.md)
- [IMS service (VoLTE/VoWiFi/SMSoIP)](../volte-vowifi/ims-services-volte-vowifi-smsoip.md)
- [Roaming IMS Services](../volte-vowifi/roaming-ims-services.md)

## On this page

# Payment Safeguarding (PSG)

## Overview

Payment Safeguarding (PSG) is a network‑level spend‑control mechanism that protects subscribers from excessive charges on Premium Services, including Premium SMS, Shortcode Voice, and NGCS Voice.

PSG enforces regulatory spend limits in real time. It operates independently of service barrings and merchant controls.

This article explains what PSG is, how it works, what limits apply, and how blocking and notifications behave.

## What PSG Applies To

PSG applies cumulatively across all Premium Services:

- Premium SMS
- Shortcode Voice
- NGCS Voice

All qualifying charges (service & access charges) count toward the same monthly PSG balance.

## How PSG Works

Each time a subscriber attempts to use a Premium Service, a real‑time authorisation check is performed against the subscriber’s PSG balance.

- If sufficient PSG balance is available, the service is allowed and the charge is deducted in real time.
- If the PSG balance is exhausted, the service attempt is rejected and no charge is applied.

For voice calls, PSG is enforced while the call is in progress. Calls are automatically terminated when a transaction limit is reached.

## Spend Limits

### Monthly Spend Cap

- £240 per month across all Premium Services
- The cap is fixed and not customisable
- Once reached, all Premium Services are blocked until the next reset

### Warning Threshold

- 80% of the monthly cap (£192)
- When crossed, the subscriber is notified automatically

### Per‑Transaction Limit

- £40 maximum per transaction
- Applies to both Premium SMS and Premium Voice
- Voice calls are disconnected automatically upon reaching this limit

## Reset & Renewal

The PSG balance resets automatically based on the subscriber’s configured renewal date:

- Default renewal date: 1st of each month (but can be modified)
- The balance resets to £0 charged at renewal

If the renewal date falls between the 29th and 31st, the next reset occurs on the 1st of the following applicable month.

## Blocking Behaviour

When the monthly PSG cap is reached:

- All Premium SMS (MO and MT) are blocked
- All Shortcode Voice calls are blocked
- All NGCS Voice calls are blocked

Blocking remains in place until the next PSG reset, unless the option is manually modified.

## Notifications & Events

Subscribers receive automatic SMS notifications for the following events:

- PSG activated or deactivated
- Warning threshold reached
- Monthly spend cap reached

Each event also generates a webhook that the MVNO may consume for customer care or monitoring purposes.

## Relationship with Barrings

Network barrings take precedence over PSG:

- If Premium Services are barred, no traffic is generated and PSG is not incremented
- PSG does not override barrings

Barrings and PSG may be used together as complementary controls.

## Refunds & PSG Balance

Refunds do not restore PSG balance.

If a refund is applied:

- The charge appears as a negative value in billing records
- The refunded amount is not deducted from the PSG balance if refund falls outside of the current period.

This prevents subscribers from exceeding the monthly cap through refunds posted in later periods.

## Scope Limitations

- PSG applies only to Premium Services
- PSG does not apply to standard voice, SMS, or data usage
- PSG is separate from prepaid credit controls

## Summary

Payment Safeguarding (PSG) provides mandatory, real‑time spend protection across all Premium Services. It ensures regulatory compliance, protects subscribers, and gives MVNOs a consistent control framework that operates independently of merchant behaviour.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
