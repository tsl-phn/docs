---
title: "Switching Termination Fees report"
---

# Switching Termination Fees report

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

# Switching Termination Fees report

**Switching Termination Fees report**

**About switching**  
Transatel allows MVNOs to enter their subscribers’ termination fees in case of [switching](../../sim-management/mobile-number-portability/managing-mobile-number-portability-in-the-uk.md) via our Auriga interface.  
More information on the Termination Fees that can be entered can be found [here](../../sim-management/mobile-number-portability/mvna-uk-how-do-i-enter-switching-information-in-auriga.md).  
  
**About the Termination Fees report**  
By default, at 00:00 on on the first day of each month, Transatel will generate a CSV report containing all of the Termination Fees that the MVNO has entered into Auriga.  
It is exported to the directory */Exports/Reports/SwitchingFees*, and it will be named *MVNOaccountname\_SwitchingTerminationFee\_YYYYMMDD.csv*  
The files will be automatically removed from the sFTP server after 90 days.  
  
**Fields**  
  
**TransatelId**: A unique number (19 integer) assigned by Transatel to a SIM. This number is in general printed on the SIM  
**MvnoRef**: MVNO account name  
**Handsetfee**: handset fees in decimal format  
**Handsetexpirationdate**: handset contract end date in “yyyy-MM-dd” format  
**Monthlyfee**: fees in decimal format  
**MaximumFee**: maximum fees in decimal format  
**Monthlychargeexpirationdate**: contract end date in “yyyy-MM-dd” format  
**Fixedfee**: fees in decimal format  
**Fixedchargeexpirationdate**: contract end date in “yyyy-MM-dd” format

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
