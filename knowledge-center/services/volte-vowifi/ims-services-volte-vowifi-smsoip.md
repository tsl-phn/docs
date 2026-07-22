---
title: "IMS services (VoLTE/VoWiFi/SMSoIP)"
---

## **What is IMS?**

IMS stands for IP Multimedia Subsystem. It is a component of the core network which permits the latest voice calling technology. In essence, it allows voice calls to be carried using data (packet-switched, over 4G or 5G networks), which means that coverage can be extended and call quality can be greatly improved compared to traditional voice calls (CS or Circuit-Switched).

## **What does IMS do?**

IMS allows users to access the latest voice and SMS services, including:

- **VoLTE** (Voice over LTE)): the ability to make calls using the 4G (or LTE) network
- V**oWiFi** (Voice over WiFi): the ability to make calls using your home, office or public Wi-Fi, which is especially useful if there is no coverage for cellular data
- **SMSoIP** (SMS over IP)**:** the ability to send an SMS over the internet (i.e. 4G/LTE or WiFi network)

## What are the advantages of IMS?

These services carry benefits such as:

- Being able to talk and surf on 4G at the same time
- Not requiring to fall back to the 2G network to take a call (requiring the device to reattach to 4G once the call is finished)
- Faster call connection
- Improved call quality
- Extended coverage from the 4G network
- Access to the 800MhZ spectrum which is reserved for VoLTE usageAdd image

## **What do I need to access VoIMS services?**

To enable VoIMS for a user, the requirements are:

- The “VoIMS service (VoLTE & VoWiFi)” is provisioned to ”on” via Auriga or API
- The user must have an IMS, VoLTE or VoWiFi compatible handset
- Handset settings must have IMS, 4G (or LTE) calling and Wi-Fi calling set to “on” (the naming and options may vary according to the handset and manufacturer)
- Handset settings must have 4G data set to on
- The 2G/3G/4G or 2G/3G/4G/5G service is provisioned to ”on” via Auriga or API
- The user must be in within 4G coverage, or in a Wi-Fi zone and connected to the Wi-Fi network

Enable Wi-Fi calling on an Apple device: <https://support.apple.com/en-gb/HT203032>

For android or other devices, check your manual.

## **What happens if I can’t get 4G signal?**

When 4G is not available, your device will automatically pass calls through the 2G or 3G networks if you are within coverage. This is called CS Fallback (or Circuit-Switched Fallback)  
  
Be aware that the benefits of VoLTE will be lost in this case (surf and talk, voice quality…).

## Do IMS services work in roaming?

VoLTE and SMSoIP is supported in a limited number of countries, but the list is growing as new partnerships are deployed!  
  
VoWiFi is not supported in roaming.  
  
Find out more about IMS in Roaming by clicking [here](roaming-ims-services.md).

## What about 5G?

When you are making a call, your phone will automatically switch to a 4G network.  
This means you will not be able to use 5G whilst on a call, but you’ll nonetheless benefit from the speeds of 4G .  
  
Surfing on 5G whilst on a call will become possible with the launch of VoNR (Voice over New Radio / also referred to as Voice over 5G or Vo5G). VoNR is likely to become standardised in the market some time after the standardisation of 5G SA (stand alone).

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
