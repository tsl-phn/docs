---
title: "Using the Pooled bundle management report"
---

# Using the Pooled bundle management report

## Analytics & Reports

## [Analytics Reports](business-intelligence-reports/README.md)

- [About the Analytics Reports](business-intelligence-reports/how-to-access-the-bi-reports-for-iot-customers.md)
- [Using the Fleet overview report](understanding-each-bi-report-in-the-interface.md)
- [Using the Usage Overview report](how-to-use-the-usage-overview-report.md)
- [Using the Worldwide Usage report](how-to-use-the-worldwide-usage-report.md)
- [Using the Top Consumption report](how-to-use-the-top-consumption-report.md)
- [Using the Pooled bundle management report](using-the-pooled-bundle-management-report.md)
- [Using the Billing Reports](business-intelligence-reports/billing-reports.md)

## [Invoices](invoices/README.md)

- [The detailed invoice file](invoices/the-detailed-invoice-file.md)
- [Understanding your Transatel invoice](iot-understanding-your-transatel-invoice.md)
- [Using the Billing Reports](business-intelligence-reports/billing-reports.md)

## [Report files](report-files/README.md)

- [Transatel's Call Detail Records (CDR files)](report-files/transatels-call-detail-records-cdr-files.md)
- [Wholesale Call Detail Records (Wholesale CDRs / Rated CDRs)](report-files/wholesale-call-detail-records-wholesale-cdrs-rated-cdrs.md)
- [Bundle inventory report](report-files/bundle-inventory-report.md)
- [SIM delivery file](report-files/sim-delivery-file.md)
- [Near Real Time Call Detail Records (NRT CDRs)](report-files/near-real-time-call-detail-records-nrt-cdrs.md)
- [Switching Termination Fees report](report-files/switching-termination-fees-report.md)
- [Services report](services-report.md)
- [Subscription report](report-files/subscription-report.md)
- [Portability information report](../uncategorized/portability-information-report.md)
- [SIM Swap report](report-files/sim-swap-report.md)
- [Transatel's Call Detail Record (CDR files)](transatels-call-detail-record-cdr-files.md)
- [Rated Call Detail Records (Rated CDRs)](report-files/rated-call-detail-records-cdrs.md)
- [Near Real Time Call Detail Records (NRT CDRs)](near-real-time-cdrs.md)
- [Your Transatel SFTP account](your-transatel-sftp-account.md)

## On this page

# Using the Pooled bundle management report

**Using the Pooled bundle management report**

The Pooled bundle report is currently in beta phase and slowly being deployed to our customers.  
  
This article will explain how to make the most out of the report’s capabilities  
  
The report has 4 main features:  
– it shows you the consumption made part of the pool’s volume, out of bundle, and out of the pool’s geographic area all along the month (updated every hour)  
– it displays the allowance remaining in the pool  
– it highlights SIMs with the highest usage in the pool  
– it calculates average usage, letting you know if the pool is the good fit   
  
**How does it work?**  
  
To access the report, go to T**racking & Reports > BI Reports**, and in the drop-down list, select pooled bundles management  
![image](/knowledge-center/assets/image-1.png)
  
The report will open empty. To display data, select a pooled bundle and a month in the filter panel on the left side:  
  
![image](/knowledge-center/assets/image-2.png)
The report will then load data according to your selection.

**Total usage** 

The 3 squares at the top middle show usage for the month:  
– made as part of the pool’s volume  
– made out-of-bundle (if the pool’s volume was exhausted)  
– made out-of-area (in a geographic location not included in the pool)  
Usage is displayed in MB by default, but you can switch to KB or GB by using the filter on the right  
  
![image](/knowledge-center/assets/image-3.gif)

**Monthly histogram view**

Usage in green is in-bundle, and usage in pink is out-of-bundle (that is charged in addition of the pool’s monthly fee).  
If your fleet is only consuming as part of the pooled bundle, it will look like this:  
  
![image](/knowledge-center/assets/image-4.png)
However, if some SIMs are making usage out-of-area or if the pool’s volume is exhausted, you’ll start to see out-of-bundle usage displayed in pink.  
In the example below, we clearly see that the pool was exhausted on July 27th, and that the fleet started making out-of-bundle usage:  
   
![image](/knowledge-center/assets/image-5.png)
  
You can hover your cursor over each day to get the total usage in and out of bundle:  
  
![image](/knowledge-center/assets/image-6.gif)

**Top SIM display**

On the right side, you can show the 200 SIMs with the highest usage.   
You have the possibility to filter on out-of-bundle usage or in-bundle usage only.  
  
![image](/knowledge-center/assets/image-9.png)
  
Click on a SIM, and the detailed view page will open in a new tab, enabling you to check if the usage is normal for this particular card.  
 ![image](/knowledge-center/assets/image-10.gif)

**Number of SIMs & Average usage**

Finally, the last item of the report shows:  
 – how many SIMs were in the pool at the beginning of the month – this gives a general idea of the total size of the pool (but additional SIMs activated since can have increased the total amount)  
– how much data has been consumed in average by the SIM cards in use (SIMs with no data consumption during the month are not included in this average) – this lets you know if the pool’s volume is the right fit for your SIM’s average usage.  
  
![image](/knowledge-center/assets/image-11.png)
  
For example, if your SIMs with usage have consumed 73MB in average on a complete month, a 100MB pool is a good fit.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
