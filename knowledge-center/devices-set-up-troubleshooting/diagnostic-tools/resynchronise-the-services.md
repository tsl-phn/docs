---
title: "Resynchronise the services"
---

# Resynchronise the services

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

# Resynchronise the services

****Resynchronise the services****

**What is the option “Resynchronise the services”** Also known as the “Network Refresh” or “FUR/Full Refresh”, it is a little bit like “factory reset” on a network level, this button will re-provision all the services that have been provisioned on the SIM (via Auriga or API)  
  
**When is it recommended to use this option?**  
**Resending SPN**: When the MVNO’s Service Provider Name (SPN) is not displaying on the device. Since the SPN is received Over-the-Air (OTA), issues may arise if the SIM was not in the device, out of coverage, or the phone was turned off during the SPN reception process.  
**Network Problems**: When troubleshooting standard issues such as voice, SMS, or data problems with the SIM card, and traditional troubleshooting methods have failed to resolve the issues.  
  
/!\ **What are the subscriber impacts?**  
**Loss of Custom Configurations**: Any custom configurations, such as call forwarding rules, will be reset to their default settings.  
**Reboot Prompt**: The subscriber will receive a message prompting them to reboot their device after the operation is completed.  
**Display of MVNO SPN**: If the MVNO SPN was not previously displayed on the device, it should now be visible after the operation.  
  
**What are the best practices for using the option?**  
The refresh sometimes takes time, patience is key.  
If an operation exceeds its expected duration (too long than usual), feel free to raise a ticket for further investigation.  
We recommend advising end-users to restart their devices after each use of the option.  
  
**Where do I find this option?**  
After having chosen the SIM you wish to resynchronise, go to “Other actions” in the top right-hand corner:  
![image](/knowledge-center/assets/image-1.png)
You will then be prompted if you wish to proceed:  
![image](/knowledge-center/assets/image-2.png)
  
In summary, “Resynchronise the services” is a tool used to reset and re-provision all services associated with a SIM card to resolve network-related issues or resend OTA updates like the SPN. However, it should be used judiciously as it resets custom configurations and requires a device restart.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
