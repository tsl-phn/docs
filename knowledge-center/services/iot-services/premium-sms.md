---
title: "Premium SMS"
---

## Overview

Premium SMS allows subscribers to interact with services provided by third‑party merchants using short numerical shortcodes (typically 3–6 digits). These interactions are commonly used for voting, charity donations, subscriptions, alerts, and other value‑added services.

This article explains what Premium SMS is, how it works, and how charges are triggered at message level. It does not describe monthly spend caps, transaction limits, warnings, blocking rules, or reset logic. All spend limits, thresholds, notifications, and blocking behaviour are documented exclusively in the Payment Safeguarding article.

## How Premium SMS Works

A Premium SMS interaction usually consists of two distinct steps:

### MO SMS (Mobile Originated)

The subscriber sends an SMS to a shortcode.

- The SMS may be free, or
- Charged at the standard network SMS rate (not usually included in bundles)

### MT SMS (Mobile Terminated)

The merchant sends one or more reply messages containing the paid service.

- Each MT SMS may carry a service charge set by the merchant
- Multiple MT messages may generate multiple charges

Charges are applied in real time as the messages are sent or received.

## Typical Use Cases

- TV and media voting
- Charity donations
- One‑off purchases
- Subscriptions and recurring services
- Alerts and informational content
- Marketing campaigns
- Authentication (OTP / MFA)

## Key Characteristics

- Uses short numerical codes (typically 3–6 digits)
- Supports one‑off and recurring charging models
- Charges are initiated by the merchant, not the network
- Detailed Premium SMS records are generated for billing and support

## Opt‑In, Opt‑Out & Consumer Protection

Premium SMS services are regulated under UK Premium Rate Services rules and must provide clear mechanisms for consent, stopping services, dispute resolution, and escalation.

A subscriber can stop an individual Premium SMS service at any time by sending STOP to the shortcode that is charging them. Where supported by the merchant and aggregator, a subscriber may also be able to send STOP ALL to the provider’s dedicated opt‑out shortcode, which is separate from the charging shortcode, to stop all Premium SMS services associated with that provider.

Merchants are fully responsible for managing opt‑in flows, subscription life‑cycles, pricing transparency, and compliance with Ofcom and PSA consumer‑protection requirements. This includes ensuring that subscribers are clearly informed of charges, whether services are recurring, and how to stop them.

In the event of a dispute, the subscriber must first attempt to resolve the issue directly with the merchant providing the Premium SMS service. If the subscriber is unable to resolve the dispute with the merchant, they may escalate the complaint through Ofcom’s Premium Rate Services complaints process.

Independently of merchant controls and dispute processes, the MVNO must be able to bar Premium SMS services at network level upon subscriber request. When Premium SMS is barred by the MVNO, no further Premium SMS charges can be generated for that subscriber, regardless of merchant behaviour.

## Finding Retail Charges (NRT CDRs)

Retail charges for Premium SMS are exposed in Near Real‑Time (NRT) Call Detail Records (CDRs). These records are the authoritative source for the retail price charged to the subscriber, including any applicable VAT.

For Premium SMS, the NRT CDRs contain:

- A record for the MO SMS, showing whether the outbound message was free or charged at the standard network SMS rate.
- One or more records for the MT Premium SMS, each containing the service charge applied by the merchant.

NRT CDRs are delivered to dedicated sFTP directories and can be used directly by the MVNO to generate subscriber billing, perform charge validation, and handle customer queries.

Wholesale CDRs should not be used to determine retail charges, as they are designed for wholesale reconciliation and exclude VAT.

## Refunds

Refunds are rare but can occur in limited circumstances, for example:

- The subscriber is unreachable and the charged MT SMS cannot be delivered
- A merchant explicitly issues a refund

Refunds appear as negative charges in billing records. Refunds do not re‑credit any monthly spend limits.

## Availability & Limitations

- UK domestic usage only (not supported in roaming)
- Compatible with prepaid services, Voice Convergence & SMS recording

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
