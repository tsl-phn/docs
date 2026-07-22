---
title: "New High Usage Alert Menu"
---

**New High Usage Alert Menu**

Our new High Usage menu was deployed in June  
What is changing? Compared to the current system, here are the 4 key changes:  
  
**1.       A new menu to manage all your high usage rules in the interface…and via API**  
The biggest change is that **High Usage rules will no longer be part of a Service Profile: they’ll be created & managed independently**, and be applied to populations that you’ll be able to select based on Service Profiles, Rate Plans or Options  
You’ll be able to see all the rules in one single screen, with quick access buttons to edit, clone or delete them.  
This will also be made available through API requests, so you will now be able to integrate the new methods and manage rules directly from your interface.  
This article will provide further information on [how to manage the rules in the new menu](https://docs.transatel.com/services-setup/managing-high-usage-rules/)  
  
**All the rules that currently exist in your Service Profiles will be migrated in the new menu** **on June** **2nd, and you will be able to access the new menu on June 3rd.**  
**The migrated rules will be named after the Service Profile they originated from and will be applied to the Service Profile – this means there will be no impact to your configuration.**  
  
**2.       Stackable rules**  
With rules independent from the Service Profiles, you’ll now be able to **apply multiple rules to a same SIMs**, which was not possible through the Service Profiles – for example one rule to send an email alert after 100MB consumed, and an alert to automatically suspend the SIM after 500MB consumed.  
[This article explains how to create rules in the new menu](https://docs.transatel.com/services-setup/how-to-create-manage-high-usage-alerts-in-our-sim-management-platform/)  
  
**3.       Easily track the SIMs that triggered the alert with file reports**  
In addition to emails, you’ll now get a **report generated on your SFTP account** (easily accessible through our SIM Management Platform) containing all the details on the SIM(s) that have triggered the alert. This is a first step – we’re working on a full-blown alert notification menu 😉  
[This article details the content of the alert email and of the file report.](https://docs.transatel.com/services-setup/high-usage-file-report-alert-emails/)  
  
**4.       Snooze & deactivate rules**  
Finally, one last change concerns the recurrence of the alerts: you will now have a “snooze” option, which means that if the threshold is reached, the rule will not run anymore until the end of the Billing month.  
 What does it mean? Let’s take the example of a SIM with a rule set at 100MB of data usage.  
With Snooze on you will only receive the email once when the SIM reaches 100MB – then no more  
If you reactivate a SIM that was suspended by the rule, it will not be suspended again if it reaches another 100MB of usage.  
Finally, rules can be deactivated at any time, without needing to be deleted. Just reactivate them when need them again.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
