---
title: "The Test Mode"
---

**The Test Mode for IoT SIMs**

The Test mode is an optional mode that can be enabled for your account.  
  
The test mode is a temporary status meant to be used for tests before the device is deployed.  
It delays the SIM’s activation – and therefore monthly fees, while allowing a quota of data and SMS for internal tests.  
While in Test Mode, monthly SIM fees or minimum revenue per SIM are not applied.  
  
The test mode’s configuration is based on:  
– a **quota of data and SMS** allowed  
– a **maximum number of days** in the status  
– the **status** the SIM should switch to when exiting test mode  
  
The default configuration is that the SIM should switch to Active status after exiting Test Mode, but it is also possible to transition into Sleep Mode to further delay the activation and the start of the billing.   
  
For example if you have a test mode enabled with the following configuration  
– 1MB   
– 30 days   
– Switch to Active status when exiting Test Mode  
  
When you activate the SIM (via API or our interface), it will go into Test Mode.  
Then, when the 1MB is used, or 30 days have passed, the SIM will automatically switch to Active.  
  
![image](/knowledge-center/assets/image-1.png)

**Managing SIMs in Test Mode**

In the interface, the test mode is clearly displayed.  
  
![image](/knowledge-center/assets/image-2.png)
  
A SIM car in Test mode can be switched to the following statuses:  
– Activated – forcing the activation is possible at any time  
– Suspended – the SIM will exit test mode definitely, will become chargeable, but will not be able to make any traffic  
– Terminated – the final and irreversible status  
  
Please note that exiting Test Mode is a final action, the SIM cannot go back to Test Mode.  
  
![image](/knowledge-center/assets/image-3.png)

**How to track usage and remaining days of the SIMs in Test Mode?**

When test mode is enabled for your account, a new type of report file will be generated daily to track the SIMs in test mode.  
The Test Mode reports can be accessed:  
– in the interface, in Tracking & Reports > File Reports > Test mode reports  
– on your Transatel SFTP account  
  
The daily report lists for each SIM in test mode:  
– the SIM details  
– inital and remaning data, SMS and voice allowances  
– initial and remaning days in test mode  
  
Here is an example for 2 SIMs :   
![image](/knowledge-center/assets/image-4.png)
  
Below is the list of fields of the report:  
ICCID  
Msisdn  
Tariff  
Activation\_Date  
Initial\_Period  
Remaining\_Period  
Initial\_PSD\_Allowance  
Remaining\_PSD\_Allowance  
Initial\_SMS\_Allowance  
Remaining\_SMS\_Allowance  
Initial\_Voice\_CSD\_Allowance  
Remaining\_Voice\_CSD\_Allowance

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
