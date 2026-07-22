---
title: "Data session diagnostic tool"
---

# Data session diagnostic tool

## SIM Management​

## [Checking your SIM card details](../../sim-management/checking-your-sim-card-details/README.md)

- [Adding Subscriber Data in Bulk](../../sim-management/adding-subscriber-data-in-bulk.md)
- [Using Metadata (custom fields)](../../sim-management/metadata-custom-fields.md)
- [eSIM Quickstart Guide](../../sim-management/checking-your-sim-card-details/esim-quickstart-guide.md)
- [eSIM FAQs](../../sim-management/checking-your-sim-card-details/esim-faqs.md)
- [What are the different types of SIM? (Sales/Swap)](../../sim-management/checking-your-sim-card-details/what-are-the-different-types-of-sim-sales-swap.md)
- [Everything you need to know about SIM cards](../../sim-management/all-you-want-to-know-about-the-sim-cards.md)
- [SIM page & checkup panel overview](../../sim-management/sim-page-overview.md)
- [Adding or editing SIM and subscriber information](../../sim-management/how-to-group-tag-and-label-your-sims.md)
- [SIM's history and logs](../../sim-management/checking-a-sims-history-and-logs.md)
- [Checking a SIM's data usage](../../sim-management/sim-usage-history.md)
- [Finding an eSIM's status and retrieving the activation code](../../sim-management/how-to-find-an-esims-status-and-retrieve-the-activation-code.md)
- [Error CDRs](../../sim-management/checking-your-sim-card-details/error-cdrs.md)

## [Activate or change SIM status](../../sim-management/activate-or-change-sim-status/README.md)

- [Activating a single SIM card](../../sim-management/activating-a-single-sim-card-2.md)
- [SIM Swap](../../sim-management/activate-or-change-sim-status/sim-swap.md)
- [MSISDN Swap](../../sim-management/msisdn-swap.md)
- [SIM Lifecycle](../../sim-management/activate-or-change-sim-status/sim-lifecycle.md)
- [Activating a single SIM card](../../uncategorized/activating-a-single-sim-card.md)
- [Activating a single IoT SIM card](../../sim-management/activate-or-change-sim-status/how-to-activate-a-single-iot-sim-card.md)
- [Activating SIM cards in bulk](../../sim-management/activate-or-change-sim-status/how-to-activate-sim-cards-in-bulk.md)
- [Performing actions in bulk](../../sim-management/how-to-perform-actions-in-bulk.md)

## [Managing Groups](../../sim-management/managing-groups/README.md)

- [Creating groups of SIMs](../../sim-management/creating-groups-of-sims.md)
- [Editing, managing or deleting SIM groups](../../sim-management/managing-groups/how-to-edit-manage-or-delete-sim-groups.md)
- [Adding multiple SIMs to a group](../../sim-management/how-to-add-multiple-sims-to-a-group.md)
- [Removing SIMs from a group](../../sim-management/managing-groups/how-to-remove-a-sim-from-a-group.md)
- [Adding a SIM to a group](../../sim-management/managing-groups/how-to-add-a-sim-to-a-group.md)

## [Real-time diagnostics](https://docs.transatel.com/sim-management/real-time-diagnostics/)

- [Data session diagnostic tool](data-session-diagnostic-tool.md)
- [Network attach diagnostic](../../sim-management/network-attach-diagnostic.md)

## [Mobile Number Portability](../../sim-management/mobile-number-portability/README.md)

- [Sw-API: providing custom switching information](../../sim-management/mobile-number-portability/sw-api-providing-custom-switching-information.md)
- [Switching Information](../../sim-management/mobile-number-portability/switching-information.md)
- [Managing Mobile Number Portability in Belgium](../../sim-management/mobile-number-portability/managing-mobile-number-portability-in-belgium.md)
- [Number Portability: everything you need to know](../../sim-management/mobile-number-portability/number-portability.md)
- [Managing Mobile Number Portability in France](../../sim-management/mobile-number-portability/managing-mobile-number-portability-in-france.md)
- [Managing Mobile Number Portability in the UK](../../sim-management/mobile-number-portability/managing-mobile-number-portability-in-the-uk.md)
- [How do I enter switching information in Auriga?](../../sim-management/mobile-number-portability/mvna-uk-how-do-i-enter-switching-information-in-auriga.md)
- [[MVNA UK] What is Switching Information?](../../sim-management/mobile-number-portability/mvna-uk-switching-information.md)

## On this page

# Data session diagnostic tool

**Data session diagnostic tool**

Transatel’s SIM Management platform allows you to know the following information about the data session of your SIM card in real-time:  
  
Note: this tool is not available for customers on MVNO France Light and MVNO UK frameworks  
  
– **The visited network**  
In this first iteration, we will display the Visited Network Identity code, which is a combination of the Mobile Country Code (MCC) & the Mobile Network Code (MNC)   
For example, 20815 will appear for a SIM in France (208) on the Free (15) network.   
You can look up the code here: [https://www.mcc-mnc.com](https://www.mcc-mnc.com/)    
 – **Bearer**  
Radio access technology currently in use: 2G, 3G, 4G, 5G  
 – **The APN** (Access Point Name) used for the session   
It can be either our default, dedicated-to-the-IoT “mobiledata” APN, or your business’ private APN   
 – The device’s **private IP address**  
 – The device’s **IMEI**and**IMEISV**   
The IMEI (International Mobile Equipment Identity) is the unique identifier of your device. It consists of 15 digits: 14 + luhn digit. On hover, the IMEISV is displayed = 14 + SV (Software Version) = 16 Digits  
  
**How to access and use the tool?**  
  
Go to the line view of your SIM, and in the checkup panel, click on “See more info” in the Last Communications section. This will launch the tool instantly.  
  
See it in action below:  
![image](/knowledge-center/assets/image-1.gif)
  
As the tool is in real-time, it will only display information if there is an ongoing data session.  
If there is no active data session, you will see this message:  
  
![image](/knowledge-center/assets/image-2.png)

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
