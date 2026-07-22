---
title: "Transatel\u2019s Call Detail Records (CDR files)"
---

**About Transatel’s CDRs**

CDR – Call Detail Records are, as their name suggests, the records of a call (call may be voice, data or SMS).  
The content of the record varies (we’ll go further on this below), but they generally contain the timestamp, duration or volume, and details on the call such as location, destination/recipient, roaming or not…  
  
The CDRs of each line that generated traffic are then aggregated in a single file for the whole account, at a specific frequency .  
  
Transatel provides two types of CDRs:  
– [Near Real Time CDRs](near-real-time-call-detail-records-nrt-cdrs.md) (NRT CDRs):   
– [Wholesale CDRs](wholesale-call-detail-records-wholesale-cdrs-rated-cdrs.md) (or Rated CDRs)  
Depending on your framework and your options, only one of the two types may be available to you.  
  
CDRs are the best method to display usage details in your own interface if you have integrated our APIs. You will need to implement an automated task to retrieve the files from the SFTP directory where they are deposited and import them in your system.  
  
The CDR files deposited on the SFTP directory are in CSV files compressed in GZ format. GZ files can be unzipped using any ZIP software (WinZip, 7-Zip…) or for Windows users, by using the ‘tar’ command in the Windows Command Prompt

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
