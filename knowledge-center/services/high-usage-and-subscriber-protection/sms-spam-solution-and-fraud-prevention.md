---
title: "SMS Spam Solution and Fraud Prevention"
---

**What is SMS spam, and why is it a concern?**

SMS spam includes unwanted text messages, often sent to promote products, services, or to deceive recipients into disclosing personal information for fraudulent purposes. Some messages mimic legitimate businesses, banks, or even government agencies. These messages can lead to financial loss and are increasingly common, with spam representing around 10% of SMS traffic in certain regions.  
  
As a reminder, to protect the network, subscribers and conforming to regulation, the use of SIMs in unauthorised equipment (such as SIM boxes) is prohibited.

**How can SMS spam be reported?**

Subscribers can report spam or fraudulent SMS messages by forwarding them to the short code **7726** (which spells “SPAM” on a mobile keypad). This service is available within the UK and while roaming abroad. Messages sent to 7726 are free for end users, and reported numbers are investigated by Ofcom.

**Are there any requirements for prepaid and postpaid MVNOs regarding the 7726 service?**

– **Prepaid MVNOs:** No specific action is needed, as the 7726 service is already activated and zero-rated.  
– **Postpaid MVNOs:** You should confirm with your billing supplier that they are set up to handle SMS to MOSNS (Mobile Originating SMS to National Special number) and ensure these messages aren’t correctly rated.

**How does the automated SMS barring system work to prevent spam?**

BT automatically bars outgoing SMS from any number that sends SMS messages to more than 300 unique recipients within a 24-hour period. This threshold is based on the number of recipients, not the total SMS sent. SMS barring remains in place until removed via a Service Desk request. Customers with legitimate needs to exceed this limit can be exempted by contacting Service Desk.

**What should MVNOs do to support this barring service?**

No specific action is required from MVNOs, although updating terms & conditions to inform customers of this barring policy may be advisable.

**What is the High Usage Alert (HUA) enhancement, and how can it help?**

To help MVNOs tackle fraud, they can set a special rule on Transatel’s systems to recieve a High Usage Alert when an MSISDN sends SMS to a threshold of unique recipients.  
  
– The High Usage Alert service by Transatel now includes thresholds based on:  
 – Total charges (monetary limits)  
 – Usage volume (e.g., SMS, data, minutes)  
 – Number of recipients (per month)  
  
To enable the threshold per number of unique recipients, please contact your Account Manager.  
  
Actions triggered by these thresholds include sending alerts to a designated email or FTP server, or automatically suspending a SIM card.

**How can an MVNO adjust the thresholds for High Usage Alerts?**

To configure new High Usage Alerts, MVNOs are autonomous using the Auriga interface. Click [here](https://docs.transatel.com/services-setup/high-usage-alerts/iot-new-high-usage-alert-menu/) to find out how.  
  
For the special threshold of unique recipients, please contact your Account Manager to implement this rule.

**Will customers still receive SMS when their outgoing SMS service is barred?**

Yes, even when outgoing SMS is barred, customers will continue to receive SMS messages.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
