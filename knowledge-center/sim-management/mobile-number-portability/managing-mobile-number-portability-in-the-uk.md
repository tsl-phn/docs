---
title: "Managing Mobile Switching in the UK"
---

**Switching includes  
– Porting (Mobile Number Portability)  
– Switching  
– Info (Switching information)**

**Some general terms to understand:**  
  
**PAC – Porting Authorisation Code:** a code allowing an end user to port their MSISDN from an operator to another in UK. It has 3 letters followed by 6 numbers.  
  
**STAC – Service Termination Authorisation Code:** a code allowing an end user to switch from an operator to another in UK without having to contact their current provider. It has 6 numbers followed by 3 letters.  
  
**MSISDN**: a unique mobile number attached to each SIM card.  
  
**SIM Management Portal**: Transatel’s SIM provisioning interface available to Service Providers, through which aspects of subscription and supporting functions can be configured.  
  
**Donor**: operator hosting the MSISDN at the beginning of a portability process.  
  
**Recipient**: operator initiating the portability request to host a MSISDN from another operator.  
  
Follow our [step-by-step guide](https://papyrus-dev.priv.transatel.net/docs/connectivity-management-guides-uk-portin/) to SIM card activation on our **Developer’s Portal**.

****How does a subscriber port their number to my MVNO?**  
  
![image](/knowledge-center/assets/image-1.png)**

****What is the portability/**switching **process in t**he **UK?****

1. The subscriber provides their PAC/STAC code to their new (recipient) operator  
  
2. The recipient operator submits the request to the porting coordinator in the UK, Syniverse. Syniverse can accept the request or reject the request when the PAC does not match the MSISDN that needs porting.  
During this step, it is still possible for the recipient to cancel the request or to postpone it.2.   
  
3. Syniverse notifies both the recipient and donor operators that the portability will be executed the next day. The request is frozen and modifications are prohibited.  
The deadline for locking in the portability request in the porting system is before 5pmthe day prior to the porting occurring.  
The process will not be validated if the request is made less than one working day before the wished portability of your subscriber.  
  
4. On the porting day, the recipient operator activates the ported number on the line. The donor operator performs the routing of all inbound traffic to the recipient operator. The processes should be completed around 18:00.

****How** do you **retrieve a portability/**switching **code, PAC/STAC?****

The end user will request either a PAC or STAC code, depending on whether they want to keep their current number or acquire a new one.  
The subscriber must request the code from their current operator. Once received, they will then be able to send this code to the new (recipient) operator.\*  
  
A subscriber should be able to request their code:  
–          by SMS  
–          by phone  
–          through a Web Portal or app  
  
A PAC or a STAC can be used for 30 days, and after this, it will automatically expire.

****What do I have to do as an MVNO?****

When a new subscriber wants to migrate to your services, you have to make a portability request to Transatel. The information required for portability includes the MSISDN, PAC or STAC and the portability date.  
  
Portability will be eligible if:  
– The SIM is active when the portability is made  
– There is no other portability on the Transatel line and on the number  
– A valid portability date has been chosen  
  
The end-user can also request for a portability to be triggered once the SIM attaches to a network, without a specific portability date.   
  
Once the eligibility is validated, the portability will be executed. The portability MSISDN is completed on the donor side and is now used on the recipient side.

****What portability actions can I take as a Service Provider?****

All portability actions can be taken using our portability APIs, in the Web Front End or using a CSV (comma-separated values) file.  
  
As an MVNO on Transatel’s platform, you can:  
  
–          Cancel a portability request  
If the subscriber wants to cancel his portability request, you can make the request directly to Transatel.  
  
The cancellation can only be done during the eligibility period. The MVNO will then be notified by Transatel when the cancellation of the portability is done.  
  
–          Change a portability date  
You can change the date of portability up until the validation has been accepted.

**What information do I need to provide as an MVNO, to a subscriber who wants to port-out?**

When a subscriber asks for a PAC or STAC code, they should receive along with this code some additional switching information (“Switching Info”). This information includes:  
  
–          Early termination fees   
–          Credit balance for prepaid subscribers  
–          Web-link to the subscriber’s account login page  
–          Outstanding loans for a handset  
–          Impact on any other services provided  
–          Contract end date  
  
From this point on, you will have no more operations to do. This PAC or STAC will be used by the recipient operator to launch the portability or the switch. You will be informed about the progress thanks to the events.

Switching shortcodes can only be accessed from the UK, they will not work in roaming

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
