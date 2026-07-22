---
title: "SIM Swap"
---

# SIM Swap

## SIM Management​

## [Checking your SIM card details](../checking-your-sim-card-details/README.md)

- [Adding Subscriber Data in Bulk](../adding-subscriber-data-in-bulk.md)
- [Using Metadata (custom fields)](../metadata-custom-fields.md)
- [eSIM Quickstart Guide](../checking-your-sim-card-details/esim-quickstart-guide.md)
- [eSIM FAQs](../checking-your-sim-card-details/esim-faqs.md)
- [What are the different types of SIM? (Sales/Swap)](../checking-your-sim-card-details/what-are-the-different-types-of-sim-sales-swap.md)
- [Everything you need to know about SIM cards](../all-you-want-to-know-about-the-sim-cards.md)
- [SIM page & checkup panel overview](../sim-page-overview.md)
- [Adding or editing SIM and subscriber information](../how-to-group-tag-and-label-your-sims.md)
- [SIM's history and logs](../checking-a-sims-history-and-logs.md)
- [Checking a SIM's data usage](../sim-usage-history.md)
- [Finding an eSIM's status and retrieving the activation code](../how-to-find-an-esims-status-and-retrieve-the-activation-code.md)
- [Error CDRs](../checking-your-sim-card-details/error-cdrs.md)

## [Activate or change SIM status](README.md)

- [Activating a single SIM card](../activating-a-single-sim-card-2.md)
- [SIM Swap](sim-swap.md)
- [MSISDN Swap](../msisdn-swap.md)
- [SIM Lifecycle](sim-lifecycle.md)
- [Activating a single SIM card](../../uncategorized/activating-a-single-sim-card.md)
- [Activating a single IoT SIM card](how-to-activate-a-single-iot-sim-card.md)
- [Activating SIM cards in bulk](how-to-activate-sim-cards-in-bulk.md)
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

# SIM Swap

**SIM Swap**

****What is a SIM Swap?****

A SIM Swap is a process performed to move a subscriber’s subscription (including all of their bundles and settings) and MSISDN from one SIM card to new one.  
  
It is useful in the following situations:  
– A SIM (or a handset with the SIM inside) has been lost or stolen  
– Their SIM has become damaged (i.e. worn from switching devices too often, or water damage)  
– The subscriber is using a uSIM (3G-only SIM) and wants to benefit from 4G/5GNSA by upgrading to an iSIM  
 – The subscriber changes device and the format of the SIM is incompatible in the new device (Mini / Micro / Nano / eSIM) or the plastic frame has been lost to increase the size (i.e. from Micro to Mini SIM) according to the handset SIM card tray  
– A fault is suspected on the SIM card and a swap is used to rule out/fix this type of anomaly  
– (eSIM) the eSIM profile has been deleted from the device  
   
See the different types of SIM [here](https://docs.transatel.com/sim-management/checking-your-sim-cards-details/what-are-the-different-types-of-sim-sales-swap/).

****Can I swap to and from a physical SIM or eSIM?****

All types of Transatel SIMs can be swapped between each other according to the needs of the Subscriber and their devices:  
– Physical SIM to Physical SIM  
– Physical SIM to eSIM  
– eSIM to Physical SIM  
– eSIM to eSIM

****How do I perform a SIM SWAP?****

**1. Find an available Swap SIM**  
  
The Swap SIM is the SIM that will receive the subscriber’s subscriptions and MSISDN at the end of the process.  
  
This will correspond to any of your available SIMs without an MSISDN paired to the SIM. You can use the search functions to filter available SIMs from your entire fleet, and sort by MSISDN to find a SIM that does not have one.  
  
You may want to swap to a physical SIM or an eSIM as highlighted below.  
  
![image](/knowledge-center/assets/image-1.png)
Note the ICCID of the SIM that you want to use for swap.  
  
**2. Go to the subscriber’s current active SIM**  
Go to Auriga and search for the Subscriber’s line (the old one that will be replaced at the end of this process).  
  
**3. On the top-right hand corner, select Other actions > Change SIM**  
![image](/knowledge-center/assets/image-2.png)
  
**4. Enter the ICCID of the Swap SIM (noted in step 1) into the prompt and click confirm**  
  
![image](/knowledge-center/assets/image-3.png)
  
**5. Track the action by going to the page for the Swap SIM in Auriga.**  
  
When the SIM Swap is complete, the old SIM will be terminated, and the new SIM will automatically activate.  
  
**6. Install the SIM**  
  
If using a physical SIM, you can insert the new SIM in the phone at any point of the SIM swap process. In any case, it is important to insert the SIM rapidly after having completed Step 4, so that the new SIM can receive the correct SIM settings via *Over the Air Updates*.  
  
**7. What to do when you have an eSIM**  
  
Depending on your offer, there are different steps to take.   
  
**If you are a UK MVNO:** When using an eSIM, it is best practice to download the eSIM uniquely when the process has completed and the eSIM has been fully activated on the network. Otherwise, the phone will need to be restarted once the Swap process has completed (and the eSIM is active).  
  
**If you are a French MVNO:**First, you must scan the QR code of the eSIM. Once the QR has been downloaded, you can then make the SIM Swap request.   
  
 [See the eSIM quickstart guide](https://docs.transatel.com/sim-management/checking-your-sim-cards-details/esim-quickstart-guide/). It is also best practice now to perform a [refresh](../../devices-set-up-troubleshooting/diagnostic-tools/resynchronise-the-services.md).

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
