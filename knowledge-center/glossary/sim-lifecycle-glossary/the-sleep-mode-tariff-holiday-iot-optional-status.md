---
title: "The Sleep Mode (Tariff Holiday) \u2013 IoT optional status"
---

# The Sleep Mode (Tariff Holiday) – IoT optional status

## Glossary

## [Glossary](../glossary-2/README.md)

- [Glossary of eSIM status](../glossary-2/glossary-of-esim-status.md)
- [Telecom glossary](../telecom-glossary.md)
- [OCS Glossary](../glossary.md)

## [SIM Lifecycle glossary](README.md)

- [The Sleep Mode (Tariff Holiday) - IoT optional status](the-sleep-mode-tariff-holiday-iot-optional-status.md)
- [the Test Mode for IoT SIMs](../../services/iot-services/the-test-mode.md)
- [IoT SIM Lifecycle](iot-sim-lifecycle.md)
- [SIM Statuses](../sim-statuses.md)

## On this page

# The Sleep Mode (Tariff Holiday) – IoT optional status

**The Sleep Mode (Tariff Holiday) – IoT optional status**

The Sleep Mode is an optional status that can be used for IoT SIMs.  
It is also known under the name “Tariff Holiday”, especially in technical reports and API requests.  
  
![image](/knowledge-center/assets/image-1.png)
  
The Sleep Mode allows you to **block usages and suspend charges** for a SIM for a limited number of days.  
  
If you SIM has a commitment period, the number of days spent in Sleep Mode do not count. Only days spent in billed statuses, such as Active or Suspended status are part of the commitment period.

**How to use the Sleep Mode**

– To benefit from the Sleep Mode, it must be activated for your account, and has a special fee.  
Please contact your account manager to get it set up for your account.  
– Once Sleep mode is active for your account, you can then use the interface to request a Switch to Sleep Mode, or perform the change via [API request](https://api.transatel.com/connectivity-management/subscribers/docs/index.html#operation/scheduleTariffHolidayUsingPOST).  
  
![image](/knowledge-center/assets/image-2.png)
  
The change is not immediate, but is **scheduled for start the 1st day of the next Bill Cycle**   
On the 1st day of the following month, the SIM will switch to Sleep mode – this is when the susbcription fees will be paused.   
You can see in this example of log a request to plan the switch to Sleep Mode, followed by the SIM entering the mode on the 1st :  
![image](/knowledge-center/assets/image-3.png)
  
On the Billing side, all subscription fees will be fully discounted while the SIM is in Sleep Mode.  
Your invoice & detailed invoice files will show the charges, and then a negative equal charge to cancel it.  
  
Once the SIM reaches the maximum number of days in Sleep Mode, it will automatically reactivate.  
The susbcription fee of the ongoing month will be prorated based on the current time of the month.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
