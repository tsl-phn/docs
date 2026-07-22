---
title: "Data Safeguarding"
---

**Data Safeguarding** 

![image](/knowledge-center/assets/image-1.png)

**What is Data Safeguarding?**

Data Safeguarding is a real-time service designed to protect consumers from bill shock whilst roaming.  
In the UK since 2022, the Ofcom regulation recommends MNOs and MVNOs to set consumers’ price caps on data roaming use. The consumers must consent via SMS to exceed the threshold limit.  
At Transatel, we have implemented a default threshold of £45 per monthly period.  
See more information from Ofcom [here](https://www.ofcom.org.uk/news-centre/2021/travelling-abroad-check-for-roaming-charges).

**How does it work?**

The Data Safeguarding service functions as follows:  
·       **Warning:** Transatel notifies the subscriber by SMS when they have used 80% of the limit  
·       **Cutoff:** Transatel notifies the subscriber by SMS when they have used 100% of the limit and bar all roaming data in the zones covered by the Data Safeguarding Solution  
·       **Resume:** The Subscriber must reply “OK DATA” in order to remove data barring and accept further roaming costs.

**How can the MVNO manage Data Safeguarding?**

Transatel allows the MVNO to manage the Data Safeguarding service via the web portal or OCS-API. These interfaces enable the Service Provider to verify the status of the service and if the limit has been reached, as well as opt-out on behalf of the subscriber temporarily or permanently.

**What are the different actions on Data Safeguarding?** 

Depending on the configuration set by the MVNO on the subscriber’s line, the following settings are available:   
  
·       **Suspend Temporarily**: when the subscribers consume £45 of data whilst roaming, they will be suspended temporarily until the next calendar month.  
![image](/knowledge-center/assets/image-2.png)
·       **Cancel Permanently**: the Data Safeguarding service will not apply to this line forever. i.e. they will never be notified or blocked by the service, nor need to reply “OK data”.  
![image](/knowledge-center/assets/image-3.png)
·       **Subscribe to the option**: when a subscriber is cancelled permanently, they can request to reactivate Data Safeguarding.  
![image](/knowledge-center/assets/image-4.png)
·       **Modify the renewal date**: MVNOs can change the date in which the counter is reset. I.e. if your billing cycle is from the 15th of the month, you can align the Data Safeguarding to reset on this date.  
![image](/knowledge-center/assets/image-5.png)

**How does data safeguarding combine with RTCP and capped daily roaming passes?**

On RTCP, a subscriber needs to purchase a daily roaming pass in order to use data outside of Zone 1. The data safeguarding wallet is never impacted.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
