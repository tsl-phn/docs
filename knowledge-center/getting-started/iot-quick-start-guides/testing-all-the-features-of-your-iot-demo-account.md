---
title: "Testing all the features of your IoT Demo account"
---

**Testing all the features of your IoT Demo account**

If you have received access to one of our IoT Demo accounts, this article will detail all the available features that you can test with your SIMs.  
  
After changing an option, you may need to switch the device to plane mode, or to use the “[detach](../../sim-management/network-attach-diagnostic.md)” button in the interface for the change to be implemented immediately.   
  
![image](/knowledge-center/assets/image-1.png)

****Select the radio types (2G, 3G, LTE) of your SIMs****

The new Network type control will give you the choice between 5 configurations: access all network types, or bar one type.  
  
This is a powerful tool in the following use-cases :  
–          Force a network type in locations where we offer 3G only or LTE only coverage  
–          Bar a network type where our partner operator’s bands are not compatible with your modem’s  
–          Running tests on the coverage  
–          Force a network in locations where you know it has a stronger signal (ex: 3G might be faster than a weak LTE signal)  
  
By default, the selection will be on “All services (2G/3G/4G)”, you can change then change the selection in the Service Profiles, or directly in one SIM’s settings.  
  
![image](/knowledge-center/assets/image-2.gif)

**Networks coverage selection**

Custom footpring is part of our catalogue of features.  
To enable you to test it, we have set up 3 coverage types in the demo offer :  
  
![image](/knowledge-center/assets/image-3.png)
  
Please refer to the detailed coverage shared with your commercial contact to find which carriers are included in each destination.

**SIM2SIM Communications (Hairpinning)**

Our Demo offers allows you to test remote device access using SIM2SIM (hairpinning).  
How does it work?  
Once you have selected the setting “SIM to SIM” in the “IP & routing options” drop down list, your SIM will:  
– be assigned a static private IP  
– be able to communicate with other SIMs with the same option enabled  
  
![image](/knowledge-center/assets/image-4.png)
Once the choice is applied, a new data session needs to be started for the settings to apply. You can switch the device to plane mode for a few seconds.  
  
You can then try to ping a device with the other, or send traffic.  
*Please note that consumer devices such as smartphones are often protected against pinging for safety.*   
  
You will also notice in the usage logs that the SIM is also assigned a Static IP:  
![image](/knowledge-center/assets/image-5.png)
  
Note: for demo accounts, this feature will only work for users in Europe & Africa. It can be enabled worldwide for commercial accounts.

**External routing**

To demonstrate how we can route traffic towards a specific endpoint we have enabled a simple way for you to test how we can direct data towards a specific endpoint.  
Note : this feature can only be tested on accounts in EU & Africa.  
  
How to test?  
In the “IP & routing options” drop-down list, select “External Routing”  
  
 ![image](/knowledge-center/assets/image-6.png)
Once this option is enabled, the SIM can only traffic towards a specific AWS instance created for the demo.  
Launch a new data session, and try to access “transatel.com”   
*Note: Your browser may have our corporate website in history, do not use this link, and type in manually “transatel.com”*  
  
Instead of landing on Transatel’s corporate website, you will arrive on this demo page on the AWS Server:   
![image](/knowledge-center/assets/image-7.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
