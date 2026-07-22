---
title: "How to find your SIMs\u2019 static IP?"
---

If your offer contains one of our static IP services (private or fixed static IP), we offer two solutions enabling you to retrieve the IPs assigned to your SIMs.

- Whole fleet IP retrieval: in a **dedicated report** generated daily for your whole fleet – Perfect to retrieve all IPs at once
- Individual IP check: in the **detailed view** of the SIM in our interface – Great for finding out the IP immediately  
    
  Before we detail how to use each method, here are a few important notes regarding the assignation of static IPs:   
  IPs are paired with the SIMs at the first data session:
- If you have just switched your SIM card from dynamic IPs to fixed IPs, a new data session must be started for the fixed IP to be assigned
- If your SIM has not made a first data session, you cannot retrive the static IP

## The Single IP Report

Every morning (around 10AM Paris time), a file containing all fixed IPs (public or private) assigned to SIMs active in the last 30 days is deposited on your account’s SFTP, and can be downloaded from our interface.

**In the interface**  
The reports can be downladed in “Tracking & Reports” > “File Reports” > “Fleet inventory”

![image](/knowledge-center/assets/image-1.png)

**On the SFTP**  
You will find the daily reports in the “Reports” folder:

![image](/knowledge-center/assets/image-2.gif)

The file format is as follows:

![image](/knowledge-center/assets/image-3.png)

## In the interface

If you wish to immediately retrieve the IP assigned to a SIM, go to the detailed SIM view in our SIM Management Portal.

**New! You can now see the IP in the line details**

In the SIM’s detailed view, click on “see more info”

![image](/knowledge-center/assets/image-4.png)

and the IP will be the last field:

![image](/knowledge-center/assets/image-5.png)

If the SIM currently has an active data session, the IP will also be displayed in the data session tool, in the checkup bar:  
  
![image](/knowledge-center/assets/image-6.gif)
  
Please note that the interface still displays “Private IP” even if a public IP is being used.  
  
If there is no active data session, the IP of the previously made sessions can be found in the data usage tab – if you do not see the IP column, check that this field in selected by clicking on the “+” :  
  
![image](/knowledge-center/assets/image-7.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
