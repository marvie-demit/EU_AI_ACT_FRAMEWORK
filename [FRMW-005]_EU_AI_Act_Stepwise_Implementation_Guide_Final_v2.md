[FRMW-005]
Author: Dipl. Ing. Marvie Demit
---

# A Consolidated Stepwise Implementation Guide for EU AI Act Compliance (Final Version)

**Author:** Manus AI
**Date:** November 20, 2025

## 1. Introduction

The European Union's Artificial Intelligence (AI) Act is a landmark regulatory framework establishing a global benchmark for AI governance. This guide presents a consolidated, structured, and stepwise implementation model for achieving compliance. Inspired by the phased approach of the World Health Organization's Laboratory Quality Stepwise Implementation (LQSI) framework [1], this guide provides a clear and actionable roadmap for organizations.

By adopting a risk-based methodology, this guide breaks down the compliance journey into two parallel tracks:

1.  **A three-phase track based on the specific risk level** of the final AI application (Minimal, Limited, and High Risk), with expanded, granular activities for all phases.
2.  **A parallel track for providers of General Purpose AI (GPAI) models**, which have their own distinct set of obligations.

This dual-track approach ensures that organizations can address both specific use-case risks and foundational model risks simultaneously and methodically. Unacceptable risk AI systems, which are prohibited under the Act, are not covered in this implementation guide.

## 2. The EU AI Act's Risk-Based Structure

The EU AI Act classifies AI systems into distinct categories based on their potential risk to health, safety, and fundamental rights. This classification determines the level of regulatory scrutiny and the specific obligations that apply [2, 3].

| Risk Category | Regulatory Approach | Key Obligations |
| :--- | :--- | :--- |
| **Unacceptable Risk** | **Prohibited** | Banned from the EU market. Includes systems for social scoring, exploitation of vulnerabilities, and most real-time remote biometric identification in public spaces. |
| **High Risk** | **Strictly Regulated** | Subject to extensive requirements, including risk management, data governance, human oversight, and conformity assessments before market entry. |
| **General Purpose AI (GPAI)** | **Model-Level Regulation** | Providers of GPAI models have specific obligations regarding technical documentation, transparency, and cooperation with downstream providers. |
| **Limited Risk** | **Transparency Obligations** | Must adhere to specific transparency requirements, such as informing users they are interacting with an AI system (e.g., chatbots, deepfakes). |
| **Minimal Risk** | **Largely Unregulated** | The vast majority of AI systems fall into this category (e.g., spam filters, AI in video games). No mandatory obligations, but voluntary codes of conduct are encouraged. |

## 3. The Consolidated Dual-Track Compliance Framework

This framework integrates the risk-based phases and the parallel GPAI track into a single, comprehensive roadmap. Organizations should address both tracks concurrently based on their role as either an AI system deployer, a GPAI provider, or both.

### The 10 Compliance Essentials

These 10 "Compliance Essentials," derived from the EU AI Act, guide the activities within both tracks:

1.  **Risk Management System** (Article 9)
2.  **Data Governance** (Article 10)
3.  **Technical Documentation** (Article 11 & 53)
4.  **Record-Keeping / Logging** (Article 12)
5.  **Transparency & User Information** (Article 13 & 53)
6.  **Human Oversight** (Article 14)
7.  **Accuracy, Robustness & Cybersecurity** (Article 15)
8.  **Quality Management System** (Article 17)
9.  **Conformity Assessment** (Article 43)
10. **Post-Market Monitoring** (Article 61)


### Track A: Risk-Based Implementation Phases (For AI System Deployers)

#### Phase 1: Foundational Governance & Minimal Risk Compliance

**Focus:** To establish a corporate AI governance structure, create a complete inventory of all AI systems, classify them by risk, and address the recommended best practices for Minimal Risk systems. This phase is the essential starting point for any organization.

