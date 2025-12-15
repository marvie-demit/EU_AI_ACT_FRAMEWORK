[[LORI-140]]
Author: Dipl. Ing. Marvie Demit
---

# Activity 1.4: Develop Risk Classification Procedure

**Phase:** 1 - Foundational Governance & Minimal Risk Compliance  
**Estimated Duration:** 2-3 weeks  
**Complexity:** Medium  
**Prerequisites:** Activity 1.1 (AI Governance Body established)

---

## 1. Activity Overview

### Purpose
Create a standardized procedure for classifying AI systems according to EU AI Act risk categories (Unacceptable, High-Risk, Limited Risk, Minimal Risk).

### Why This Matters
Risk classification determines which compliance obligations apply. Misclassification can lead to under-compliance (regulatory violations) or over-compliance (wasted resources). Article 6 requires providers to assess whether their system is High-Risk.

### Key Deliverables
- Risk Classification Procedure Document ([LORI-141])
- Risk Classification Decision Tree ([LORI-142])
- Classification workflow and approval process

---

## 2. Implementation Tasks

### Task 1: Study EU AI Act Risk Categories (Week 1)
- Review Article 6 (High-Risk definition) and Annex III (High-Risk use cases)
- Understand prohibited systems (Article 5)
- Review Article 52 (Limited Risk transparency obligations)
- Document edge cases specific to your industry

### Task 2: Create Classification Decision Tree (Week 1-2)
- Start with: Is the system prohibited? (Article 5)
- Then: Is it listed in Annex III or a safety component? → High-Risk
- Then: Does Article 52 apply? (chatbot, deepfake, biometric) → Limited Risk
- Otherwise: → Minimal Risk
- Customize template [LORI-142] with your organization's examples

### Task 3: Draft Procedure Document (Week 2)
- Use template [LORI-141]
- Define who performs classification (typically system owner + governance body review)
- Establish approval workflow (initial classification + governance body confirmation)
- Set timeline requirements (before system deployment)
- Include re-classification triggers (significant system changes)

### Task 4: Pilot Test Procedure (Week 2-3)
- Select 5-10 systems from inventory (Activity 1.3)
- Apply classification procedure
- Identify ambiguities or unclear cases
- Refine procedure based on pilot results

### Task 5: Obtain Approval and Roll Out (Week 3)
- Present to AI Governance Body for approval
- Communicate procedure to all system owners
- Integrate with system development lifecycle

---

## 3. Common Pitfalls and Mitigation

### Pitfall 1: Misinterpreting Annex III
**Problem:** Annex III use cases are specific. Don't assume your system is High-Risk without careful analysis.

**Example:** Not all HR systems are High-Risk. Only those used for "recruitment or selection of natural persons" (Annex III, point 4(a)). Employee performance management is NOT in Annex III.

**Mitigation:** Read Annex III literally. Seek legal counsel for borderline cases.

---

### Pitfall 2: Ignoring "Safety Component" Definition
**Problem:** Your AI might not be in Annex III but could still be High-Risk if it's a safety component of a product covered by EU safety legislation.

**Example:** AI in medical devices, machinery, toys, aviation equipment.

**Mitigation:** Review Article 6(1)(b) and consult with product safety/regulatory teams.

---

### Pitfall 3: Static Classification
**Problem:** Treating classification as one-time decision.

**Reality:** Systems evolve. A change in purpose, deployment context, or functionality can change risk level.

**Mitigation:** Include re-classification triggers in procedure (use template [LORI-154]). Require re-classification for any significant system change.

---

## 4. Practical Examples

### Example 1: Chatbot Classification
**System:** Customer service chatbot  
**Initial Thought:** Just a chatbot, probably Minimal Risk  
**Correct Classification:** Limited Risk (Article 52(1) - users must be informed they're interacting with AI)  
**Key Learning:** Article 52 transparency obligations create Limited Risk category even for simple chatbots.

---

### Example 2: Resume Screening Tool
**System:** AI that ranks job applicants  
**Initial Thought:** HR tool, maybe Limited Risk  
**Correct Classification:** High-Risk (Annex III, point 4(a) - recruitment and selection)  
**Key Learning:** Annex III specifically lists this use case. Full High-Risk compliance required.

---

### Example 3: Predictive Maintenance
**System:** AI predicting equipment failures in manufacturing  
**Initial Thought:** Internal operations, probably Minimal Risk  
**Correct Classification:** Depends - If equipment failure could cause safety risk, might be High-Risk under Article 6(1)(b) as safety component  
**Key Learning:** Context matters. Same AI can be different risk levels in different applications.

---

## 5. Related Templates

- **[LORI-141] AI Risk Classification Procedure Document**
- **[LORI-142] AI Risk Classification Decision Tree**
- **[LORI-154] Risk Re-classification Procedure**

---

## 6. Next Steps

Proceed to Activity 1.5: Classify All Inventoried Systems using the procedure developed in this activity.

---

**Document Version:** 2.0  
**Last Updated:** December 2024  
**Next Review Date:** December 2025
