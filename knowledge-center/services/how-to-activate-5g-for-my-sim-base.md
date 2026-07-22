---
title: "How to activate 5G for my SIM base?"
---

**How to activate 5G for my SIM base?**

5G is available for all French MVNOs on our Full architecture. You can activate the 5G option directly from our SIM provisioning platform, or by integrating our REST APIs.

**How does it work?**

By default, your SIMs will be connected to the 4G or 3G network, depending on the location of the handset and the provisioning of the SIM card.   
  
The 5G option will be available as an option to activate, on a SIM per SIM basis. This will therefore give you the freedom to define your own 5G offers for your client base. Make sure that your end-users are using a 5G compatible terminal.   
  
Don’t hesitate to get in touch with your Account Manager for any help regarding the commercialisation of this option.

**How do I activate the option via the SIM provisioning platform?**

In order to activate the option from our SIM provisioning platform, you can go to the Configured Services tab, once you’ve chosen a SIM.  
The option is available from the drop down list, under Network Type Selection:

![image](/knowledge-center/assets/image-1.png)
![image](/knowledge-center/assets/image-2.png)

**How do I activate the option via API?**

The action is also available to access via our REST APIs. The values you must imput in order to have access to our 5G offer are in the table below.  
  
You can contact your Account Manager for more information regarding this integration.

|  |  |
| --- | --- |
| **Technical Package Name** | **Exclusion Group** |
| DATA\_BEARER\_208\_NO2GNO3G​ | <Offer\_Name>\_FORFAIT\_DATA\_BEARER​ |
| DATA\_BEARER\_208\_NO4G​ | <Offer\_Name>\_FORFAIT\_DATA\_BEARER​ |
| DATA\_BEARER\_208\_ALL​ | <Offer\_Name>\_FORFAIT\_DATA\_BEARER​ |
| DATA\_BEARER\_208\_5G | <Offer\_Name>\_FORFAIT\_DATA\_BEARER​ |

In order to find the correct value for the 5G options, you can go to the Catalogue > Options menu of the SIM management platform.

![image](/knowledge-center/assets/image-3.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
