---
title: "Payment Safeguarding (PSG)"
---

## Overview

Payment Safeguarding (PSG) is a network‑level spend‑control mechanism that protects subscribers from excessive charges on Premium Services, including Premium SMS, Shortcode Voice, and NGCS Voice.

PSG enforces regulatory spend limits in real time. It operates independently of service barrings and merchant controls.

This article explains what PSG is, how it works, what limits apply, and how blocking and notifications behave.

## What PSG Applies To

PSG applies cumulatively across all Premium Services:

- Premium SMS
- Shortcode Voice
- NGCS Voice

All qualifying charges (service & access charges) count toward the same monthly PSG balance.

## How PSG Works

Each time a subscriber attempts to use a Premium Service, a real‑time authorisation check is performed against the subscriber’s PSG balance.

- If sufficient PSG balance is available, the service is allowed and the charge is deducted in real time.
- If the PSG balance is exhausted, the service attempt is rejected and no charge is applied.

For voice calls, PSG is enforced while the call is in progress. Calls are automatically terminated when a transaction limit is reached.

## Spend Limits

### Monthly Spend Cap

- £240 per month across all Premium Services
- The cap is fixed and not customisable
- Once reached, all Premium Services are blocked until the next reset

### Warning Threshold

- 80% of the monthly cap (£192)
- When crossed, the subscriber is notified automatically

### Per‑Transaction Limit

- £40 maximum per transaction
- Applies to both Premium SMS and Premium Voice
- Voice calls are disconnected automatically upon reaching this limit

## Reset & Renewal

The PSG balance resets automatically based on the subscriber’s configured renewal date:

- Default renewal date: 1st of each month (but can be modified)
- The balance resets to £0 charged at renewal

If the renewal date falls between the 29th and 31st, the next reset occurs on the 1st of the following applicable month.

## Blocking Behaviour

When the monthly PSG cap is reached:

- All Premium SMS (MO and MT) are blocked
- All Shortcode Voice calls are blocked
- All NGCS Voice calls are blocked

Blocking remains in place until the next PSG reset, unless the option is manually modified.

## Notifications & Events

Subscribers receive automatic SMS notifications for the following events:

- PSG activated or deactivated
- Warning threshold reached
- Monthly spend cap reached

Each event also generates a webhook that the MVNO may consume for customer care or monitoring purposes.

## Relationship with Barrings

Network barrings take precedence over PSG:

- If Premium Services are barred, no traffic is generated and PSG is not incremented
- PSG does not override barrings

Barrings and PSG may be used together as complementary controls.

## Refunds & PSG Balance

Refunds do not restore PSG balance.

If a refund is applied:

- The charge appears as a negative value in billing records
- The refunded amount is not deducted from the PSG balance if refund falls outside of the current period.

This prevents subscribers from exceeding the monthly cap through refunds posted in later periods.

## Scope Limitations

- PSG applies only to Premium Services
- PSG does not apply to standard voice, SMS, or data usage
- PSG is separate from prepaid credit controls

## Summary

Payment Safeguarding (PSG) provides mandatory, real‑time spend protection across all Premium Services. It ensures regulatory compliance, protects subscribers, and gives MVNOs a consistent control framework that operates independently of merchant behaviour.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
