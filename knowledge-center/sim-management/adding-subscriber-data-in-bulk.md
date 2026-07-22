---
title: "Adding Subscriber Data in Bulk"
---

# Adding Subscriber Data in Bulk

## SIM Management​

## [Checking your SIM card details](checking-your-sim-card-details/README.md)

- [Adding Subscriber Data in Bulk](adding-subscriber-data-in-bulk.md)
- [Using Metadata (custom fields)](metadata-custom-fields.md)
- [eSIM Quickstart Guide](checking-your-sim-card-details/esim-quickstart-guide.md)
- [eSIM FAQs](checking-your-sim-card-details/esim-faqs.md)
- [What are the different types of SIM? (Sales/Swap)](checking-your-sim-card-details/what-are-the-different-types-of-sim-sales-swap.md)
- [Everything you need to know about SIM cards](all-you-want-to-know-about-the-sim-cards.md)
- [SIM page & checkup panel overview](sim-page-overview.md)
- [Adding or editing SIM and subscriber information](how-to-group-tag-and-label-your-sims.md)
- [SIM's history and logs](checking-a-sims-history-and-logs.md)
- [Checking a SIM's data usage](sim-usage-history.md)
- [Finding an eSIM's status and retrieving the activation code](how-to-find-an-esims-status-and-retrieve-the-activation-code.md)
- [Error CDRs](checking-your-sim-card-details/error-cdrs.md)

## [Activate or change SIM status](activate-or-change-sim-status/README.md)

- [Activating a single SIM card](activating-a-single-sim-card-2.md)
- [SIM Swap](activate-or-change-sim-status/sim-swap.md)
- [MSISDN Swap](msisdn-swap.md)
- [SIM Lifecycle](activate-or-change-sim-status/sim-lifecycle.md)
- [Activating a single SIM card](../uncategorized/activating-a-single-sim-card.md)
- [Activating a single IoT SIM card](activate-or-change-sim-status/how-to-activate-a-single-iot-sim-card.md)
- [Activating SIM cards in bulk](activate-or-change-sim-status/how-to-activate-sim-cards-in-bulk.md)
- [Performing actions in bulk](how-to-perform-actions-in-bulk.md)

## [Managing Groups](managing-groups/README.md)

- [Creating groups of SIMs](creating-groups-of-sims.md)
- [Editing, managing or deleting SIM groups](managing-groups/how-to-edit-manage-or-delete-sim-groups.md)
- [Adding multiple SIMs to a group](how-to-add-multiple-sims-to-a-group.md)
- [Removing SIMs from a group](managing-groups/how-to-remove-a-sim-from-a-group.md)
- [Adding a SIM to a group](managing-groups/how-to-add-a-sim-to-a-group.md)

## [Real-time diagnostics](https://docs.transatel.com/sim-management/real-time-diagnostics/)

- [Data session diagnostic tool](../devices-set-up-troubleshooting/diagnostic-tools/data-session-diagnostic-tool.md)
- [Network attach diagnostic](network-attach-diagnostic.md)

## [Mobile Number Portability](mobile-number-portability/README.md)

- [Sw-API: providing custom switching information](mobile-number-portability/sw-api-providing-custom-switching-information.md)
- [Switching Information](mobile-number-portability/switching-information.md)
- [Managing Mobile Number Portability in Belgium](mobile-number-portability/managing-mobile-number-portability-in-belgium.md)
- [Number Portability: everything you need to know](mobile-number-portability/number-portability.md)
- [Managing Mobile Number Portability in France](mobile-number-portability/managing-mobile-number-portability-in-france.md)
- [Managing Mobile Number Portability in the UK](mobile-number-portability/managing-mobile-number-portability-in-the-uk.md)
- [How do I enter switching information in Auriga?](mobile-number-portability/mvna-uk-how-do-i-enter-switching-information-in-auriga.md)
- [[MVNA UK] What is Switching Information?](mobile-number-portability/mvna-uk-switching-information.md)

## On this page

# Adding Subscriber Data in Bulk

This article explains how to add subscriber data to multiple SIMs simultaneously using the CSV import functionality in Auriga.

Maintaining subscriber data in Auriga provides several operational and regulatory benefits. Subscriber information can be used to quickly identify the user associated with a SIM, making customer support, troubleshooting, and fleet management more efficient. It also allows Auriga to serve as a CRM and subscriber management platform, helping operators maintain a centralized and up-to-date view of their subscriber base. Additional benefits include improved reporting, easier SIM ownership tracking, faster incident resolution, simplified customer management processes, and support for regulatory and legal disclosure requirements where applicable.

## 1. GDPR and Regulatory Requirements

When uploading subscriber data into Transatel platforms, the MVNO must ensure that the appropriate contractual data protection appendix has been signed.

By uploading subscriber data, the MVNO acknowledges that:

- The MVNO remains the **Data Controller** of the subscriber information.
- Transatel acts solely as the **Data Processor** on behalf of the MVNO.

For **MVNA Light**, **MVNE UK**, and **MVNE Belgium** businesses, providing accurate and up-to-date subscriber information is mandatory if the Disclosure Form declares that the legal disclosure service is delegated to the MNO. In this case, subscriber data must be maintained and kept up to date at all times.

## 2. Adding Subscriber Data in Bulk

Subscriber data can be added in bulk by importing a CSV file into Auriga from the dedicated menu. To do so, follow these steps:

1. Log in to **Auriga**.
2. Navigate to **All Assets** and click **Import CSV**.

![image](/knowledge-center/assets/image-1.png)

1. Select **Import Subscriber Data** and click **Next**.

![image](/knowledge-center/assets/image-2.png)
![image](/knowledge-center/assets/image-3.png)

1. Upload your CSV file on the following screen, either by drag & drop or by selecting the file from your device.

![image](/knowledge-center/assets/image-4.png)

1. Review the **Import Validation** results.
2. Click **OK** to confirm the import.

## 3. Creating Your CSV

Please upload a file containing your subscribers and their associated subscriber data. Feel free to use our template file, which can be downloaded from the **Import CSV** page in Auriga.

![image](/knowledge-center/assets/image-5.png)

The file must comply with the following criteria:

- It must be in **.csv** format.
- The first column must contain the subscriber number (MSISDN).
- The following columns may contain subscriber information as described below.
- Imports are limited to **500 rows per file**.

### Subscriber Data Fields

| Field | Description |
| --- | --- |
| `gender` | Subscriber title. Allowed values: `Mr`, `Ms`, `Mrs` (**Required**) |
| `firstName` | Subscriber first name |
| `lastName` | Subscriber last name |
| `birthDate` | Subscriber date of birth |
| `company` | Company name |
| `country` | Subscriber nationality (ISO 3166-1 alpha-2 country code, e.g. `FR`, `GB`, `BE`) (**Required**) |
| `email` | Email address |
| `language` | Preferred language. Allowed values: `IT`, `FR`, `EN`, `JA`, `PT`, `NL`, `DE`, `ZH` |
| `address` | Street address |
| `zipCode` | Postal code |
| `city` | City |
| `postalBox` | Postal box |
| `external_ref` | External customer reference |
| `country_residence` | Country of residence (ISO 3166-1 alpha-2 country code, e.g. `FR`, `GB`, `BE`) (**Required**) |

> **Note:** Required fields must be populated for every subscriber. Any unsupported values or incorrectly formatted data will be flagged during the validation process.

### Example

subscriber;gender;firstName;lastName;birthDate;company;country;email;language;address;zipCode;city;postalBox;external\_ref;country\_residence

01261178.00000068;Mr;John;Doe;23/03/2020;Transatel;FR;john.doe@transatel.com;EN;1 rue de Rivoli;75001;Paris;BP75;my ext ref;FR

## See Also

**Adding or editing SIM and subscriber information for a single SIM card**: https://docs.transatel.com/sim-management/how-to-group-tag-and-label-your-sims/

Can't find your answer?

[Ask our support](https://support.transatel.com/secure/Dashboard.jspa)

## On this page
