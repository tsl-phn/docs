---
title: "About SMS Recording"
---

## **What is SMS Recording?**

SMS Recording is a feature that provides Service Providers with a **near real‑time copy** of their subscribers’ incoming and outgoing SMS messages. These copies are delivered securely via **SMPP** and allow for compliance, analysis, or integration into broader communication tools.

## **How does SMS Recording work?**

Once activated for a subscriber, Transatel receives a copy of each eligible SMS after it has been delivered by the network and forwards it to the Service Provider through a secure SMPP connection. The original SMS delivery is *not* affected.

## **Why would a Service Provider use SMS Recording?**

Common use cases include:

- **Regulatory compliance**, especially in sectors such as finance
- **Multi‑device access**, enabling SMS copies to appear on desktops or unified comms apps
- **Enhanced FMC services**, integrating SMS history into communication platforms

## **Which SMS types are included?**

The feature covers most **P2P SMS traffic**, including:

- On‑net & off‑net SMS
- Super on‑net SMS
- International SMS
- Network and premium/shortcode SMS
- A2P SMS

## **Which SMS types are *not* included?**

Some messages cannot be copied, including:

- Emergency SMS (999 / 112)
- Silent SMS (e.g., RCS activation, AML location, SPN updates)
- SMS sent using RCS instead of the traditional SMS protocol
- OTA SMS
- MMS
- OTT messages (WhatsApp, iMessage, etc.)

## **What do I need to activate SMS Recording?**

A Service Provider must have:

- A **secure SMPP 3.1/3.4/5.0 connection** with Transatel
- The feature **activated per SIM** via Auriga or the Connectivity Management API

## **Is subscriber consent required?**

Yes. The MVNO must ensure that it has the appropriate **lawful basis** (such as consent or regulatory obligation) before activating SMS Recording.

## **Will SMS Recording impact CDRs or generate extra charges?**

No changes occur to CDRs, and there is **no additional wholesale charge** for SMS copies.

## **Will I receive SMS copies in real time?**

Yes. SMS Records are delivered in **near real‑time** over the SMPP link, typically at the same moment the original SMS reaches the end user.

## **Why might I not be receiving SMS copies?**

Common causes include:

- **RCS is enabled** on the end‑user device (SMS is then sent as data rather than via the SMSC)
- The subscriber **does not have SMS Recording activated**
- The **SMPP link is unavailable**

## **Can the same SMS be copied twice?**

No. If both sender and receiver are on the same fleet, Transatel sends **only one SMS copy** to avoid duplication.

## **Can I use an API instead of SMPP?**

Not currently. SMPP is the standard supported interface, but alternative methods can be evaluated via Change Request.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
