---
title: "Default Services"
---

# Default Services

## Uncategorized

## [Uncategorized](../../uncategorized/README.md)

- [Adding Capped Bundles in Bulk](../../uncategorized/adding-capped-bundles-in-bulk.md)

- [All about Static IP](../../uncategorized/all-about-public-static-ip.md)
- [Default Services](default-services.md)
- [Activating a single SIM card](../../uncategorized/activating-a-single-sim-card.md)
- [Portability information report](../../uncategorized/portability-information-report.md)
- [Network Coverage Selection - Advanced](../../uncategorized/iot-network-coverage-selection-advanced.md)
- [Network Coverage Selection](iot-network-coverage-selection.md)

## On this page

# Default Services

**Default Services**

**What is a default service?**

There are many services available to subscribers, such as barring (i.e. bar roaming), technologies (i.e. 4G or 5G) used or wholesale options (i.e. pay-per-use or a wholesale bundle). Unless otherwise specified, a default service will be enabled for a user upon activating their SIM card. For example:  
·        Auriga: when activating a SIM, a certain number of services will be pre-selected on the activation screen.  
·        API: for every service not specified in the API call for the SIM activation, the default value will be applied

**What services are enabled by default for my MVNO?**

The default services are defined in your IT Catalogue. These may be specific per MVNO, or generic. To find out which specific services are enabled by default, rendezvous in Auriga!  
1.      Go to Catalogue -> Options  
![image](/knowledge-center/assets/image-1.png)
2.      If you have several offers, select the rateplan for which you want to see your services. If you only have one offer, skip this step  
![image](/knowledge-center/assets/image-2.png)
3.      In the table of services, check the column “Default Value”  
![image](/knowledge-center/assets/image-3.png)
The default value can be:  
–        Enabled (on) / disabled (off)  
–        A specific value where a multiple choice of values is presented (i.e. 3G or 3G/4G or 3G/4G/5G)

**What if I don’t want the default value?**

The default value is overridden if the service is specified in the activation request.  
–        Auriga custom activation: the default services will be preselected. However, you can click on each service and choose the value required. These will be taken into account upon the activation request  
–        Auriga Service Profile: by creating and applying a service profile, you choose your own default services. More about Service Profiles [here](https://docs.transatel.com/services-setup/service-profiles/).  
–        API: as long as the service is specified in the activation request, the value requested will be the one implemented upon activation of the line.

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)