| Activity ID | Activity Description | Compliance Essential(s) Addressed |
| :--- | :--- | :--- |
| **1.1** | **Establish AI Governance Body:** Form a cross-functional team or committee responsible for overseeing AI compliance, risk management, and ethical guidelines. | Quality Management System |
| **1.2** | **Develop AI Inventory Procedure:** Create a standardized procedure for identifying and documenting all AI systems used or developed within the organization. | Technical Documentation |
| **1.3** | **Conduct Initial AI System Inventory:** Execute the procedure to create a comprehensive register of all AI systems, recording each one's purpose, owner, data sources, and vendor. | Risk Management System, Technical Documentation |
| **1.4** | **Develop Risk Classification Procedure:** Create a formal procedure based on the EU AI Act's criteria (Annexes II and III) to classify AI systems as Minimal, Limited, High, or Unacceptable. | Risk Management System |
| **1.5** | **Classify All Inventoried Systems:** Apply the procedure to every AI system in the inventory and thoroughly document the justification for each classification. | Risk Management System |
| **1.6** | **Draft and Adopt Voluntary Code of Conduct:** For all systems classified as **Minimal Risk**, draft, adopt, and publish a voluntary code of conduct for ethical AI use to demonstrate a commitment to trustworthy principles. | N/A (Best Practice) |

#### Phase 2: Limited Risk Compliance

**Focus:** To implement the mandatory transparency obligations for all AI systems classified as Limited Risk with granular, auditable steps.

| Activity ID | Activity Description | Compliance Essential(s) Addressed |
| :--- | :--- | :--- |
| **2.1** | **Identify User-Facing Limited-Risk Systems:** From the AI inventory, create a sub-list of all systems where users directly interact with AI (e.g., chatbots, customer service bots). | Transparency & User Information |
| **2.2** | **Implement User Notification Mechanisms:** For systems identified in 2.1, design and deploy clear, unambiguous notifications (e.g., banners, pop-ups, initial messages) to inform users they are interacting with an AI. | Transparency & User Information |
| **2.3** | **Identify AI Content Generation Systems:** Create a sub-list of all systems that generate or manipulate image, audio, or video content (i.e., "deepfakes"). | Transparency & User Information |
| **2.4** | **Implement Content Labeling/Watermarking:** For systems identified in 2.3, implement a reliable mechanism to ensure the output is clearly and persistently labeled or watermarked as artificially generated. | Transparency & User Information |
| **2.5** | **Identify Biometric/Emotion Recognition Systems:** Create a sub-list of all systems that perform biometric categorization or emotion recognition. | Transparency & User Information |
| **2.6** | **Implement Explicit Information & Consent:** For systems identified in 2.5, deploy mechanisms to explicitly inform individuals of the system's operation and, where required, obtain consent before use. | Transparency & User Information |
| **2.7** | **Maintain Records of Transparency Measures:** Create and maintain an auditable log of all transparency measures implemented for each Limited Risk system, including dates and versioning. | Record-Keeping / Logging |

#### Phase 3: High-Risk AI Compliance

**Focus:** To implement the full, comprehensive set of legal and technical requirements for all systems classified as High-Risk. This is the most intensive phase of the compliance journey and involves a deep engagement with all 10 Compliance Essentials. The activities in this phase are extensive and should be managed as a formal project.

