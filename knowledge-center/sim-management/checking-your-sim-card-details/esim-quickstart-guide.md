---
title: "eSIM Quickstart Guide"
---

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
