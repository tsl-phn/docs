---
title: "eSIM Troubleshooting"
---

# eSIM Troubleshooting

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

# eSIM Troubleshooting

**eSIM Troubleshooting**

If you are having problems downloading or activating an eSIM, please follow these steps below.

**Check that the eSIM is a “sales” eSIM (with a number attached) and that it hasn’t been scanned before**

Like physical SIMs, there are sales and swap esIMs. Find out more about sales and swap [here](https://docs.transatel.com/sim-management/checking-your-sim-cards-details/what-are-the-different-types-of-sim-sales-swap/). The QR code provided to a client must be a sales SIM with an MSISDN already paired with the eSIM.  
Transatel eSIMs can only be downloaded once. If the eSIM has already been scanned, a swap must be provided. The swap must be performed before providing the QR code for the new SIM. Find more about SIM swapping [here](../../sim-management/activate-or-change-sim-status/sim-swap.md).

**Check that the eSIM has been activated prior to scanning**

It is recommended to activate the SIM before downloading it onto the device. If the eSIM has not been activated, it will download onto the device, but remain stuck on “activating”. If this happens, first activate the SIM before rebooting the device: the eSIM should now display as “active”.

**Check that the device is connected to the internet**

eSIMs require an internet connection to be downloaded onto the device. Check the device is connected to a reliable WiFi signal, or in good coverage if using an existing provider. For example, try loading a web page successfully.

**Check the device is unlocked**

If the device is locked to an operator, the eSIM will probably not work. The subscriber must contact their previous operator to unlock the device.

**Check the software version. Make sure it is the latest one**

Handset manufacturers and OS providers often update their software to iron out bugs and issues. Some of these may be related to the eSIM. If the eSIM does not work or cannot be downloaded on a older version of the OS, it must be updated.

**Check that the device is GSMA eSIM compliant**

Only devices following the consumer eSIM protocol from the GSMA can use a Transatel eSIM. If the device uses a bespoke eSIM or similar, it may only work with the intended operator who provides SIMs to that specification (for example, the older generation of iPads which used the Apple SIM).

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
