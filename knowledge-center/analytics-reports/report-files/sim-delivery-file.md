---
title: "SIM delivery file"
---

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
