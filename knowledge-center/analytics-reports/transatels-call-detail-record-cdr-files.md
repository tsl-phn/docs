---
title: "Transatel\u2019s Call Detail Record (CDR files)"
---

# Transatel’s Call Detail Record (CDR files)

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

# Transatel’s Call Detail Record (CDR files)

**About Transatel’s CDR**

CDR – Call Detail Records are, as their name suggests, the records of a call (call may be voice, data or SMS).  
The content of the record varies (we’ll go further on this below), but they generally contain the timestamp, duration or volume, and details on the call such as location, destination/recipient, roaming or not…  
  
The CDRs of each line that generated traffic are then aggregated in a single file for the whole account, at a specific frequency .  
  
Transatel provides two types of CDRs:  
– [Near Real Time CDRs](https://docs.transatel.com/uncategorized/near-real-time-cdrs/) (NRT CDRs):   
– [Rated CDRs](report-files/rated-call-detail-records-cdrs.md)   
Depending on your framework and your options, only one of the two types may be available to you.  
  
CDRs are the best method to display usage details in your own interface if you have integrated our APIs. You will need to implement an automated task to retrieve the files from the SFTP directory where they are deposited and import them in your system.  
  
The CDR files deposited on the SFTP directory are in CSV files compressed in GZ format. GZ files can be unzipped using any ZIP software (WinZip, 7-Zip…) or for Windows users, by using the ‘tar’ command in the Windows Command Prompt

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
