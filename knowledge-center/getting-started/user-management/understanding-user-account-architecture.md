---
title: "Understanding user account architecture"
---

**Understanding user account architecture**

User accounts in our interface are based on 3 foundations:  
– which **customer account** they can access  
– which **scopes** the user has  
– which **rights** the user has  
  
Let’s see how this works  
– A **Customer Account** is a fleet of SIM – most of our customers only have one, but some, requiring services on very different technical frameworks, have multiple accounts.   
  
– A **Scope** – the user at least needs ROLE\_USER for the account to work  
  
– Finally, a **Right** is the access to a minor feature or action. For example Activating a SIM card.  
There are many rights, as we let you decide exactly what each user should or should not be able to do.  
This is why critical actions such as terminating a SIM card (an action that cannot be reversed) is a separate from other rights, so that only the right people in your organization have this power.  
For further details on user rights, [click here](https://docs.transatel.com/user-management/user-rights/).  
  
To sum thing up, to be able to perform an action on a SIM, the user account must have:  
– access to the customer account of the SIM  
– at least one scope  
– the right to which the action corresponds  
  
Let’s take the example of activating SIM cards in bulk.  
The user who wants to perform an activation in bulk will require a user account with:  
– access to the customer accounts the SIMs belong to  
– the USER scope  
– the specific right to manage SIMs in bulk

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
