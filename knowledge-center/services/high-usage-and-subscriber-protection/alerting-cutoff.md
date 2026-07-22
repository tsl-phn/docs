---
title: "Alerting Cutoff"
---

## What is Alerting Cutoff?

Alerting Cutoff is Orange’s roaming data protection mechanism designed to prevent excessive out-of-bundle charges when subscribers use mobile data abroad. It applies to all MVNO subscriber lines hosted on the Orange network.

The mechanism monitors roaming data consumption and automatically:

- Warns subscribers when they are approaching a predefined threshold.
- Suspends mobile data usage once the maximum threshold is reached.
- Requires explicit consent before data roaming can continue.

## Why does Alerting Cutoff exist?

European regulations require operators to protect subscribers from excessive roaming charges outside regulated European roaming zones.

The regulatory spending limit is set at **€50 excluding VAT**. Once the corresponding threshold is reached, the subscriber must explicitly consent before continuing to use mobile data while roaming.

## How does Alerting Cutoff work?

The Alerting Cutoff mechanism operates in two stages:

### Step 1 – Alert at 80%

When a subscriber reaches **80% of the applicable roaming threshold**, an SMS notification is sent.

**SMS message**

> > ```
> > Vos consommations Data à l'étranger sont facturées hors forfait. Par mesure de prévention, votre session pourra être interrompue.
> > ```

### Step 2 – Cutoff at 100%

When a subscriber reaches **100% of the threshold**, Orange:

- Sends a second SMS notification.
- Suspends data roaming services.

**SMS message**

> > ```
> > Vous avez été déconnecté afin de prévenir tout risque de facturation excessive. Vous pouvez vous reconnecter en débloquant votre ligne sur la page de redirection à partir de votre navigateur.
> > ```

## What are the roaming data thresholds?

The thresholds vary depending on the roaming zone. They are configured to correspond to the regulatory spending limit while taking into account the cost of data in each destination.

| Roaming Zone | 80% Alert | 100% Cutoff |
| --- | --- | --- |
| Europe (Zone 1) | 8,000 MB | 10,000 MB |
| Switzerland & Andorra (Zone 2) | 3,600 MB | 4,500 MB |
| Maghreb & Turkey (Zone 3) | 266 MB | 333 MB |
| USA & Canada (Zone 4) | 800 MB | 1,000 MB |
| Rest of World (including French Polynesia, Wallis & Futuna and New Caledonia) (Zone 5) | 40 MB | 50 MB |
| Satellite & Maritime Networks (Zone 6) | 1.6 MB | 2 MB |

## Why are thresholds different for each zone?

Data roaming costs vary significantly depending on the destination and network type.

For example:

- European roaming destinations allow much larger volumes of usage before reaching the regulatory limit.
- Satellite and maritime networks are significantly more expensive, resulting in much lower thresholds.
- The thresholds are designed to ensure compliance with the €50 regulatory cap.

## What happens when a subscriber reaches 100% of the threshold?

Once the 100% threshold is reached:

- The subscriber receives a cutoff SMS.
- Mobile data roaming is suspended.
- The subscriber can no longer use data services while roaming until the restriction is removed.

Voice and SMS services are not impacted by the Alerting Cutoff mechanism (subject to standard roaming service availability).

## How was Alerting Cutoff managed previously?

Historically, subscribers who reached the cutoff threshold could restore data services themselves through an Orange-hosted web portal.

However, following changes to Orange’s platform, this self-service web page is no longer available. Subscribers can therefore no longer remove the restriction autonomously.

## How can a blocked subscriber be unblocked?

MVNOs can now unblock subscribers directly from Auriga thanks to the integration of Orange’s Alerting Cutoff API.

This allows authorized users to remove the restriction on behalf of the subscriber without requiring access to the historical Orange self-service portal.

## How do I perform a roaming data unblock in Auriga?

1. Open the subscriber record in Auriga.
2. Click **Other Actions**.
3. Select **Unblock roaming data usage**.
4. Confirm the action.

![image](/knowledge-center/assets/image-1.png)

The request is sent to Orange and the roaming data restriction is removed.

## Who can perform the unblock action?

Only users with the **Fleet Manager** role can perform the **Unblock roaming data usage** action in Auriga.

If the option is not visible, please verify your permissions or contact your administrator.

## When should a subscriber be unblocked?

A subscriber should only be unblocked when:

- The Alerting Cutoff threshold has been reached.
- The subscriber wishes to continue using mobile data while roaming.
- The subscriber understands that additional roaming charges may apply.

## Does the unblock action reset usage counters?

No.

The unblock action only lifts the roaming data restriction. It does not reset the subscriber’s roaming consumption counter.

Once the unblock has been performed, the Alerting Cutoff mechanism will not trigger again during the current calendar month, regardless of additional roaming data consumption.

The roaming usage counter is automatically reset at the beginning of the next calendar month, at which point the Alerting Cutoff protection becomes active again.

## Does Alerting Cutoff apply to all subscribers?

Yes.

Alerting Cutoff is operated by Orange on all MVNO subscriber lines and applies whenever roaming data usage is subject to the roaming protection mechanism.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