| Activity ID | Activity Description | Compliance Essential(s) Addressed |
| :--- | :--- | :--- |
| **3.1** | **Establish Formal Risk Management System:** Implement and document a continuous risk management system for each high-risk AI system, as required by Article 9. This includes procedures for risk identification, analysis, evaluation, and mitigation. | Risk Management System |
| **3.2** | **Implement Robust Data Governance Framework:** Enforce strict data governance practices for the data used to train, validate, and test high-risk AI systems, as per Article 10. This includes assessing data for bias, ensuring relevance, and documenting data lineage. | Data Governance |
| **3.3** | **Create and Maintain Detailed Technical Documentation:** Develop and keep up-to-date the comprehensive technical documentation required by Annex IV of the Act, detailing the system's architecture, performance, and intended purpose. | Technical Documentation |
| **3.4** | **Establish Formal Quality Management System (QMS):** Implement a QMS as per Article 17 to ensure and demonstrate compliance. This includes defining a quality policy, setting objectives, and documenting all procedures. | Quality Management System |
| **3.5** | **Implement Human Oversight Mechanisms:** Design and deploy appropriate human oversight measures to allow for monitoring and intervention, as required by Article 14. This includes implementing "stop" buttons and training overseers. | Human Oversight |
| **3.6** | **Ensure Technical Accuracy, Robustness, and Cybersecurity:** Validate that the system performs accurately and is resilient against errors, faults, and malicious attacks, as per Article 15. This includes conducting rigorous testing and implementing security controls. | Accuracy, Robustness & Cybersecurity |
| **3.7** | **Enable Automatic Event Logging:** Ensure the system automatically records events (logs) during its operation to provide traceability of the system's functioning, as per Article 12. The logs must be secure and immutable. | Record-Keeping / Logging |
| **3.8** | **Perform Conformity Assessment:** Conduct the required conformity assessment for each high-risk AI system before it is placed on the market, as per Article 43. This may be a self-assessment or require a third-party notified body. | Conformity Assessment |
| **3.9** | **Register in EU Database:** Register the high-risk AI system in the public EU database before placing it on the market or putting it into service. | N/A (Legal Requirement) |
| **3.10** | **Establish a Post-Market Monitoring System:** Implement a system to proactively collect and analyze performance data from high-risk AI systems after deployment to ensure continued compliance and identify new risks, as per Article 61. | Post-Market Monitoring |


### Track B: Parallel Compliance for General Purpose AI (GPAI) Providers

**Focus:** For providers of GPAI models (e.g., large language models, foundation models) to meet their specific obligations under the Act. These activities run in parallel to the risk-based phases.

**Timeline:** These requirements apply **12 months** after the Act’s enforcement.

| Activity ID | Activity Description | Compliance Essential(s) Addressed |
| :--- | :--- | :--- |
| **B.1** | **Develop and Maintain Technical Documentation:** Create and maintain detailed technical documentation for the GPAI model as required by Article 53, including its training process, data used, and evaluation results. | Technical Documentation |
| **B.2** | **Create Downstream Provider Information:** Prepare and provide comprehensive documentation for downstream providers who integrate the GPAI model into their own systems, enabling them to understand its capabilities and limitations. | Transparency & User Information |
| **B.3** | **Establish a Policy on EU Copyright Law:** Implement a policy to ensure the GPAI model's training respects EU copyright law, including honoring opt-outs from rightsholders. | Data Governance |
| **B.4** | **Publish a Detailed Summary of Training Data:** Make publicly available a sufficiently detailed summary of the content used to train the GPAI model. | Transparency & User Information |
| **B.5** | **Appoint an EU Representative:** If the GPAI provider is established outside the EU, they must appoint an authorized representative within the Union. | N/A (Legal Requirement) |
| **B.6** | **Register the GPAI Model:** Register the GPAI model in the official EU database for AI systems. | N/A (Legal Requirement) |
| **B.7** | **Cooperate with Authorities:** Establish processes to cooperate with the European Commission and national competent authorities upon request. | N/A (Legal Requirement) |

## 4. Conclusion

Achieving compliance with the EU AI Act requires a multifaceted and methodical strategy. This consolidated dual-track framework provides a clear, comprehensive, and actionable roadmap. By separating the journey into a risk-based track for AI system deployers—with granular steps for all phases—and a parallel track for GPAI model providers, organizations can address their specific obligations in a structured manner. This approach ensures that compliance efforts are proportional to risk while also accounting for the unique, cross-cutting nature of GPAI models, turning a complex legal challenge into a strategic advantage.

## 5. References

[1] World Health Organization. (2025). *Laboratory Quality Stepwise Implementation tool*. Retrieved from https://extranet.who.int/lqsi/content/homepage

[2] Forvis Mazars. (n.d.). *EU AI Act: different risk levels of AI systems*. Retrieved from https://www.forvismazars.com/ie/en/insights/news-opinions/eu-ai-act-different-risk-levels-of-ai-systems

[3] Security Compass. (2024, August 7). *Understanding EU AI Act Risk Categories*. Retrieved from https://www.securitycompass.com/blog/understanding-eu-ai-act-risk-categories/
