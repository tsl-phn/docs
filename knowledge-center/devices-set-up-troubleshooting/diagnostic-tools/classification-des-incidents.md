---
title: "Incident Classification"
---

To ensure appropriate and prioritized incident handling, Transatel classifies incidents based on two criteria: **severity** and **impact**.  
This classification determines the level of urgency and the resources required for resolution.

### Severity

Severity defines the priority level for incident handling.

- **Blocking**: completely prevents service usage
- **Major**: significantly impacts the service without fully blocking it
- **Minor**: limited impact with minimal consequences on usage

### Impact

Impact refers to the number of users affected by the incident.

- **Single-user**: the incident affects one user only
- **Global**: the incident affects multiple users simultaneously

An incident is considered **global** when at least **5 distinct users** are impacted within a **one-hour period**.

### Conditions to qualify an incident as global

For an incident to be treated as global, the following information must be provided:

- **5 different impacted MSISDNs**
- **5 corresponding timestamps** (one per user)

If this information is not provided, the incident may be reclassified as a **single-user incident**.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
