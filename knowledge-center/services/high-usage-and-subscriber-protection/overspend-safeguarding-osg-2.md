---
title: "Overspend Safeguarding (OSG)"
---

# Overspend Safeguarding (OSG)

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

# Overspend Safeguarding (OSG)

****What is Overspend Safeguarding (OSG)?****

OSG is a real-time spend-control feature designed for Pay Monthly mobile subscriptions. It allows Service Providers to set a maximum out-of-bundle (OOB) spend limit for each subscriber. Once this limit (called the OSG Cutoff) is reached, any additional OOB usage is automatically blocked. This helps prevent unexpected charges and ensures compliance with Ofcom’s bill-shock regulations.

****How does OSG work in practice?****

OSG operates through Transatel’s Online Charging System (OCS), which monitors subscriber usage in real time. When a subscriber uses services outside their bundle (e.g., extra data or roaming), these charges accumulate in the OSG “Charged” balance. If the Charged balance reaches the predefined Cutoff, OSG instantly blocks further OOB usage. This mechanism applies across national and roaming data, international calls, and SMS.

****Can subscribers still buy add-ons or roaming bundles when OSG is active?****

Yes. If an add-on or roaming bundle is purchased, usage will first deduct from that bundle before impacting the OSG Charged balance. This means subscribers can continue to manage their usage without disabling OSG.

****How can Service Providers manage OSG?****

OSG can be managed via:

- **Auriga Web Interface:** Activate/deactivate OSG, set Cutoff values, view Charged balance, and adjust renewal dates.
- **OCS-API & Webhooks:** Automate OSG management and receive real-time notifications for events like activation, renewal, or reaching 80%/100% of the Cutoff.

**What happens when the OSG Cutoff is reached?**

Once the Cutoff is reached:

- All OOB usage (data, roaming, international calls/SMS) is blocked.
- Premium services in the UK remain available and unlimited.
- Roaming premium services are blocked.
- Subscribers receive an SMS notification informing them that their spend cap has been reached.

**Are subscribers notified about their OSG status?**

Yes. Transatel sends SMS alerts at key thresholds:

- **80% of Cutoff:** “You have used 80% of your mobile bill limit.”
- **100% of Cutoff:** “Your mobile bill limit has been reached and services with additional charges are no longer available.”  
  MVNOs can also create custom notifications using webhook events.

**Is OSG compatible with other options like Data Safeguarding (DSG)?**

Yes. OSG and DSG can run together.

**What happens if OSG is disabled?**

Disabling OSG removes all spend protection. All OOB usage becomes unrestricted (“open bar”), which can lead to high bills if not monitored.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
