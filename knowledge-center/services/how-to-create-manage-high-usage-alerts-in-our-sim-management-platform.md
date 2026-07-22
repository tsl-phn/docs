---
title: "Creating High Usage Alerts"
---

# Creating High Usage Alerts

## Services

## [Service profiles​](service-profiles/README.md)

- [Changing Service Profiles](service-profiles/changing-service-profiles.md)
- [What is a Service Profile](what-is-a-service-profile.md)
- [Creating a Service Profile](how-to-create-a-service-profile.md)
- [What is a deviation from a Service Profile](what-is-a-deviation-from-a-service-profile.md)

## [Plans & Bundles](plans-bundles/README.md)

- [Adding Capped Bundles in Bulk](../uncategorized/adding-capped-bundles-in-bulk.md)
- [IoT Connect Capped Bundles](plans-bundles/iot-connect-capped-bundles.md)
- [Bundles with delayed activation](plans-bundles/bundles-with-delayed-activation.md)
- [How to subscribe to an Add-On Bundle](plans-bundles/how-to-subscribe-to-an-add-on-bundle.md)
- [Switching bundles during a month cycle](plans-bundles/i-want-to-switch-the-bundle-of-a-subscriber-during-the-month.md)
- [Managing Bundles from the SIM Management platform](plans-bundles/mvno-managing-bundles-from-the-sim-management-platform.md)
- [Pricing models of our IoT offers](plans-bundles/types-of-plans-and-bundles.md)
- [Understanding Pooled Bundles](plans-bundles/iot-understanding-pooled-bundles.md)
- [Adding SIM cards to a pooled bundle](iot-adding-sim-cards-to-a-pooled-bundle.md)
- [Understanding Capped bundles](iot-understanding-capped-bundles.md)
- [Adding a capped bundle to a SIM](iot-adding-a-capped-bundle-to-a-sim.md)
- [Managing capped bundles](iot-managing-capped-bundles.md)

## [High Usage and Subscriber protection](high-usage-and-subscriber-protection/README.md)

- [Alerting Cutoff](high-usage-and-subscriber-protection/alerting-cutoff.md)

- [Overspend Safeguarding](high-usage-and-subscriber-protection/overspend-safeguarding-osg.md)
- [All about Hiya protect](high-usage-and-subscriber-protection/all-about-hiya-protect.md)
- [SMS Spam Solution and Fraud Prevention](high-usage-and-subscriber-protection/sms-spam-solution-and-fraud-prevention.md)
- [Managing High Usage Rules](managing-high-usage-rules.md)
- [Creating High Usage Alerts](how-to-create-manage-high-usage-alerts-in-our-sim-management-platform.md)
- [High Usage File Report & Alert emails](high-usage-file-report-alert-emails.md)
- [New High Usage Alert Menu](high-usage-and-subscriber-protection/iot-new-high-usage-alert-menu.md)

## [Services & features](iot-services/README.md)

- [Premium Services](iot-services/premium-services.md)
- [NGCS Voice (Non‑Geographic Call Services)](iot-services/ngcs-voice-non-geographic-call-services.md)
- [Shortcode Voice](iot-services/shortcode-voice.md)
- [Premium SMS](iot-services/premium-sms.md)
- [About SMS Recording](iot-services/about-sms-recording.md)
- [Roaming Alerts](iot-services/raoming-alerts.md)
- [SIM Card Artwork](iot-services/sim-card-artwork.md)
- [How to use the IMEI Lock feature](iot-services/how-to-use-the-imei-lock-feature.md)
- [Default Services](iot-services/default-services.md)
- [The Sleep Mode (Tariff Holiday) - IoT optional status](../glossary/sim-lifecycle-glossary/the-sleep-mode-tariff-holiday-iot-optional-status.md)
- [the Test Mode for IoT SIMs](iot-services/the-test-mode.md)
- [Data Safeguarding](data-safeguarding.md)
- [Key shortcodes](iot-services/key-shortcodes.md)
- [Smart Barring](iot-services/smart-barring.md)
- [Select the radio types (2G, 3G, LTE) of your SIMs](iot-select-the-radio-types-2g-3g-lte-of-your-sims.md)
- [Network Coverage Selection](iot-services/iot-network-coverage-selection.md)

