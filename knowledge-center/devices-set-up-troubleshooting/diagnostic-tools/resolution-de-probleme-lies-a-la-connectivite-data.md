---
title: "Troubleshooting Data Connectivity Issues"
---

# Troubleshooting Data Connectivity Issues

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

# Troubleshooting Data Connectivity Issues

Below are the steps to follow, in order, when a user reports a **data connection outage or instability**.  
Start with the simplest checks before investigating configuration or platform-related causes.

### Steps

### 1. Basic device-side checks

Ask the user to:

- Disable and then re-enable airplane mode
- Verify that mobile data is enabled
- Ensure the correct SIM is selected for data usage (dual SIM devices)

### 2. Check SIM status

Apply the steps described in **“SIM Status Verification”**.

👉 **Do not proceed** if the SIM is inactive or if no subscription is associated.

### 3. Restart the device

- Power off the device completely for **30 seconds**
- Turn it back on

👉 This helps force reconnection to the network.

### 4. Check APN configuration

Incorrect APN settings are a common cause of data issues.

Verify that:

- The APN name is correct (no spaces, no case errors)
- The authentication type is correct
- The APN profile is properly saved and selected

Refer to the APN configuration article  
(*Internet access settings, tethering and MMS*).

### 5. Perform a cross-test

- Test the SIM in another device
- Test another SIM in the same device

👉 Record the results with **date and time**.

### 6. Check network and signal

Ensure that:

- The device displays network coverage (not “No service”)
- The operator name is visible
- The selected network mode is compatible with the area  
  (e.g. not restricted to 5G in a 4G-only area)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
