---
title: "SIM delivery file"
---

# SIM delivery file

## Analytics & Reports

## [Analytics Reports](../business-intelligence-reports/README.md)

- [About the Analytics Reports](../business-intelligence-reports/how-to-access-the-bi-reports-for-iot-customers.md)
- [Using the Fleet overview report](../understanding-each-bi-report-in-the-interface.md)
- [Using the Usage Overview report](../how-to-use-the-usage-overview-report.md)
- [Using the Worldwide Usage report](../how-to-use-the-worldwide-usage-report.md)
- [Using the Top Consumption report](../how-to-use-the-top-consumption-report.md)
- [Using the Pooled bundle management report](../using-the-pooled-bundle-management-report.md)
- [Using the Billing Reports](../business-intelligence-reports/billing-reports.md)

## [Invoices](../invoices/README.md)

- [The detailed invoice file](../invoices/the-detailed-invoice-file.md)
- [Understanding your Transatel invoice](../iot-understanding-your-transatel-invoice.md)
- [Using the Billing Reports](../business-intelligence-reports/billing-reports.md)

## [Report files](README.md)

- [Transatel's Call Detail Records (CDR files)](transatels-call-detail-records-cdr-files.md)
- [Wholesale Call Detail Records (Wholesale CDRs / Rated CDRs)](wholesale-call-detail-records-wholesale-cdrs-rated-cdrs.md)
- [Bundle inventory report](bundle-inventory-report.md)
- [SIM delivery file](sim-delivery-file.md)
- [Near Real Time Call Detail Records (NRT CDRs)](near-real-time-call-detail-records-nrt-cdrs.md)
- [Switching Termination Fees report](switching-termination-fees-report.md)
- [Services report](../services-report.md)
- [Subscription report](subscription-report.md)
- [Portability information report](../../uncategorized/portability-information-report.md)
- [SIM Swap report](sim-swap-report.md)
- [Transatel's Call Detail Record (CDR files)](../transatels-call-detail-record-cdr-files.md)
- [Rated Call Detail Records (Rated CDRs)](rated-call-detail-records-cdrs.md)
- [Near Real Time Call Detail Records (NRT CDRs)](../near-real-time-cdrs.md)
- [Your Transatel SFTP account](../your-transatel-sftp-account.md)

## On this page

# SIM delivery file

**SIM delivery file**

Transatel will send by email, or FTP if requested by the Service Provider, the different SIM details in a single file. This file will have the following structure:  
  
*“Simdelivery – YYYYMMDD – SP’s Name – Nb\_of\_simcards.csv”*  
  
Where:  
– *YYYYMMDD* = date of file generation  
– *Nb\_of\_SIM\_card*, the number of delivered SIM cards  
  
Format: .CSV file (using “;” as separator value)  
Content: 1 SIM record per row (with column headings line)

****Fields** (Physical SIM Order)**

**TransatelId** (Integer): Transatel internal ID used as reference for the SIM.  
**MSISDN** (‘+’Integer): Associated MSISDN of the SIM card, international format including ‘+’  
**Release** (Text): Electric profile reference configured on the SIM  
**ICCID** (Integer): SIM serial number (printed near the chip)  
**Status** (Text): Status of the SIM card on the network.  
**PIN** (Integer): Personal Identification Number (4 digits requested when the subscriber turns on their mobile phone)  
**PUK** (Integer): Personal Unblocking Code (8 digits) – code that allows to unlock the SIM after 3 consecutive wrong PIN codes being attempted by the subscriber.

****Fields** (eSIM Order)**

**TransatelId** (Integer): Transatel internal ID used as reference for the SIM.  
**MSISDN** (‘+’Integer): Associated MSISDN of the SIM card, international format including ‘+’  
**Release** (Text): Electric profile reference configured on the SIM  
**ICCID** (Integer): SIM serial number (printed near the chip)  
**Status** (Text): Status of the SIM card on the network.  
**PIN** (Integer): Personal Identification Number (4 digits requested when the subscriber turns on their mobile phone)  
**PUK** (Integer): Personal Unblocking Code (8 digits) – code that allows to unlock the SIM after 3 consecutive wrong PIN codes being attempted by the subscriber.  
**ActivationCode** (1$sm-v4-010-a-gtm.pr.go-esim.com$64F4614560E20CAF5FD97BXXXXXXXXXX): Activation codes to be used for QR code generation

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
