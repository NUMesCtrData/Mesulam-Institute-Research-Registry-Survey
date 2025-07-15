# Mesulam Center Registry Survey REDCap Instrument

This repository includes the REDCap instrument for the **Mesulam Center Registry Survey**, used to collect standardized intake data for individuals participating in Alzheimer’s disease and related research at the Mesulam Center for Cognitive Neurology and Alzheimer’s Disease.

---

## 📄 Instrument Overview

- **Instrument Name**: `mesulam_center_registry_survey`
- **Version**: July 2025
- **Purpose**: Participant intake and registry tracking for recruitment into current and future studies

---

## 📋 Sample Fields

Here is a preview of selected fields from this instrument:

| Field Variable     | Field Label                        | Field Type |
|--------------------|------------------------------------|------------|
| `record_id`        | Study ID                           | text       |
| `first_name`       | First Name                         | text       |
| `last_name`        | Last Name                          | text       |
| `dob`              | Date of Birth                      | text       |
| `consent_status`   | Consent Status                     | radio      |
| `contact_attempts` | Number of Contact Attempts         | integer    |
| `language`         | Preferred Language                 | dropdown   |
| `proxy_flag`       | Does this participant have a proxy?| yesno      |

(*Actual fields should be drawn from the uploaded CSV*)

---

## 🛠️ Setup Instructions

1. Download `MesulamCenterRegistrySurvey_DataDictionary_2025-07-15.csv` from this repository
2. Log into your REDCap project
3. Navigate to **Project Setup > Online Designer > Upload Instrument**
4. Upload the CSV to create the data collection form
5. Customize any field logic or study-specific settings as needed

---

## 🔍 Notes

- The instrument includes logic for eligibility, contact management, and self/proxy data entry.
- Branching logic is already configured in the CSV.
- Enable the REDCap **Survey feature** if participants will be self-registering.

---

## 🧾 License

This instrument is proprietary to the Mesulam Center at Northwestern University. Redistribution or reuse without permission is prohibited.

**Maintainer**: [Debby Zemlock](mailto:your.email@northwestern.edu)
