---
title: "eSIM: Frequently asked questions"
---

**eSIM FAQs**

**What is an eSIM?**  
An eSIM is a module inside a mobile device that is capable of replacing the normal SIM hardware (i.e. a plastic card with a chip). An eSIM has the particularity of being able to store and access several “eSIM Profiles”.  
   
Furthermore, an eSIM operates the same services for your MVNO (eg. voice services, barrings, bundles etc.) as a traditional physical SIM card. The only difference is that the onboarding journey has become digitalised.  
   
More and more smartphones, tablets, and laptops are equipped with an eSIM following the standards defined by the GSMA. These standards unify the specification for all Network Operators and handset manufacturers to deploy eSIM and eSIM profiles so that they are universally compatible.  
   
**What is an eSIM profile?**  
An eSIM profile is a set of configurations that must be downloaded to an eSIM in order to access the carrier’s mobile network. The eSIM profile is generally presented as an activation code (a URL to the address of the service to download the profile from), or a QR code (linking to the activation code).  
   
**How do I install an eSIM profile?**  
To install an eSIM profile onto your device, there are several options are available:  
Scan a QR code via the eSIM setup wizard on your device to download the eSIM profile and complete the setup of the eSIM directly  
Alternatively, the activation code may be entered manually (or copy and pasted) into the device’s eSIM setup wizard  
Some operators have the rights to install the eSIM profile directly from their own application  
  
/!\  Attention /!\ Most devices do not enter into the eSIM setup journey by scanning directly from the camera app. You must first go into the eSIM setup menu.  
  
**Where can I find the eSIM setup guides for different devices?**  
Apple: <https://support.apple.com/en-us/HT212780>  
Samsung: <https://www.samsung.com/uk/support/mobile-devices/how-to-use-an-esim-with-your-galaxy-phone/>  
Google Pixel: <https://guidebooks.google.com/pixel/explore-your-phone/set-up-esim?hl=en>  
Huawei: <https://consumer.huawei.com/uk/support/content/en-gb15769080/>  
  
**Do I need to be connected to a Wi-Fi or cellular connection to install an eSIM profile?**  
Yes, a data connection or a Wi-Fi connection is needed beforehand to download the eSIM profile when you scan the QR code or enter an Activation Code.  
It can be done with Wifi connection either in HPLMN or VPLMN.  
  
**How can I get eSIM profiles?**  
You can order eSIMs from Transatel in the same way as physical SIMs. A new SIM Order Form will be sent to MVNOs to be able to make their selection.  
  
**How are eSIMs delivered?**  
Upon order fulfilment, the Transatel Fulfillment team will send an output file (similar to a physical SIM order) which contains the activation codes.  
   
The MVNO can choose two options:  
Use the activations codes from the output file to distribute to their subscribers: i.e. the text that can be inserted into the eSIM setup menu, or convert these activation codes into QR codes to be scanned by subscribers.  
Use Transatel’s SIM Management APIs to retrieve activation codes or URLs. Several options are available, please visit <https://developers.transatel.com/docs/sim-management-overview/> to learn more.  
   
The MVNO can decide how to provide these eSIM profiles to subscribers, such as including the QR code in an email, or printing QR codes onto vouchers or letters.  
  
**How are eSIMs activated?**  
The MVNO can activate the eSIM via Auriga or API, and provision the relevant services as per the process of a physical SIM card.  
  
**Do eSIMs need to be activated to download them?**  
No, but an activated eSIM leads to a better customer journey. Indeed, an activated eSIMs will work straight away.  
However, if you decided to activate the eSIM after download, the eSIM will remain under status “activating”. In this case, the subscriber simply needs to restart the handset once the SIM has been activated via Auriga/API.  
   
**What if my subscriber can’t scan the QR code?**  
If the subscriber doesn’t have a second screen to display the QR code, or if they are having difficulties displaying the QR code, the MVNO can simply provide them with the activation code which the subscriber can copy and paste into the eSIM setup journey. Most service providers distribute the activation code alongside the QR code.  
  
