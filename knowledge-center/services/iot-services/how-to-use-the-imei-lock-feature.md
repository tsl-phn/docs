---
title: "How to use the IMEI Lock feature"
---

# How to use the IMEI Lock feature

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

# How to use the IMEI Lock feature

**IMEI Lock feature**

Our IMEI Lock feature will enable you to prevent fraudulent usage if one of your SIMs is stolen, and that the “thief” tries to use it in another device.  
  
This article will explain how to use the feature, its current limitations, as well as guidelines to understand fully the service.  
  
**The feature is currently deployed on select IoT offers only. If you do not see the “IMEI Management” drop down list in your offer, please contact your Account Manager for further information.**

**Limitations of the IMEI Lock**

Before we start, please note the following limitations of the feature:  
  
– **Restricting blocking to data sessions:** The use of the RADIUS protocol for this feature limits blocking via IMEI recognition to data sessions only. As a result, t**his feature does not block the use of voice and SMS services**.  
  
– **Limited to the 1st IMEI detected:** To offer our customers an intuitive experience while limiting the risk of errors, the IMEI is automatically recognized and saved.   
You will not be able to enter and associate a predefined list of IMEIs or TAC.  
You can however remove the IMEI lock, and pair the SIM with a new device if required.  
  
**– Not recommended for frequent IMEI changes**  
This feature is not meant if a new IMEI is to be paired frequently. It is made for use-cases where the SIM is supposed to stay “forever” in its device, with possible, infrequent changes.  
In case of repeated changes in the same 24/48h timeframe there is a possibility that an old saved IMEI can stay stored in the network, while the new IMEI would be saved, meaning that any new device encounter will not accept a data session.  
  
– **No IMEI change alert**: for the first version of the feature, we will not send alerts if we detect an unauthorized IMEI.  
This is coming in the near future 🙂

**How to use the feature**

The IMEI Lock comes as a drop-down list in your offer, named “IMEI Management”  
By default, the IMEI Lock option is set to “Disabled”, which means that the SIM can work in any device.  
  
![image](/knowledge-center/assets/image-1.png)
  
The option has 3 other values:  
  
![image](/knowledge-center/assets/image-2.png)
  
***IMEI Lock*** ***is disabled*** : This means allowing data sessions to be opened on all devices where it is inserted. No equivalence check between the saved IMEI and the presented IMEI is performed by RADIUS.  
  
***IMEI Lock is enabled*** : When the IMEI Lock is enabled for the first time, no IMEI has been registered beforehand. The first IMEI encountered is then saved, and the SIM is “locked” to this IMEI. From then on, the RADIUS checks the equivalence between the saved IMEI and the presented IMEI, authorizing the data session only if the presented IMEI matches that of the first device encountered.  
  
***IMEI Pairing*** : When the SIM is changed to the “IMEI Pairing” state, the data session is authorized by RADIUS as in the “IMEI Lock OFF” state, without any equivalence check.   
While in this value, each time the SIM is inserted into a device, its saved IMEI is replaced by that of the current device.  
The purpose of this value is to allow the saved IMEI to be modified, so that you can then switch back the SIM in “IMEI Lock ON” status.   
*Please see below for a detailed step-by-step on how to change the IMEI*

**Timing of the feature**

As the activation of the feature is a provisioning actions, you must wait until the request is processed for it to be working.  
This means that  
– if you are activating the SIM, the IMEI Lock will not be “on” until the activation is processed  
– if you are changing the value of the service (via Service Profile or directly for the SIM), you must wait until you see that the change has been successfully processed.   
  
![image](/knowledge-center/assets/image-3.png)

****If you want to pair with a new IMEI:****

1. Switch to “IMEI Pairing” and wait until the change is processed  
2. Insert the SIM in the new device and make some data traffic so that the new IMEI is stored  
3. Then switch the SIM back to IMEI Lock, and wait until the change is processed – the SIM will now be locked to the new IMEI

**Pricing**

Based on your contract, you may have a monthly fee per SIM applied if the option is activated on one of your SIMs.  
The fee is charged only when you apply the IMEI Lock, as stated in the label “extra fees apply”  
There is no fee applied to SIMs while “IMEI Lock is disabled” or “IMEI Pairing” are applied.  
The fee is only charged once, if you change the value multiple times during the month, the fee will only be applied once  
  
![image](/knowledge-center/assets/image-4.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
