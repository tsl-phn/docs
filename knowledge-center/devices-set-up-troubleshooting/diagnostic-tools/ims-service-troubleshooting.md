---
title: "IMS service troubleshooting"
---

# IMS service troubleshooting

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

# IMS service troubleshooting

**IMS service troubleshooting**

****What is IMS?****

IMS services include:  
·        **VoLTE**: the ability to make calls using the 4G (or LTE) network  
·        **VoWiFi**: the ability to make calls using your home, office or public Wi-Fi, which is especially   
·        **SMSoIP:** the ability to send an SMS over the 4G/LTE or WiFi network  
  
Learn more about these services [here](../../services/volte-vowifi/ims-services-volte-vowifi-smsoip.md).

****What do I need to access VoIMS services?****

To enable VoIMS for a user, the requirements are:  
·        The “VoIMS service (VoLTE & VoWiFi)” is provisioned to ”on” via Auriga or API  
·        The user must have an IMS, VoLTE or VoWiFi compatible handset  
·        Handset settings must have IMS, 4G (or LTE) calling and Wi-Fi calling set to “on” (the naming and options may vary according to the handset and manufacturer)  
·        Handset settings must have 4G data set to on  
·        The 2G/3G/4G or 2G/3G/4G/5G service is provisioned to ”on” via Auriga or API  
·        The user must be in within 4G coverage, or in a Wi-Fi zone and connected to the Wi-Fi network  
  
Enable Wi-Fi calling on an Apple device: <https://support.apple.com/en-gb/HT203032>  
For android or other devices, check your manual.

****What if I can’t access VoIMS services?****

The above criteria must be fulfilled to access the services.  
Once the VoIMS service is provisioned, and the handset settings enabled, it is recommended to restart the handset to reattach to the network and to attach to the services that have recently been enabled.  
  
If VoWiFi is not working, go outside or to a zone with 4G coverage, disconnect Wi-Fi and test a call using VoLTE. If the calls go through correctly, there may be a problem with the Wi-Fi Router or its internet permissions (which must be resolved with your Wi-Fi provider).

****What happens if I can’t get 4G signal?****

When 4G is not available, your device will automatically pass calls through the 2G or 3G networks if you are within coverage.

****What happens if VoIMS suddenly stops working?****

Try following the following steps:  
·        Check that your handset is connected to 4G, with a good signal  
·        Turn off power saving mode: sometimes this mode stops background processes such as VoWiFi  
·        Check the settings on the handset have not been reset or disabled (such as by accident or a software update)  
·        Turn on aeroplane mode, wait a few seconds, and turn it back off again  
·        Restart the handset  
·        Reset network settings  
  
Reset network settings on an Apple device: <https://support.apple.com/en-gb/guide/iphone/iphea1c2fe48/ios>  
For android devices, check your manual.

**Do IMS services work in roaming?**

VoLTE and SMSoIP is supported in a limited number of countries, but the list is growing as new partnerships are deployed!  
  
VoWiFi is not supported in roaming.  
  
Find out more about IMS in Roaming by clicking [here](../../services/volte-vowifi/roaming-ims-services.md).

**What about 5G?**

VoNR (Voice over New Radio / also referred to as Voice over 5G or Vo5G) is not available. When connected to 5G, the device will fall back to 4G to make a phone call.

**What SPN is displayed when using VoWiFi?**

When using VoWiFi, the network name will appear as “EE-WiFi”. You will know that calls are going through WiFi when this network is displayed.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
