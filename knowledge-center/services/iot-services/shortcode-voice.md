---
title: "Shortcode Voice"
---

## Overview

Shortcode Voice allows subscribers to access premium voice services by calling short numerical numbers (typically 3–6 digits). These calls are routed to merchant‑operated platforms such as IVRs or call centres and are billed at premium rates.

This article explains what Shortcode Voice is, how it works, and how charges are triggered at call level. It does not describe monthly spend caps, transaction limits, warnings, blocking rules, or reset logic. All spend limits, thresholds, notifications, and blocking behaviour are documented exclusively in the Payment Safeguarding article.

## How Shortcode Voice Works

A Shortcode Voice interaction consists of a voice call initiated by the subscriber:

### MO Voice Call (Mobile Originated)

The subscriber dials a premium shortcode.

- A voice access charge may be applied when the call is connected.
- A voice service charge may be applied for each minute of the call. Charges are typically billed per started minute, with no pro‑rata.

### Follow‑up Communication

In rare cases, a voice service may also trigger a follow‑up SMS from the merchant. If such an SMS carries a charge, it is billed separately as part of the service.

All charges are applied in real time while the call is in progress.

## Typical Use Cases

- Customer support and advice lines
- Interactive voice campaigns
- Voice‑based voting or surveys
- Premium information or content services

## Key Characteristics

- Uses short numerical voice numbers (typically 3–6 digits)
- Charges are applied per call and/or per minute
- Charges are initiated by the merchant’s service, not by the network
- Detailed voice call records are generated for billing and support

## Consumer Protection & Disputes

Shortcode Voice services are regulated under UK Premium Rate Services rules.

Merchants are responsible for presenting pricing information, managing call flows, and complying with Ofcom and PSA consumer‑protection requirements.

In the event of a dispute, the subscriber must first attempt to resolve the issue directly with the merchant operating the Shortcode Voice service. If the dispute cannot be resolved with the merchant, the subscriber may escalate the complaint through Ofcom’s Premium Rate Services complaints process.

Independently of merchant processes, the MVNO must be able to bar premium voice services at network level upon subscriber request. When Shortcode Voice is barred, no further premium voice calls can be made by that subscriber.

## Finding Retail Charges (NRT CDRs)

Retail charges for Shortcode Voice calls are exposed in Near Real‑Time (NRT) Call Detail Records (CDRs). These records are the authoritative source for the retail price charged to the subscriber, including any applicable VAT.

For Shortcode Voice, the NRT CDRs contain:

- A record for the voice access charge, if applicable
- One or more records representing the per‑minute service charge for the duration of the call

NRT CDRs are delivered to dedicated sFTP directories and can be used by the MVNO to generate subscriber billing, validate charges, and answer customer queries.

Wholesale CDRs should not be used to determine retail charges, as they are intended for wholesale reconciliation and exclude VAT.

## Refunds

Refunds for Shortcode Voice services are uncommon. Where refunds do occur, they are typically initiated by the merchant and appear as negative charge entries in billing records.

Refunds do not re‑credit any monthly spend limits or cumulative usage controls.

## Availability & Limitations

- UK domestic usage only (not supported in roaming)
- MVNOs using Voice Convergence must provide the service themselves: Transatel will forward the call to the MVNO for billing and termination logic
- Compatible with prepaid services
- Call forwarding to Shortcode Voice numbers is not supported

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
