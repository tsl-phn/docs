---
title: "Creating High Usage Alerts"
---

****Creating High Usage Alerts****

You can create rules to monitor your fleet’s usage in our interface.  
  
**Key details of the rules system:**  
–          Our system runs the rules **every hour**, and the counters are reset each beginning of each calendar month.  
–          Rules are usage based: data volume, SMS sent, voice minutes or amount charged…  
–          If a rule is triggered, the system can send alert emails, generate a file report and/or suspend the SIM.  
–          You can filter which SIMs the rules will be applied to according to [Service Profiles](https://docs.transatel.com/services-setup/what-is-a-service-profile/), Rate Plans or Billing Options  
–          Rules can be configured through API requests  
  
![image](/knowledge-center/assets/image-1.png)
  
The High Usage menu is accessible in **Tracking & reports** > **Set Automation rules**  
  
![image](/knowledge-center/assets/image-2.png)
  
To create a new rule, click on “add a rule” at the top right  
  
![image](/knowledge-center/assets/image-3.png)
  
You can now configure the following in the new window.  
  
Here is an overview of each section of the window:  
  
**Rule**  
•       Rule name: it must be unique to your account  
•       Activate rule: activate or deactivate the rule if you do not want it implemented now  
![image](/knowledge-center/assets/image-4.png)
**Please make sure that you activate the rule upon creating it, otherwise it will not be implemented**  
**Usage limit:**  
•       Type of usage: depends on the Rate Plans available on your account – data, SMS, voice, amount charged…  
•       Volume: defines the threshold  
  
![image](/knowledge-center/assets/image-5.png)
Below are a few examples and explanations for the “type of limit” criteria:  
*All airtime*: all voice, SMS, data, MMS usage which may be national, international or roaming  
*All national data*: all data used in the home country of the SIM  
*All data usage:* all data used, regardless of the originating country  
  
**Actions**  
You can select “Line suspension” for the automated suspension of the line when the volume is reached.  
  
**Alerts**  
•       *SFTP file notification*: files are deposited on your SFPT every hour – and can be accessed easily from the SIM Management Platform (in Tracking & Reports >Report Files)  
•       *Email notification*: an email notification is sent when trigger is reached. A file is attached to the Email (the same as deposited on the SFTP)  
•       *Repeat alerts*: if this option is selected, you will receive the notification for each affected line every time the rule runs. If it is deactivated, the HU Rule runs for a line until the threshold is reached. Then the Rule will not run again for this line until the end of the month. This parameter is mandatory with “Line suspension” and is automatically activated when “Line suspension” is “Active”.  
  
![image](/knowledge-center/assets/image-6.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
