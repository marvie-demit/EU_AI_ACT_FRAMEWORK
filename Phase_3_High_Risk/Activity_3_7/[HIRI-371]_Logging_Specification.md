[HIRI-371]
Author: Dipl. Ing. Marvie Demit
---

# Logging Specification

**Source:** Activity_3_7


*(A document to be completed for each High-Risk AI system)*

| | |
| :--- | :--- |
| **System Name / ID:** | [e.g., Credit Scoring Model / AI-007] |
| **Technical Lead:** | [Name] |
| **Version:** | 1.0 |

| **1. Events to be Logged** | |
| :--- | :--- |
| **Events:** | - Start and end of each use of the system.<br>- The reference to the input data the system has been trained on.<br>- The input data for which the system has produced an output.<br>- The output of the system for each use.<br>- Any human oversight interventions (e.g., an override). |

| **2. Log Data Schema** | |
| :--- | :--- |
| **Schema:** | See the "Sample Log Output" template for the detailed JSON schema, including fields like `timestamp`, `event_id`, `user_id`, `system_id`, `event_type`, `input_hash`, `output_value`, etc. |

| **3. Log Storage & Retention** | |
| :--- | :--- |
| **Storage Solution:** | [e.g., "AWS S3 with Object Lock (Immutability)"] |
| **Retention Period:** | [e.g., "10 years from the date of the event, in line with product liability regulations."] |

| **4. Access Control** | |
| :--- | :--- |
| **Access Policy:** | [e.g., "Read-only access is restricted to the AI Governance Body and designated members of the incident response team via IAM roles. Write/delete access is prohibited for all users."] |

**Approved by (AI Governance Body):** [Name, Date]