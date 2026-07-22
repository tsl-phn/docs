---
title: "What is a deviation from a Service Profile"
---

**What is a deviation from a Service Profile?**

You may see in the interface the message that a SIM has been deviated from its [Service Profile](https://docs.transatel.com/services-setup/what-is-a-service-profile/).  
It means that the settings of the SIM have been modified at SIM level, and that the values are not different from the Service Profile that was applied to it.  
  
This happens when a user has made changes to the services in the SIM’s detailed page – in the Configured Services tab – instead of changing the Service Profile.  
It can also happen if a change was made through API calls – API changes do not take into account Service Profile, and can therefore deviate SIMs.

**How do you know if a SIM has been deviated?**

It will be displayes in the following menus:s  
– The interface will show this “wave” icon next to the Service Profile’s name in the lists of SIMs:  
  
![image](/knowledge-center/assets/image-1.png)
  
– In the SIM’s detailed view, the following message will appear in the “configured services” tab :  
  
![image](/knowledge-center/assets/image-2.png)
  
In this screen, click on “See Profile” and you’ll be able to see side by side the SIM’s settings, and the Profile’s settings – and therefore see what change was made (if the change has not been reverted to the original value)  
![image](/knowledge-center/assets/image-3.gif)

**How to remove the deviation?**

If you do not want the SIM to stay deviated, you must:  
– migrate it to a different Service Profile  
– then migrate it back to the original Service Profile  
  
**Just reverting the setting that was changed is not enough to get the SIM back into the Service Profile’s configuration**

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
