---
title: "Roaming data troubleshooting"
---

# Roaming data troubleshooting

## Devices Set up & Troubleshooting

## [Diagnostic tools](README.md)

- [Understanding the “Data Safeguarding” Mechanism](comprendre-le-mecanisme-data-safegarding-2.md)
- [Incident Classification](classification-des-incidents.md)
- [Mandatory Information to Open a Ticket](informations-obligatoires-pour-ouvrir-un-ticket.md)
- [Troubleshooting Data Connectivity Issues](resolution-de-probleme-lies-a-la-connectivite-data.md)
- [SIM Status Verification](../verification-du-statut-de-la-sim.md)
- [eSIM Troubleshooting](esim-troubleshooting.md)
- [Resynchronise the services](resynchronise-the-services.md)
- [IMS service troubleshooting](ims-service-troubleshooting.md)
- [Roaming data troubleshooting](roaming-data-troubleshooting.md)
- [Data session diagnostic tool](data-session-diagnostic-tool.md)
- [Network attach diagnostic](../../sim-management/network-attach-diagnostic.md)

## [[IoT] Inter-operable devices](../iot-inter-operable-devices/README.md)

- [Introduction to SIM-Device testing Program](../iot-inter-operable-devices/introduction-to-sim-device-testing-program.md)
- [Tested and Compatible Devices](../tested-and-compatible-devices.md)
- [Compatible Modules](../compatible-modules.md)

## [Device Configuration](../device-configuration/README.md)

- [eSIM Troubleshooting & Best Practices](../device-configuration/bonnes-pratiques-de-diagnostic-esim.md)
- [Internet & MMS access settings](../device-configuration/internet-hotspot-mms-access-settings.md)
- [How to use the IMEI Lock feature](../../services/iot-services/how-to-use-the-imei-lock-feature.md)
- [UK MVNO mobile internet and MMS APN settings](../device-configuration/uk-mvno-mobile-internet-and-mms-apn-settings.md)
- [Configuring your device for our IoT SIM cards](../device-configuration/iot-configuring-your-device-for-our-iot-sim-cards.md)

## [Service Desk Templates](../service-desk-templates/README.md)

- [CDR Delivery Template](../cdr-delivery-template.md)
- [Mobile Switching template](../service-desk-templates/mobile-switching-template.md)
- [Roaming Template](../service-desk-templates/roaming-template.md)
- [Welcome SMS / Roaming template](../service-desk-templates/welcome-sms-roaming-template.md)
- [Voicemail Access template](../service-desk-templates/voicemail-access-template.md)
- [Porting Issue template](../service-desk-templates/porting-issue-template.md)
- [Subscriber Provisioning / Service Orders template](../service-desk-templates/subscriber-provisioning-service-orders-template.md)
- [SIM Swap template](../service-desk-templates/sim-swap-template.md)
- [Voice/SMS/Data template](../service-desk-templates/voice-sms-data-template.md)

## On this page

# Roaming data troubleshooting

**Roaming data troubleshooting**

We will go through a few steps to troubleshoot a device that has no access to data in roaming

**Did this device & SIM work nationally?**

If the SIM didn’t work on the national network before going into roaming, the problem is probably with the SIM configured services / device settings, and nothing to do with roaming.  
Check the national troubleshooting first.

**Check that the phone is attached to a network**

Your phone should show at the top of the screen or under the network settings:   
– it is connected to a network   
– good signal strength (warning: if only 1-2 bars an internet page may take a while to load)   
– The technology (2G, 3G, 4G or 5G). If using 2G, data may take a very long time to load. Under 3G, things should be fairly quick (warning: many countries and networks are decommissioning 3G). With 4G/5G and a good signal, internet pages should load almost immediately.   
  
If you’re not showing a network or good signal and technology, you can try:  
– Toggling the network on and off  
– Manually search for a network: you test several different ones to see if one works or works better than the others   
– Turn the device on and off  
– Move to a different area where there is good reception (either use the coverage checker of a local operator, or check another device  
– Soft reset the device or reinitialise network settings

**Roaming with capped bundles**

If you are an MVNO which has subscribed to capped bundles, there are several points to check.  
Firstly, check that the subscriber has remaining balance in their bundle resources (these are decremented – once it his 0, they’re capped!). Secondly, check with that they’re located in a country which is allowed in the bundle.  
Roaming voice, SMS and data are blocked in certain zones by default to prevent bill shock. The subscriber must purchase a Daily Roaming Pass to have access to data by sending an SMS to 1250.   
Otherwise, you can provision the subscriber to “Tiered data” to give them access to open-bar data nationally and in roaming.

**Provisioned “Configured Services”**

Using our SIM Management platform, you should check that the SIM has been provisioned with:   
– Data technology: should be set as *3G/4G/5G* to guarantee access. *3G/4G* should be okay as well, but the user won’t have access to 5G. *2G/3G* may have some restrictions in countries where 3G networks have been decommissioned.   
– *Roaming Voice, SMS and Data Open from All Zones* or *Roaming Voice, SMS and Data Open from Zones 1 Only* (if roaming in the EU and continue to block access extra-EU) to open roaming services.

**Data safeguarding**

Transatel’s data safeguarding solution may have stepped in to prevent the subscriber from bill shock. This will block access to roaming data to prevent the subscriber from going over £45 of roaming data usage.   
The subscriber will have received an SMS informing them that they have hit 80% of the threshold, and again when they have reached the threshold. They are prompted to reply “OK data” to acknowledge the charge and to continue using data.   
You can check if this has been hit on the check-up:   
![image](assets/image-1.png)   
Alternatively, it will also show on the Plans and Options tab:   
![image](assets/image-2.png)   
Here, you also have options to open the data access back up.   
  
More information on Data Safeguarding can be found [here](https://docs.transatel.com/services-setup/data-safeguarding/).

**APN Settings**

Even in roaming, the national APN settings still apply. Check that your device has the right APN settings found [here](../device-configuration/uk-mvno-mobile-internet-and-mms-apn-settings.md).

**WiFi**

Turn the WiFi off: sometimes the phone will be connected to a WiFi network which is defective. Turn WiFi off to see if you are experiencing an issue with the mobile network.   
For example, if you have arrived by aircraft, some planes provide their own WiFi network that may not work when grounded or may require an internet package to be purchased to access the internet.

**Handset settings**

Sometimes the handset has been configured to disallow access to roaming data. This can be different per device – check with the handset manufacturer for a complete guide on what options are available   
Most commonly, we have:   
– Apple: <https://support.apple.com/en-us/HT201643#:~:text=In%20the%20Settings%20app%2C%20tap,Turn%20off%20Data%20Roaming>.   
– Android: Open your Settings app and tap **Network and Internet** or **Connections**. Depending on your device, these options may be different.

**Russia**: temporary measures

Due to recent restrictions put into place by the Russian government, data and SMS will be barred for the first 24 hours upon network attach. If no activity is detected, the bar will be reinstated. Voice calls are not affected.

It is **not** recommended for Subscribers to manually switch networks, as this will start the process again with the subsequent Russian operator.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
