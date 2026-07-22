---
title: "eSIM Quickstart Guide"
---

# eSIM Quickstart Guide

## SIM Management​

## [Checking your SIM card details](README.md)

- [Adding Subscriber Data in Bulk](../adding-subscriber-data-in-bulk.md)
- [Using Metadata (custom fields)](../metadata-custom-fields.md)
- [eSIM Quickstart Guide](esim-quickstart-guide.md)
- [eSIM FAQs](esim-faqs.md)
- [What are the different types of SIM? (Sales/Swap)](what-are-the-different-types-of-sim-sales-swap.md)
- [Everything you need to know about SIM cards](../all-you-want-to-know-about-the-sim-cards.md)
- [SIM page & checkup panel overview](../sim-page-overview.md)
- [Adding or editing SIM and subscriber information](../how-to-group-tag-and-label-your-sims.md)
- [SIM's history and logs](../checking-a-sims-history-and-logs.md)
- [Checking a SIM's data usage](../sim-usage-history.md)
- [Finding an eSIM's status and retrieving the activation code](../how-to-find-an-esims-status-and-retrieve-the-activation-code.md)
- [Error CDRs](error-cdrs.md)

## [Activate or change SIM status](../activate-or-change-sim-status/README.md)

- [Activating a single SIM card](../activating-a-single-sim-card-2.md)
- [SIM Swap](../activate-or-change-sim-status/sim-swap.md)
- [MSISDN Swap](../msisdn-swap.md)
- [SIM Lifecycle](../activate-or-change-sim-status/sim-lifecycle.md)
- [Activating a single SIM card](../../uncategorized/activating-a-single-sim-card.md)
- [Activating a single IoT SIM card](../activate-or-change-sim-status/how-to-activate-a-single-iot-sim-card.md)
- [Activating SIM cards in bulk](../activate-or-change-sim-status/how-to-activate-sim-cards-in-bulk.md)
- [Performing actions in bulk](../how-to-perform-actions-in-bulk.md)

## [Managing Groups](../managing-groups/README.md)

- [Creating groups of SIMs](../creating-groups-of-sims.md)
- [Editing, managing or deleting SIM groups](../managing-groups/how-to-edit-manage-or-delete-sim-groups.md)
- [Adding multiple SIMs to a group](../how-to-add-multiple-sims-to-a-group.md)
- [Removing SIMs from a group](../managing-groups/how-to-remove-a-sim-from-a-group.md)
- [Adding a SIM to a group](../managing-groups/how-to-add-a-sim-to-a-group.md)

## [Real-time diagnostics](https://docs.transatel.com/sim-management/real-time-diagnostics/)

- [Data session diagnostic tool](../../devices-set-up-troubleshooting/diagnostic-tools/data-session-diagnostic-tool.md)
- [Network attach diagnostic](../network-attach-diagnostic.md)

## [Mobile Number Portability](../mobile-number-portability/README.md)

- [Sw-API: providing custom switching information](../mobile-number-portability/sw-api-providing-custom-switching-information.md)
- [Switching Information](../mobile-number-portability/switching-information.md)
- [Managing Mobile Number Portability in Belgium](../mobile-number-portability/managing-mobile-number-portability-in-belgium.md)
- [Number Portability: everything you need to know](../mobile-number-portability/number-portability.md)
- [Managing Mobile Number Portability in France](../mobile-number-portability/managing-mobile-number-portability-in-france.md)
- [Managing Mobile Number Portability in the UK](../mobile-number-portability/managing-mobile-number-portability-in-the-uk.md)
- [How do I enter switching information in Auriga?](../mobile-number-portability/mvna-uk-how-do-i-enter-switching-information-in-auriga.md)
- [[MVNA UK] What is Switching Information?](../mobile-number-portability/mvna-uk-switching-information.md)

## On this page

# eSIM Quickstart Guide

****About eSIM****

Transatel eSIMs are the same as Transatel’s Physical SIMs but 100% digital. They will behave in the same way as a Physical SIM, and you can provide the same services. They will have a UK IMSI and MSISDN. The SPN will be delivered OTA upon activation like physical SIMs.

****Journey Overview****

1. [MVNO] Orders eSIMs from Transatel  
2. [MVNO] Selects an available eSIM and activate it  
3. [MVNO] Retrieves the QR Code/Activation Code via Auriga/API and sends it to the subscriber  
4. [Subscriber] Goes to the eSIM setup menu and scans the QR code / enters the activation code when prompted  
5. [Subscriber] Waits for a few seconds to minutes to download the eSIM profile  
6. [MVNO] Sends a Refresh to the SIM to ensure the SPN OTA download

****Stock Management****

Transatel’s MVNOs can manage their stock of eSIMs in the same way as they do with Physical SIMs. MVNOs are able to order sales and swap eSIMs and upon delivery will receive an output file with all of the information for the eSIM stocks to be integrated into the BSS or inventory system.  
MVNOs can order eSIMs via the SIM order form (it is possible to order both physical SIMs and eSIMs at once), which can be obtained from your Account Manager.

****Retrieving QR codes****

The QR codes can be displayed in 3 different ways:  
– In Auriga > select an available eSIM > Other actions > Retrieve eSIM activation code  
![image](/knowledge-center/assets/image-1.png)
– Via SIM Management API > [Get eSIM details](https://api.transatel.com/sim-management/sims/docs/index.html#operation/getEsimDetailsUsingGET) > QR code  
![image](/knowledge-center/assets/image-2.png)
– Use a conversion tool to convert the activation code supplied in the SIM Delivery file into a QR code  
![image](/knowledge-center/assets/image-3.png)

****eSIM lifecycle****

eSIMs and Subscribers follow two different lifecycles:  
For Transatel eSIMs, these only have the status “released” meaning they are ready for download. No other statuses are available.  
![image](/knowledge-center/assets/image-4.png)
The Subscriber lifecycle remains the same as physical SIMs:  
![image](/knowledge-center/assets/image-5.png)

****Activating Subscribers for eSIMs****

For an optimum client experience, we recommend that the Subscriber be activated before the eSIM is downloaded, as downloading an inactive eSIM will leave the SIM status on the handset as “pending activation”. You can activate an eSIM Subscriber using the standard procedure as per physical SIMs. Once the Subscriber has been activated, the device must be restarted to enable the eSIM.  
![image](/knowledge-center/assets/image-6.png)
/!\ Remember the subscriber must be connected to the internet to download an eSIM /!\  
/!\ As the SIM is activated before being installed, the OTA mechanism for the SPN is triggered before it can be received by the device. The OTA should be resent via a SIM Refresh following eSIM installation /!\

****Swapping eSIMs****

Transatel eSIMs can only be downloaded once. This means that the QR code cannot be scanned a second time. You will need to provide the Subscriber with a “Swap” eSIM to be able to re-download an eSIM with their MVNO services. This is required, for example:  
– If the eSIM is deleted from the device  
– If the eSIM needs to be installed on a new device (either a replacement or upgrade)

****Switching from Physical SIM to eSIM****

Some Subscribers may wish to swap their MVNO Physical SIM to eSIM.  
*For example, they may want to have both their work and personal numbers on the same device (to avoid carrying two mobile phones with them).*  
  
To do this, the Subscriber must first be provided with a Swap eSIM and then a simple SIM swap must be performed from the Physical SIM to the provided eSIM.

****Further information****

Another question? Visit the [eSIM FAQs](https://docs.transatel.com/sim-management/checking-your-sim-cards-details/esim-faqs/)!

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