**Does the QR code expire?**  
The QR code will not expire unless it has been downloaded already.  
  
   
**What happens if a customer deletes an eSIM profile from their device? Can it be re-downloaded?**  
Transatel eSIMs can only be downloaded once. If an eSIM profile is deleted from a device, the subscriber must be provided with a new eSIM profile and the MVNO must perform a SIM swap for subscriber to continue their current subscription and the same MSISDN.  
   
**What happens if a subscriber loses their eSIM device?**  
The subscriber must download a new eSIM profile on their new device and a SIM swap must be performed.  
  
**Can I see if a customer has downloaded the eSIM?**  
For the initial rollout of eSIMs, there is not the ability to retrieve SMDP+ statuses (eg. whether the eSIM has been downloaded). However, the status of the subscriber (active, suspended, terminated…) is available on Auriga as it is for physical SIMs.  
  
**Do SIM swaps work between physical SIM and eSIM?**  
Yes. Physical SIMs can be swapped onto eSIMs and vice versa! To do this, the subscriber must be provided with a swap SIM or a swap eSIM (a SIM without an MSISDN attached) and MVNOs can perform SIM swaps via Auriga or API.  
If you are using the Apple Transfer to eSIM during iPhone setup, this is therefore not supported. The subscriber must complete iPhone setup first, perform the SIM Swap and install the new eSIM after setup.  
  
**How many eSIMs can be enabled on a device at a time?**  
Most devices allow you to download and store several eSIM profiles. However, at the moment, most devices only allow one to be enabled at a given time. This is likely to change with the arrival of eSIM-only devices.  
Therefore, in most cases, if you want to split out your data from your voice & SMS SIM, you will need to use a physical SIM alongside an eSIM.  
  
**Can an eSIM be used on more than one device?**  
No, the eSIM can only be active in one device at a time. Each device must have their own unique eSIM profile.  
  
**Can I transfer my eSIM from one device to another?**  
Currently, eSIMs can only be downloaded once. Therefore, if you want to transfer your eSIM onto a new device this must be done using a SIM Swap.  
If the subscriber is using the eSIM Transfer option during iPhone setup, this is therefore not supported. The subscriber must complete setup first, perform the SIM Swap and install the new eSIM after setup.  
  
**Will eSIMs be identified / appear differently in existing Transatel systems?**  
Yes! MVNOs will be able to filter by SIM type in Auriga using the filters on the right-hand side of the Auriga screen.  
![image](/knowledge-center/assets/image-1.png)
  
**Is there any change to lead times for ordering eSIMs?**  
Delivery lead times remain the same for physical and eSIM, however expect eSIMs to be delivered faster as we don’t have to rely on shipping carriers!  
  
**Can eSIM profiles be used in devices other than mobile phones? e.g. Smartwatches, Laptops, Tablets?**  
Yes, wherever the eSIM is GSMA compliant (all mainstream brands and devices), Transatel eSIM profiles can be downloaded onto that eSIM!  
  
**Why does the eSIM “My Number” field in the device show 00000000000? The SPN is not showing?**  
This should display the subscriber’s MSISDN. Sometimes devices need a nudge to read the right settings. Usually, the fields will update by either:  
– disabling and re-enabling the eSIM  
– Setting “aeroplane mode” on and off again  
– restarting the device  
If this does not work, the Service Provider may need to perform a “[refresh](../../devices-set-up-troubleshooting/diagnostic-tools/resynchronise-the-services.md)” on the line to send the OTA configuration to the device, in case it was not received the first time.  
   
Note, some brands require eSIMs to be downloaded onto the secondary device via a smartphone application. In which case, the manufacturer would need to integrate the MVNO’s eSIM profiles into their app to do so (eg. Apple Watch). If the app allows you to paste an activation code, there will be no problem downloading the eSIM into the device.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
