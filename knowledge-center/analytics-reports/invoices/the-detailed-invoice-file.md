---
title: "The detailed invoice file"
---

# The detailed invoice file

## Analytics & Reports

## [Analytics Reports](../business-intelligence-reports/README.md)

- [About the Analytics Reports](../business-intelligence-reports/how-to-access-the-bi-reports-for-iot-customers.md)
- [Using the Fleet overview report](../understanding-each-bi-report-in-the-interface.md)
- [Using the Usage Overview report](../how-to-use-the-usage-overview-report.md)
- [Using the Worldwide Usage report](../how-to-use-the-worldwide-usage-report.md)
- [Using the Top Consumption report](../how-to-use-the-top-consumption-report.md)
- [Using the Pooled bundle management report](../using-the-pooled-bundle-management-report.md)
- [Using the Billing Reports](../business-intelligence-reports/billing-reports.md)

## [Invoices](README.md)

- [The detailed invoice file](the-detailed-invoice-file.md)
- [Understanding your Transatel invoice](../iot-understanding-your-transatel-invoice.md)
- [Using the Billing Reports](../business-intelligence-reports/billing-reports.md)

## [Report files](../report-files/README.md)

- [Transatel's Call Detail Records (CDR files)](../report-files/transatels-call-detail-records-cdr-files.md)
- [Wholesale Call Detail Records (Wholesale CDRs / Rated CDRs)](../report-files/wholesale-call-detail-records-wholesale-cdrs-rated-cdrs.md)
- [Bundle inventory report](../report-files/bundle-inventory-report.md)
- [SIM delivery file](../report-files/sim-delivery-file.md)
- [Near Real Time Call Detail Records (NRT CDRs)](../report-files/near-real-time-call-detail-records-nrt-cdrs.md)
- [Switching Termination Fees report](../report-files/switching-termination-fees-report.md)
- [Services report](../services-report.md)
- [Subscription report](../report-files/subscription-report.md)
- [Portability information report](../../uncategorized/portability-information-report.md)
- [SIM Swap report](../report-files/sim-swap-report.md)
- [Transatel's Call Detail Record (CDR files)](../transatels-call-detail-record-cdr-files.md)
- [Rated Call Detail Records (Rated CDRs)](../report-files/rated-call-detail-records-cdrs.md)
- [Near Real Time Call Detail Records (NRT CDRs)](../near-real-time-cdrs.md)
- [Your Transatel SFTP account](../your-transatel-sftp-account.md)

## On this page

# The detailed invoice file

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

## On this page