## [Data & coverage](data-coverage/README.md)

- [VoLTE Roaming Footprint](data-coverage/volte-roaming-footprint.md)
- [Data Content Filtering/Parental Controls](data-coverage/data-content-filtering-parental-controls.md)
- [How to activate 5G for my SIM base?](how-to-activate-5g-for-my-sim-base.md)
- [How do I include a coverage checker on my website?](data-coverage/mvna-uk-how-do-i-include-a-coverage-checker-on-my-website.md)
- [Our 5G roaming footprint](data-coverage/mvno-uk-our-5g-roaming-footprint.md)
- [Access to the 5G network](data-coverage/access-to-the-5g-network.md)

## [Static IP solutions](https://docs.transatel.com/services/static-ip-solutions/)

- [All about Static IP](../uncategorized/all-about-public-static-ip.md)
- [How to find your SIMs' static IP?](how-to-find-your-sims-static-ip.md)
- [How to activate the Static Public IP option on a SIM?](mvno-how-to-activate-the-static-public-ip-option-on-a-sim.md)

## [VoLTE / VoWIFI](volte-vowifi/README.md)

- [Voicemail Notifications](volte-vowifi/voicemail-notifications.md)
- [VoLTE Roaming Footprint](data-coverage/volte-roaming-footprint.md)
- [IMS service (VoLTE/VoWiFi/SMSoIP)](volte-vowifi/ims-services-volte-vowifi-smsoip.md)
- [Roaming IMS Services](volte-vowifi/roaming-ims-services.md)

## On this page

# Creating High Usage Alerts

****Creating High Usage Alerts****

You can create rules to monitor your fleet’s usage in our interface.  
  
**Key details of the rules system:**  
–          Our system runs the rules **every hour**, and the counters are reset each beginning of each calendar month.  
–          Rules are usage based: data volume, SMS sent, voice minutes or amount charged…  
–          If a rule is triggered, the system can send alert emails, generate a file report and/or suspend the SIM.  
–          You can filter which SIMs the rules will be applied to according to [Service Profiles](https://docs.transatel.com/services-setup/what-is-a-service-profile/), Rate Plans or Billing Options  
–          Rules can be configured through API requests  
  
![image](/knowledge-center/assets/image-1.png)
  
The High Usage menu is accessible in **Tracking & reports** > **Set Automation rules**  
  
![image](/knowledge-center/assets/image-2.png)
  
To create a new rule, click on “add a rule” at the top right  
  
![image](/knowledge-center/assets/image-3.png)
  
You can now configure the following in the new window.  
  
Here is an overview of each section of the window:  
  
**Rule**  
•       Rule name: it must be unique to your account  
•       Activate rule: activate or deactivate the rule if you do not want it implemented now  
![image](/knowledge-center/assets/image-4.png)
**Please make sure that you activate the rule upon creating it, otherwise it will not be implemented**  
**Usage limit:**  
•       Type of usage: depends on the Rate Plans available on your account – data, SMS, voice, amount charged…  
•       Volume: defines the threshold  
  
![image](/knowledge-center/assets/image-5.png)
Below are a few examples and explanations for the “type of limit” criteria:  
*All airtime*: all voice, SMS, data, MMS usage which may be national, international or roaming  
*All national data*: all data used in the home country of the SIM  
*All data usage:* all data used, regardless of the originating country  
  
**Actions**  
You can select “Line suspension” for the automated suspension of the line when the volume is reached.  
  
**Alerts**  
•       *SFTP file notification*: files are deposited on your SFPT every hour – and can be accessed easily from the SIM Management Platform (in Tracking & Reports >Report Files)  
•       *Email notification*: an email notification is sent when trigger is reached. A file is attached to the Email (the same as deposited on the SFTP)  
•       *Repeat alerts*: if this option is selected, you will receive the notification for each affected line every time the rule runs. If it is deactivated, the HU Rule runs for a line until the threshold is reached. Then the Rule will not run again for this line until the end of the month. This parameter is mandatory with “Line suspension” and is automatically activated when “Line suspension” is “Active”.  
  
![image](/knowledge-center/assets/image-6.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
