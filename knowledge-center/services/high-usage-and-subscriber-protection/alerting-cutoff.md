---
title: "Alerting Cutoff"
---

# Alerting Cutoff

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

# Alerting Cutoff

## What is Alerting Cutoff?

Alerting Cutoff is Orange’s roaming data protection mechanism designed to prevent excessive out-of-bundle charges when subscribers use mobile data abroad. It applies to all MVNO subscriber lines hosted on the Orange network.

The mechanism monitors roaming data consumption and automatically:

- Warns subscribers when they are approaching a predefined threshold.
- Suspends mobile data usage once the maximum threshold is reached.
- Requires explicit consent before data roaming can continue.

## Why does Alerting Cutoff exist?

European regulations require operators to protect subscribers from excessive roaming charges outside regulated European roaming zones.

The regulatory spending limit is set at **€50 excluding VAT**. Once the corresponding threshold is reached, the subscriber must explicitly consent before continuing to use mobile data while roaming.

## How does Alerting Cutoff work?

The Alerting Cutoff mechanism operates in two stages:

### Step 1 – Alert at 80%

When a subscriber reaches **80% of the applicable roaming threshold**, an SMS notification is sent.

**SMS message**

> > ```
> > Vos consommations Data à l'étranger sont facturées hors forfait. Par mesure de prévention, votre session pourra être interrompue.
> > ```

### Step 2 – Cutoff at 100%

When a subscriber reaches **100% of the threshold**, Orange:

- Sends a second SMS notification.
- Suspends data roaming services.

**SMS message**

> > ```
> > Vous avez été déconnecté afin de prévenir tout risque de facturation excessive. Vous pouvez vous reconnecter en débloquant votre ligne sur la page de redirection à partir de votre navigateur.
> > ```

## What are the roaming data thresholds?

The thresholds vary depending on the roaming zone. They are configured to correspond to the regulatory spending limit while taking into account the cost of data in each destination.

| Roaming Zone | 80% Alert | 100% Cutoff |
| --- | --- | --- |
| Europe (Zone 1) | 8,000 MB | 10,000 MB |
| Switzerland & Andorra (Zone 2) | 3,600 MB | 4,500 MB |
| Maghreb & Turkey (Zone 3) | 266 MB | 333 MB |
| USA & Canada (Zone 4) | 800 MB | 1,000 MB |
| Rest of World (including French Polynesia, Wallis & Futuna and New Caledonia) (Zone 5) | 40 MB | 50 MB |
| Satellite & Maritime Networks (Zone 6) | 1.6 MB | 2 MB |

## Why are thresholds different for each zone?

Data roaming costs vary significantly depending on the destination and network type.

For example:

- European roaming destinations allow much larger volumes of usage before reaching the regulatory limit.
- Satellite and maritime networks are significantly more expensive, resulting in much lower thresholds.
- The thresholds are designed to ensure compliance with the €50 regulatory cap.

## What happens when a subscriber reaches 100% of the threshold?

Once the 100% threshold is reached:

- The subscriber receives a cutoff SMS.
- Mobile data roaming is suspended.
- The subscriber can no longer use data services while roaming until the restriction is removed.

Voice and SMS services are not impacted by the Alerting Cutoff mechanism (subject to standard roaming service availability).

## How was Alerting Cutoff managed previously?

Historically, subscribers who reached the cutoff threshold could restore data services themselves through an Orange-hosted web portal.

However, following changes to Orange’s platform, this self-service web page is no longer available. Subscribers can therefore no longer remove the restriction autonomously.

## How can a blocked subscriber be unblocked?

MVNOs can now unblock subscribers directly from Auriga thanks to the integration of Orange’s Alerting Cutoff API.

This allows authorized users to remove the restriction on behalf of the subscriber without requiring access to the historical Orange self-service portal.

## How do I perform a roaming data unblock in Auriga?

1. Open the subscriber record in Auriga.
2. Click **Other Actions**.
3. Select **Unblock roaming data usage**.
4. Confirm the action.

![image](/knowledge-center/assets/image-1.png)

The request is sent to Orange and the roaming data restriction is removed.

## Who can perform the unblock action?

Only users with the **Fleet Manager** role can perform the **Unblock roaming data usage** action in Auriga.

If the option is not visible, please verify your permissions or contact your administrator.

## When should a subscriber be unblocked?

A subscriber should only be unblocked when:

- The Alerting Cutoff threshold has been reached.
- The subscriber wishes to continue using mobile data while roaming.
- The subscriber understands that additional roaming charges may apply.

## Does the unblock action reset usage counters?

No.

The unblock action only lifts the roaming data restriction. It does not reset the subscriber’s roaming consumption counter.

Once the unblock has been performed, the Alerting Cutoff mechanism will not trigger again during the current calendar month, regardless of additional roaming data consumption.

The roaming usage counter is automatically reset at the beginning of the next calendar month, at which point the Alerting Cutoff protection becomes active again.

## Does Alerting Cutoff apply to all subscribers?

Yes.

Alerting Cutoff is operated by Orange on all MVNO subscriber lines and applies whenever roaming data usage is subject to the roaming protection mechanism.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
