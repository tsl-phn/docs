---
title: "SMS-API and A2P SMS"
---

## **What is SMS A2P?**

In the world of IoT, it can be used for many other things, including triggering devices to upload information or to code new configurations into devices.

A2P means “Application to Person”, and this is the concept of the SMS-API. For MVNOs, it means sending messages from your MVNO to the subscriber, to inform them of all sorts of things, such as their bill payment, they have reached a spend cap or they are eligible for a new offer!

## **Can I send SMS to my subscribers?**

Yes, Transatel’s MVNOs can send SMS to their subscriber base using the SMS-API.

Documentation can be found here: <https://developers.transatel.com/docs/network-overview/#sms>

## **How do I automate selfcare?**

On some of Transatel’s offers and services, we automatically generate SMS to subscribers. For example, to tell them that they are in roaming, have used their bundle allowance or have hit their Data Safeguarding threshold.

However, MVNOs can automate SMS messages based on other events. MVNOs can subscribe to webhook events via Transatel’s API suite and use these triggers to send SMS via the API.

## **What is the sender name?**

The sender of the SMS is also called the “originator”. By default, all MVNOs have access to a few generic originators for ***onnet*** A2P SMS:

- 1250 (also used form many of Transatel’s selfcare SMS)
- 65075 (to reply to “info” switching messages)
- 75075 (to reply to “port request” switching requests)
- 85075 (to reply to “switch request” switching requests)
- WelcomeSMS (to provide roaming advice of charge)

You can contact your account manager if you want to if you’re having problems using any of these. They can also help if want to know if any other originators are available for you, or if you would like to declare a new originator.

For ***offnet*** SMS, each originator must be pre-registered (there are no default originators).

## **Can I brand the sender name?**

Indeed, you can have your MVNO name appear as the sender of the SMS sent using the SMS-API. Contact your account manager to find out how.

Please note, originator request must be validated and cannot be guaranteed.

If you request the originator to be a shortcode number, you will need to provide evidence that this shortcode belongs to you.

## **What CDRs are generated?**

You will see a new CDR type generated for SMS sent via the SMS-API. To note:

- AOSO: “A2P Originated SMS to Onnet”
- AOSD: “A2P Originated SMS Delivery Report”
- AOSxx: “A2P Originated SMS to xx” where xx represents the 2-digit ISO code for the country of the SIM that the SMS was sent to. These are for “offnet” SMS.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
