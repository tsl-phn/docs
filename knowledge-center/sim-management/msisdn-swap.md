---
title: "MSISDN Swap"
---

****MSISDN Swap****

****What is MSISDN Swap ?****

MSISDN Swap is a feature that allows the MVNO to change the current MSISDN for a given subscriber without needing to replace the their SIM card. The subscribers’ bundles and services remain unchanged. It can be performed exclusively on Active SIMs.  
This feature is available through Auriga and via API. When using the connectivity management API, a Webhook event will be received.

**/!\ Important Notes /!\**

- The MSISDN Swap is irreversible, once done the old MSISDN cannot be retrieved.
- The MSISDN Swap can be done only on an active SIM.

****When is the MSISDN Swap used for?****

The MSISDN Swap can be used in various scenarios, typically upon the request of the subscriber. Some common use-cases include:  
**Spam Calls/SMSs:** If a subscriber frequently receives spam calls and messages, an MSISDN swap can help mitigate this issue by providing a new number.  
**Harassment Calls/SMSs:** In cases where a subscriber receives threats or harassment via calls and messages to their mobile phone, an MSISDN swap can provide immediate relief by changing their number.

By offering this service, MVNOs can enhance customer satisfaction and provide a safer communication environment for their subscribers.

****How can I use the MSISDN feature?****

The following video shows how to perform an MSISDN swap via Auriga:

![image](/knowledge-center/assets/image-1.gif)

**What’s next?**

After the MSISDN replacement, the end-user receives an SMS requesting them to restart their device. As in the screen capture below :

![image](/knowledge-center/assets/image-2.jpg)

Once the operation has completed, the new MSISDN can be retrieved via Auriga, also can be retrieved from the Webhook event sent to the MVNO.

/!\ MVNOs are strongly advised to note the SIM ICCID (serial number) before performing the SIM swap in order to search for the subscriber on Auriga

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
