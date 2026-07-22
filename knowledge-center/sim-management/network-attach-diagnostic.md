---
title: "Network attach diagnostic"
---

## About Network attach

Even if there’s no ongoing data traffic, our interface gives your visibility on the last known network your SIM has attached to.   
  
Cellular-enabled devices are “attached” to a radio antenna and periodically renew the attach to stay connected. This signaling events are “location updates”.  
The last notification received in our system is what we display as the “last attach”.  
  
An update is usually triggered:

- When the device is switched on (but not always in reboots though)
- When the device moves to a new area (and connects to a new cell)
- When the device connects to another bearer type (ex: from LTE to 3G)
- At regular intervals to keep the connection active, as each operator requires devices to do so to stay connected (the duration of these intervals varies from operator to operator)

In addition, we offer you the possibility to force the SIM to detach from the network

**Note:** this tool is not available for customers on MVNO France Light and MVNO UK frameworks

## **How to use this feature?**

In our interface, go to the page of the SIM card you wish to check.  
You’ll find all the details in the Activity section of the check-up panel, on the right side.

- The **last attach’s timestamp**
- The**IMSI**
- The **visited country**
- The visited **operator network – for 4G/LTE connections only**

![image](/knowledge-center/assets/image-1.png)

If the SIM has not attached to the network in the past 3 months, we will display the following:

![image](/knowledge-center/assets/image-2.png)

## Network Attach History

You can check the history of the past 3 months of network attaches by clicking on the history button

![image](/knowledge-center/assets/image-3.png)
![image](/knowledge-center/assets/image-4.png)

the fields available are the following:

|  |  |
| --- | --- |
| **Field name** | **Description** |
| **Timestamp** | Last attach / Last location update notified to Transatel HSS |
| **IMEI** | International Mobile Equipment Identity. Unique identifier of the device embedding the SIM card  when available (only 4G / 5G) |
| **IMSI** | Always primary IMSI |
| **MSISDN** | **M**obile **S**tation **I**nternational **S**ubscriber **D**irectory **N**umber (MSISDN) is a unique identifier of a subscriber in a mobile network. Simply put, it is the telephone number to the SIM card in a device. |
| **RAT** | Radio Access Technology. Can be either “2G/3G” or “4G/5G”. |
| **HSS** | Home Subscriber Server instance which holds the connectivity service subscription. |
| **Operator Name** | PLMN name (HSS resolution) |
| **MCC** | Mobile Country code of the visited country as defined by ITU-T. |
| **Country \*** | Visited country |
| **PLMN Name \*** | PLMN name (HSS resolution) |

\* in the case of IMSI roaming sponsor some information may not be available. The PLMN Name and country shown is the following : Orange France

## **How to use the network detach tool**

Forcing the SIM to reconnect to the cellular network is a simple and effective way to solve connectivity issues as it reboots the SIM on the network.  
If the SIM encountered connectivity issues, after being detached from the network, the SIM can reattach:  
·     Correctly on the network, which solves many roaming connectivity issues  
·     To a stronger signal (new operator, new antenna)  
·     To 4G instead of 3G, or 3G instead of 2G  
And use new connectivity settings if you made a change of configuration (for example, change of footprint).

To launch a request, just click on the “detach button”

![image](/knowledge-center/assets/image-5.png)

You will see confirmation if the request was successfully transmitted to our HSS at the bottom of the screen  
![image](/knowledge-center/assets/image-6.png)
  
A “cancel location” request has been sent to the network, which will then require the equipment to update its location – in simple terms, it will have to reconnect to the network.  
After a minute, you can try to refresh the last attach – if the device has successfully updated its attach to the network, the new attach info will be displayed.

## **A few limits to keep in mind:**

- The feature **does not let you know if the device is connected at this very instant**– just when it re-attached last. It means you can know if there was recent activity.
- The device may have detached since the last attach – for example the device could have been turned off, or left to a no-coverage zone, thus without the network knowing
- We keep records over the past 3 months (starting from the launch of the service) – if a SIM has not attached in the past 3 months, we’ll display that the has no recent attach

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
