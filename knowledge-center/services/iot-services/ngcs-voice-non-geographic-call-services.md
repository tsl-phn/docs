---
title: "NGCS Voice (Non\u2011Geographic Call Services)"
---

## Overview

NGCS Voice (Non‑Geographic Call Services) allows subscribers to access premium voice services using long, non‑geographic numbers rather than shortcodes. In the UK, these services typically use number ranges such as 084, 087, 09, and 118, as defined in Ofcom’s National Numbering Plan.

NGCS Voice calls are routed to merchant‑operated platforms such as call centres, IVRs, or information services and are billed at premium rates.

This article explains what NGCS Voice is, how it works, and how charges are triggered at call level. It does not describe monthly spend caps, transaction limits, warnings, blocking rules, or reset logic. All spend limits, thresholds, notifications, and blocking behaviour are documented exclusively in the Payment Safeguarding article.

## How NGCS Voice Works

An NGCS Voice interaction consists of a voice call initiated by the subscriber to a non‑geographic number:

1. MO Voice Call (Mobile Originated)

The subscriber dials a non‑geographic premium number (for example, starting with 084, 087, 09, or 118).

- A voice access charge may be applied when the call is connected.
- A voice service charge may be applied either:
  - per call setup, and/or
  - per minute for the duration of the call.

Charges are typically billed per started minute, with no pro‑rata.

All charges are applied in real time while the call is in progress.

## Typical Use Cases

- Customer support and help lines
- Professional or technical advice services
- Directory enquiries (118 services)
- Information lines (travel, transport, or schedules)
- Entertainment or content services

## Key Characteristics

- Uses long non‑geographic numbers as defined by Ofcom
- Charges may include both access and service components
- Charging may be per call, per minute, or a combination of both
- Charges are initiated by the merchant’s service, not by the network
- Detailed voice call records are generated for billing and support

## Consumer Protection & Disputes

NGCS Voice services are regulated under UK Premium Rate Services rules and the Ofcom National Numbering Plan.

Merchants are responsible for presenting clear pricing information, managing call flows, and complying with Ofcom and PSA consumer‑protection requirements.

In the event of a dispute, the subscriber must first attempt to resolve the issue directly with the merchant operating the NGCS Voice service. If the dispute cannot be resolved with the merchant, the subscriber may escalate the complaint through Ofcom’s Premium Rate Services complaints process.

Independently of merchant processes, the MVNO must be able to bar NGCS premium voice services at network level upon subscriber request. When NGCS Voice is barred, no further NGCS calls can be made by that subscriber.

## Finding Retail Charges (NRT CDRs)

Retail charges for NGCS Voice calls are exposed in Near Real‑Time (NRT) Call Detail Records (CDRs). These records are the authoritative source for the retail price charged to the subscriber, including any applicable VAT.

For NGCS Voice, the NRT CDRs contain:

- A record for the voice access charge, if applicable
- One or more records representing the service charge, either per call or per minute

NRT CDRs are delivered to dedicated sFTP directories and can be used by the MVNO to generate subscriber billing, validate charges, and handle customer queries.

Wholesale CDRs should not be used to determine retail charges, as they are intended for wholesale reconciliation and exclude VAT.

## Refunds

Refunds for NGCS Voice services are uncommon. Where refunds do occur, they are typically initiated by the merchant and appear as negative charge entries in billing records.

Refunds do not re‑credit any monthly spend limits or cumulative usage controls.

## Availability & Limitations

- UK domestic usage only (not supported in roaming)
- Not compatible with Voice Convergence unless the MVNO provides its own termination and billing logic
- Compatible with prepaid services
- Call forwarding to NGCS premium numbers is not supported

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
