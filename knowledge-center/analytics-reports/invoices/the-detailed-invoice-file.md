---
title: "The detailed invoice file"
---

**The detailed invoice file**

Each month, our Billing generates 2 specific files enabling customers to process their monthly invoice:  
– the generic invoice, in PDF format  
– the detailed invoice file, in CSV format  
  
Both files are deposited on your dedicated [SFTP account](../your-transatel-sftp-account.md), in the “Invoices” folder.  
This article will explain in detail how the detailed invoice file is built.  
For information on the PDF invoice file, please check [this article](../iot-understanding-your-transatel-invoice.md).  
  
The “Transatel Bill Details” report is a csv file.  
Each batch file has a unique name per the following specification:  
TransatelBillDetails\_xxxxxxxx\_YYYYMM.csv  
  
Where:  
• TransatelBillDetails: is a literal value that identifies this file type. This does not  
change.  
*• xxxxxxxx: Transatel reference number for Customer (CustomerNumber). 8 digits. This does not change.*   
• YYYYMM is the Data-Time stamp of the Bill Cycle concerned by the file.  
  
![image](/knowledge-center/assets/image-1.png)
  
The detailed invoice file is also used as reference data for the [Billing Reports](../business-intelligence-reports/billing-reports.md) in the “Analytics Reports” menu.

**How is the file built**

The file lists all the charges that occurred during a given month, at *subscriber* level.  
There are 2 “types” of Subscriber:  
– the “account” subscriber, to which all account level charges are related (account fees, option fees…)   
This account subscriber has the number xxxxxxx.0000000 -where “xxxxxx” is your Customer Number.  
– “line” subscriber, each SIM/line has a dedicated number.   
  
![image](/knowledge-center/assets/image-2.png)

**Charge categories** 

The charge categories are as follows:  
  
![image](/knowledge-center/assets/image-3.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
