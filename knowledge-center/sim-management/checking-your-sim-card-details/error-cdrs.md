---
title: "Error CDRs"
---

**Error CDRs**

Error CDRs will help you diagnose Subscriber issues, as well as check if the Subscriber’s reported issue comes from the device reaching the network, and if so, why they were unable to use connectivity.

**Viewing Error CDRs**

As the most common use of CDRs is to verify usage, error CDRs will not automatically display on the usage tables – by default they will be filtered out. You can choose to include them into the usage tables in one of two ways:  
Either you can remove the filters from the top of the screen, which will then automatically include all filtered items:  
![image](/knowledge-center/assets/image-1.png)
Or you can select to include them from the filter panel under “Status”.  
   
![image](/knowledge-center/assets/image-2.gif)

**New CDR Attributes**

As well as the error CDRs, there are new CDR attributes will appear in several new columns:  
– Request Type (Data only)  
– Status  
– Service outcome  
– Termination cause (Data only)  
– Result code

****Displaying the new CDR attributes****

If you can’t see these columns, you will need to add them via clicking on the (+) *Manage Columns* button at the top-right hand side of the usage table:  
![image](/knowledge-center/assets/image-3.gif)
   
Here is a description of the new attributes:    
  
**Request Type (Data only)**  
Description: The type of the request.  
Example values:  
*Initial*: the first request (i.e. to open a data session)  
*Update*: intermediate request to check if the data session can continue (i.e. grant further data service units)  
*Terminate*: request to end the data session  
   
**Status**  
Description: Resulting status for the service. For more details about the error please see Service outcome field.   
Example values:  
*OK*: the communication is granted  
*NET\_TERM*: terminated by the network  
*NET\_ERR*: error on the network  
*ERROR*: communication not granted for other reasons, such as user not registered  
*REJECT*: request rejected as it was not authorised, i.e. requested usage in a blacklisted country, or usage not allowed in the zone  
   
**Service outcome**  
Description: Resulting status for the service.  
Example values:  
*OK*: the communication is granted  
*NET\_TERM\_GY\_USER\_DISCONNECT*: the communication is not granted  
   
**Termination cause** (Only data CDRs)  
Description: MVNOs can now see why a data session ended using the termination cause field. The Termination-Cause AVP is used to indicate the reason why a session was terminated on the access device. This information is only present for “Terminate” requests. In case where the data session is granted or ongoing (i.e. no “Terminate”), the value displayed is -1.  
*Example values*: -1, 1 (roll your mouse over the (?) to show the details):  
![image](/knowledge-center/assets/image-4.png)
  
**Result code**  
Description: SCP logic linked to error codes management. The generic result code in the case of the multi-rating group. Any response provided by SCP data with global result code in the ranges 3xxx, 5xxx will break the session. SCP will then receive a Gy terminate for this session. When the result code is 2001, it means success/no errors occurred.  
Example values:  
*2001*: The Request was successfully complete  
*5003*: A request was received for which the user could not be authorized. This error could occur if the service requested is not permitted to the user.  
*5012*: This error is returned when a request is rejected for unspecified reasons  
*5030*: The specified end user is unknown in the credit-control server.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
