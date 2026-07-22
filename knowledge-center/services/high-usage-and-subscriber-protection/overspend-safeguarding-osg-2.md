---
title: "Overspend Safeguarding (OSG)"
---

****What is Overspend Safeguarding (OSG)?****

OSG is a real-time spend-control feature designed for Pay Monthly mobile subscriptions. It allows Service Providers to set a maximum out-of-bundle (OOB) spend limit for each subscriber. Once this limit (called the OSG Cutoff) is reached, any additional OOB usage is automatically blocked. This helps prevent unexpected charges and ensures compliance with Ofcom’s bill-shock regulations.

****How does OSG work in practice?****

OSG operates through Transatel’s Online Charging System (OCS), which monitors subscriber usage in real time. When a subscriber uses services outside their bundle (e.g., extra data or roaming), these charges accumulate in the OSG “Charged” balance. If the Charged balance reaches the predefined Cutoff, OSG instantly blocks further OOB usage. This mechanism applies across national and roaming data, international calls, and SMS.

****Can subscribers still buy add-ons or roaming bundles when OSG is active?****

Yes. If an add-on or roaming bundle is purchased, usage will first deduct from that bundle before impacting the OSG Charged balance. This means subscribers can continue to manage their usage without disabling OSG.

****How can Service Providers manage OSG?****

OSG can be managed via:

- **Auriga Web Interface:** Activate/deactivate OSG, set Cutoff values, view Charged balance, and adjust renewal dates.
- **OCS-API & Webhooks:** Automate OSG management and receive real-time notifications for events like activation, renewal, or reaching 80%/100% of the Cutoff.

**What happens when the OSG Cutoff is reached?**

Once the Cutoff is reached:

- All OOB usage (data, roaming, international calls/SMS) is blocked.
- Premium services in the UK remain available and unlimited.
- Roaming premium services are blocked.
- Subscribers receive an SMS notification informing them that their spend cap has been reached.

**Are subscribers notified about their OSG status?**

Yes. Transatel sends SMS alerts at key thresholds:

- **80% of Cutoff:** “You have used 80% of your mobile bill limit.”
- **100% of Cutoff:** “Your mobile bill limit has been reached and services with additional charges are no longer available.”  
  MVNOs can also create custom notifications using webhook events.

**Is OSG compatible with other options like Data Safeguarding (DSG)?**

Yes. OSG and DSG can run together.

**What happens if OSG is disabled?**

Disabling OSG removes all spend protection. All OOB usage becomes unrestricted (“open bar”), which can lead to high bills if not monitored.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
