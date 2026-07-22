---
title: "Switching Termination Fees report"
---

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
