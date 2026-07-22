---
title: "SIM Status Verification"
---

# SIM Status Verification

## Devices Set up & Troubleshooting

## [Diagnostic tools](diagnostic-tools/README.md)

- [Understanding the “Data Safeguarding” Mechanism](diagnostic-tools/comprendre-le-mecanisme-data-safegarding-2.md)
- [Incident Classification](diagnostic-tools/classification-des-incidents.md)
- [Mandatory Information to Open a Ticket](diagnostic-tools/informations-obligatoires-pour-ouvrir-un-ticket.md)
- [Troubleshooting Data Connectivity Issues](diagnostic-tools/resolution-de-probleme-lies-a-la-connectivite-data.md)
- [SIM Status Verification](verification-du-statut-de-la-sim.md)
- [eSIM Troubleshooting](diagnostic-tools/esim-troubleshooting.md)
- [Resynchronise the services](diagnostic-tools/resynchronise-the-services.md)
- [IMS service troubleshooting](diagnostic-tools/ims-service-troubleshooting.md)
- [Roaming data troubleshooting](diagnostic-tools/roaming-data-troubleshooting.md)
- [Data session diagnostic tool](diagnostic-tools/data-session-diagnostic-tool.md)
- [Network attach diagnostic](../sim-management/network-attach-diagnostic.md)

## [[IoT] Inter-operable devices](iot-inter-operable-devices/README.md)

- [Introduction to SIM-Device testing Program](iot-inter-operable-devices/introduction-to-sim-device-testing-program.md)
- [Tested and Compatible Devices](tested-and-compatible-devices.md)
- [Compatible Modules](compatible-modules.md)

## [Device Configuration](device-configuration/README.md)

- [eSIM Troubleshooting & Best Practices](device-configuration/bonnes-pratiques-de-diagnostic-esim.md)
- [Internet & MMS access settings](device-configuration/internet-hotspot-mms-access-settings.md)
- [How to use the IMEI Lock feature](../services/iot-services/how-to-use-the-imei-lock-feature.md)
- [UK MVNO mobile internet and MMS APN settings](device-configuration/uk-mvno-mobile-internet-and-mms-apn-settings.md)
- [Configuring your device for our IoT SIM cards](device-configuration/iot-configuring-your-device-for-our-iot-sim-cards.md)

## [Service Desk Templates](service-desk-templates/README.md)

- [CDR Delivery Template](cdr-delivery-template.md)
- [Mobile Switching template](service-desk-templates/mobile-switching-template.md)
- [Roaming Template](service-desk-templates/roaming-template.md)
- [Welcome SMS / Roaming template](service-desk-templates/welcome-sms-roaming-template.md)
- [Voicemail Access template](service-desk-templates/voicemail-access-template.md)
- [Porting Issue template](service-desk-templates/porting-issue-template.md)
- [Subscriber Provisioning / Service Orders template](service-desk-templates/subscriber-provisioning-service-orders-template.md)
- [SIM Swap template](service-desk-templates/sim-swap-template.md)
- [Voice/SMS/Data template](service-desk-templates/voice-sms-data-template.md)

## On this page

# SIM Status Verification

**Is the user experiencing a connectivity or service issue with their SIM?**

Before performing any technical action, it is essential to start by verifying the **SIM status** on the Transatel platform (**Auriga**).  
A significant number of connectivity issues are caused by a SIM that is inactive, suspended, or improperly configured.

---

## Step 1 — Check SIM activation

In Auriga, confirm that:

- the SIM status is **Active** (and not *Inactive*, *Suspended*, or *Terminated*)
- no manual deactivation has been performed

👉 If the SIM is inactive, activate it and wait **2 to 5 minutes** before performing new tests.

---

## Step 2 — Check the subscription

Ensure that:

- an **active subscription** is associated with the SIM
- the subscription covers the services in use  
  (*data, SMS, MMS, voice*)
- the subscription has **not expired**

---

## Step 3 — Check usage limits

Verify that:

- the data usage threshold has not been reached
- no protection or safeguarding rule has blocked the SIM

---

## Step 4 — Check provisioned services

Confirm that the required services are enabled:

- **Mobile data**
- **Roaming** (if the user is abroad)
- **SMS / MMS** (if applicable)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
