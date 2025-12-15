[HIRI-312]
Author: Dipl. Ing. Marvie Demit
---

# AI Risk Register

**Source:** Activity_3_1


*(A spreadsheet to be maintained for each High-Risk AI system)*

| Risk ID | Description | Category | Likelihood (1-5) | Impact (1-5) | Risk Score (L*I) | Risk Treatment Plan | Owner | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **HR001-01** | Model exhibits discriminatory bias against a protected group in recruitment screening. | Fundamental Rights | 3 (Possible) | 5 (Critical) | **15** | Implement additional fairness testing with synthetic data; add human-in-the-loop review for all rejected candidates. | J. Doe | **In Progress** |
| **HR001-02** | System is vulnerable to a data poisoning attack, compromising its integrity. | Safety / Security | 2 (Unlikely) | 4 (Major) | **8** | Conduct penetration testing; implement input validation and anomaly detection on training data pipeline. | K. Smith | **Open** |
| **HR001-03** | System output is misinterpreted by users, leading to incorrect decisions. | Safety / Health | 3 (Possible) | 3 (Moderate) | **9** | Improve user interface with clearer explanations of output confidence scores; update user training materials. | J. Doe | **Open** |

**Risk Scoring Matrix:**
*   **Likelihood/Impact Scale:** 1 (Rare/Negligible) to 5 (Almost Certain/Critical)
*   **Risk Score:** 1-5 (Low), 6-12 (Medium), 13-25 (High)