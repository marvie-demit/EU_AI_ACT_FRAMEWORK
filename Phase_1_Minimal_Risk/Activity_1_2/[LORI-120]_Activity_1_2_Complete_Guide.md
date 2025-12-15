[LORI-120]
Author: Dipl. Ing. Marvie Demit
---

# Activity 1.2: Develop AI Inventory Procedure

**Phase:** 1 - Foundational Governance & Minimal Risk Compliance  
**Estimated Duration:** 2-3 weeks  
**Complexity:** Medium  
**Prerequisites:** Activity 1.1 (AI Governance Body established)

---

## 1. Activity Overview

### Purpose
Create a standardized, formal procedure for identifying, documenting, and maintaining a comprehensive register of all AI systems used or developed within the organization. This procedure transforms AI identification from an ad-hoc activity into a repeatable business process.

### Why This Matters
- **Compliance Foundation:** Cannot comply with EU AI Act without knowing which AI systems exist
- **Risk Management:** Impossible to assess risks for unknown systems
- **Regulatory Requirement:** Article 71 requires registration of High-Risk systems (must identify them first)
- **Continuous Process:** New AI systems are constantly being developed or procured
- **Consistency:** Standardized procedure ensures uniform data collection across all departments

### Key Deliverables
1. **AI System Inventory Procedure Document** - Formal process for identifying and documenting AI systems
2. **AI System Identification Form** - Standardized questionnaire for data collection
3. **Workflow Diagram** - Visual representation of the inventory process
4. **Communication Plan** - How the procedure will be rolled out organization-wide

### Success Criteria
- ✅ Procedure document approved by AI Governance Body
- ✅ Clear definition of "AI system" established
- ✅ Identification form tested with pilot group
- ✅ Workflow roles and responsibilities assigned
- ✅ Procedure communicated to all department heads

---

## 2. Detailed Implementation Tasks

### Task 1: Assign Drafting Responsibility (Day 1-2)
**Duration:** 1-2 days  
**Responsible:** AI Governance Body Chairperson

**Steps:**
1. Form a drafting sub-group from the AI Governance Body:
   - **Lead:** Compliance or IT representative
   - **Members:** Data Science, Legal, Business Unit representative
   - **Size:** 3-5 people optimal

2. Define sub-group mandate:
   - Draft procedure document and identification form
   - Pilot test with selected business units
   - Incorporate feedback and finalize
   - Present to full Governance Body for approval

3. Set timeline and milestones:
   - Draft completion: Week 1
   - Pilot testing: Week 2
   - Final approval: Week 3

4. Allocate resources:
   - Meeting time (4-6 hours total)
   - Document drafting time (20-30 hours)
   - Pilot testing time (10-15 hours)

**Deliverable:** Sub-group charter with timeline and resource allocation

---

### Task 2: Define "AI System" for Your Organization (Week 1)
**Duration:** 2-3 days  
**Responsible:** Drafting Sub-Group

**Steps:**
1. **Start with EU AI Act definition (Article 3(1)):**
   
   An AI system is a machine-based system that is designed to operate with varying levels of autonomy and that may exhibit adaptiveness after deployment, and that, for explicit or implicit objectives, infers, from the input it receives, how to generate outputs such as predictions, content, recommendations, or decisions that can influence physical or virtual environments.

2. **Translate into practical organizational definition:**
   
   Consider these questions:
   - Does this include simple rule-based systems? (Generally NO)
   - Does this include statistical models without ML? (Case-by-case)
   - Does this include AI embedded in vendor software? (YES)
   - Does this include experimental/R&D systems? (YES, if they process real data)
   - Does this include AI tools used by employees (e.g., ChatGPT)? (YES, if used for business purposes)

3. **Create decision tree for "Is this an AI system?"**
   
   Example criteria:
   - Uses machine learning, neural networks, or statistical inference? → YES
   - Makes autonomous decisions or recommendations? → YES
   - Adapts behavior based on data? → YES
   - Simple if-then rules with no learning? → NO
   - Pure data visualization with no prediction? → NO

4. **Document edge cases and examples:**
   - **Clearly AI:** Chatbot, recommendation engine, predictive maintenance, facial recognition
   - **Clearly NOT AI:** Spreadsheet formulas, static reports, manual workflows
   - **Gray Area:** Advanced analytics, optimization algorithms, expert systems (define your approach)

5. **Get legal review of definition** to ensure EU AI Act alignment

**Deliverable:** Organizational AI System Definition document with decision tree and examples

---

### Task 3: Design AI System Identification Form (Week 1)
**Duration:** 3-5 days  
**Responsible:** Drafting Sub-Group

**Steps:**
1. Use template **[LORI-121] AI System Identification Form** as starting point

2. Customize form sections to capture:
   
   **Section A: Basic Information**
   - System name and unique identifier
   - Department/business unit
   - System owner and technical contact
   - Vendor (if third-party) or internal development team
   
   **Section B: Technical Characteristics**
   - Type of AI (ML, NLP, computer vision, etc.)
   - Input data types and sources
   - Output types (predictions, recommendations, decisions, content)
   - Level of autonomy (fully automated vs. human-in-the-loop)
   
   **Section C: Use Case and Purpose**
   - Intended purpose and business objective
   - End users (internal employees, external customers, both)
   - Geographic deployment (EU, non-EU, both)
   - Deployment status (development, testing, production, decommissioned)
   
   **Section D: Preliminary Risk Indicators**
   - Does it interact with natural persons? (Yes/No)
   - Does it make decisions affecting individuals? (Yes/No)
   - Does it operate in a regulated domain? (Yes/No)
   - Could errors cause harm? (Yes/No)
   
   **Section E: Data and Privacy**
   - Does it process personal data? (Yes/No)
   - Does it process special category data? (Yes/No)
   - GDPR compliance status

3. **Balance comprehensiveness with usability:**
   - Form should take 15-30 minutes to complete
   - Use dropdown menus and checkboxes where possible
   - Include help text and examples for each question
   - Avoid overly technical jargon

4. **Choose form format:**
   - **Option A:** Online form (Google Forms, Microsoft Forms, Typeform)
   - **Option B:** Structured document (Word/PDF)
   - **Option C:** Integration with existing IT asset management system
   - **Recommendation:** Start with online form for ease of use and data aggregation

**Deliverable:** Customized AI System Identification Form (based on [LORI-121])

---

### Task 4: Draft the Inventory Procedure Document (Week 1-2)
**Duration:** 5-7 days  
**Responsible:** Drafting Sub-Group Lead

**Steps:**
1. Use template **[LORI-122] AI System Inventory Procedure Document** as foundation

2. **Customize the procedure to include:**

   **Section 1: Purpose and Scope**
   - Why this procedure exists
   - Which systems are covered (all AI per your definition)
   - Which departments must comply (typically all)
   
   **Section 2: Definitions**
   - Your organizational AI system definition
   - Key terms (system owner, deployer, provider, etc.)
   
   **Section 3: Roles and Responsibilities**
   - **System Owners:** Responsible for submitting identification forms
   - **Department Heads:** Ensure all systems in their area are reported
   - **AI Governance Body:** Reviews and approves inventory entries
   - **Inventory Administrator:** Maintains the central register
   
   **Section 4: Identification Process**
   - Step-by-step instructions for identifying AI systems
   - How to access and complete the identification form
   - Where to submit completed forms
   - Timeline expectations (e.g., within 10 business days of system deployment)
   
   **Section 5: Review and Approval Workflow**
   - Who reviews submitted forms (typically Inventory Administrator)
   - Criteria for acceptance (completeness, clarity)
   - Escalation process for unclear cases
   - Timeline for review (e.g., 5 business days)
   
   **Section 6: Inventory Maintenance**
   - How often inventory is reviewed (quarterly recommended)
   - Process for updating existing entries (system changes, decommissioning)
   - Process for adding new systems (continuous)
   - Use template **[LORI-123] System Decommissioning Procedure** for removals
   
   **Section 7: Compliance and Enforcement**
   - Mandatory nature of reporting
   - Consequences of non-compliance
   - Audit procedures

3. **Create workflow diagram:**
   - Visual flowchart showing the end-to-end process
   - Use standard flowchart symbols (start, decision, process, end)
   - Include decision points (e.g., "Is this an AI system?")
   - Show feedback loops (e.g., form returned for clarification)

4. **Include appendices:**
   - Appendix A: AI System Definition and Decision Tree
   - Appendix B: AI System Identification Form (blank template)
   - Appendix C: Examples of Completed Forms
   - Appendix D: FAQ

**Deliverable:** Complete AI System Inventory Procedure Document (based on [LORI-122])

---

### Task 5: Pilot Test the Procedure (Week 2)
**Duration:** 5-7 days  
**Responsible:** Drafting Sub-Group

**Steps:**
1. **Select pilot departments:**
   - Choose 2-3 departments with known AI usage
   - Include mix of technical (IT, Data Science) and non-technical (Marketing, HR)
   - Select cooperative department heads

2. **Conduct pilot briefing:**
   - Explain purpose of pilot
   - Walk through the procedure and form
   - Set expectations (identify 3-5 systems each)
   - Timeline (1 week to complete)

3. **Collect pilot data:**
   - Have pilot participants complete identification forms
   - Track time required to complete form
   - Note questions and confusion points
   - Gather feedback on clarity and usability

4. **Analyze pilot results:**
   - Review completed forms for quality and completeness
   - Identify common errors or misunderstandings
   - Assess whether AI definition is clear
   - Evaluate form length and complexity

5. **Refine procedure and form:**
   - Clarify confusing sections
   - Add examples where needed
   - Simplify overly complex questions
   - Update FAQ based on pilot questions

**Deliverable:** Pilot test report with recommended refinements

---

### Task 6: Obtain Formal Approval (Week 3)
**Duration:** 2-3 days  
**Responsible:** Drafting Sub-Group Lead + AI Governance Body

**Steps:**
1. **Prepare approval package:**
   - Final procedure document
   - Final identification form
   - Pilot test results and refinements made
   - Implementation plan and timeline
   - Resource requirements

2. **Present to AI Governance Body:**
   - Schedule on governance body meeting agenda (30-45 minutes)
   - Walk through procedure and form
   - Share pilot test results
   - Address questions and concerns
   - Request formal approval

3. **Incorporate final feedback:**
   - Make any last-minute adjustments requested
   - Ensure all governance body members agree

4. **Document approval:**
   - Record approval in governance body meeting minutes
   - Obtain sign-off from chairperson
   - Version the procedure document (v1.0)
   - Set review date (typically 12 months)

**Deliverable:** Approved AI System Inventory Procedure (v1.0) with governance body sign-off

---

### Task 7: Communicate and Roll Out Procedure (Week 3)
**Duration:** 3-5 days  
**Responsible:** AI Governance Body Chairperson + Communications

**Steps:**
1. **Create communication materials:**
   - Email announcement to all department heads
   - One-page procedure summary (quick reference)
   - Link to full procedure document
   - Link to identification form
   - FAQ document
   - Training presentation (optional but recommended)

2. **Conduct roll-out communications:**
   - **Week 1:** Email to all department heads with procedure
   - **Week 1-2:** Department head briefings (optional live sessions)
   - **Week 2:** Reminder email with deadline for initial inventory
   - **Ongoing:** Include in new employee onboarding

3. **Provide support resources:**
   - Designate point of contact for questions (Inventory Administrator)
   - Create email alias (e.g., ai-inventory@company.com)
   - Set up office hours for form completion assistance
   - Create internal wiki or intranet page with resources

4. **Set initial inventory deadline:**
   - Typically 4-6 weeks from procedure approval
   - Communicate clearly and repeatedly
   - Send reminders at 2 weeks and 1 week before deadline

**Deliverable:** Communication package and roll-out plan

---

## 3. Implementation Checklist

### Preparation
- [ ] Drafting sub-group formed and chartered
- [ ] Timeline and milestones established
- [ ] Resources allocated (time, budget)

### Definition Phase
- [ ] EU AI Act definition reviewed
- [ ] Organizational AI definition drafted
- [ ] Decision tree created with examples
- [ ] Edge cases documented
- [ ] Legal review of definition completed

### Form Design
- [ ] Template [LORI-121] customized
- [ ] All necessary data fields included
- [ ] Form tested for usability (15-30 min completion time)
- [ ] Help text and examples added
- [ ] Form format selected (online vs. document)

### Procedure Document
- [ ] Template [LORI-122] customized
- [ ] All sections completed (purpose, definitions, roles, process, maintenance)
- [ ] Workflow diagram created
- [ ] Appendices included (definition, form, examples, FAQ)
- [ ] Document reviewed for clarity

### Pilot Testing
- [ ] Pilot departments selected (2-3)
- [ ] Pilot briefing conducted
- [ ] Forms completed by pilot participants
- [ ] Feedback collected and analyzed
- [ ] Procedure and form refined based on feedback

### Approval
- [ ] Approval package prepared
- [ ] Presented to AI Governance Body
- [ ] Feedback incorporated
- [ ] Formal approval obtained and documented
- [ ] Procedure versioned (v1.0)
- [ ] Review date set (12 months)

### Roll-Out
- [ ] Communication materials created
- [ ] Department heads notified
- [ ] Procedure published on intranet/wiki
- [ ] Support resources established (email, office hours)
- [ ] Initial inventory deadline set and communicated
- [ ] Training sessions scheduled (if applicable)

---

## 4. Common Pitfalls and How to Avoid Them

### Pitfall 1: Overly Broad AI Definition
**Problem:** Definition is so broad that every software system is considered "AI," overwhelming the inventory process.

**Example:** Defining any system that "uses data" or "makes calculations" as AI.

**Consequences:**
- Inventory becomes unmanageable
- Resources wasted on clearly non-AI systems
- Business units become frustrated and non-compliant

**Mitigation:**
- Focus on systems that use ML, statistical inference, or autonomous decision-making
- Explicitly exclude simple rule-based systems and calculations
- Provide clear examples of what IS and IS NOT AI
- When in doubt, include in inventory (can always reclassify later)

---

### Pitfall 2: Overly Narrow AI Definition
**Problem:** Definition is so narrow that obvious AI systems are excluded, creating compliance gaps.

**Example:** Only counting systems explicitly labeled "AI" or "ML" by vendors.

**Consequences:**
- High-risk systems go unidentified
- Regulatory non-compliance
- Unexpected audit findings

**Mitigation:**
- Include all systems that meet EU AI Act definition, regardless of vendor labeling
- Focus on functionality (what it does) not labels (what it's called)
- Train employees to recognize AI capabilities (prediction, recommendation, content generation)
- Review vendor contracts and documentation for AI features

---

### Pitfall 3: Form Too Complex or Technical
**Problem:** Identification form requires deep technical knowledge, preventing non-technical employees from completing it.

**Consequences:**
- Low response rates
- Incomplete or inaccurate submissions
- Business units avoid reporting systems

**Mitigation:**
- Use plain language, not technical jargon
- Provide help text and examples for each question
- Include "I don't know" options with instructions to consult technical team
- Offer form completion assistance (office hours, designated contact)
- Test form with non-technical pilot participants

---

### Pitfall 4: No Clear Ownership or Accountability
**Problem:** Procedure doesn't specify who is responsible for identifying and reporting AI systems.

**Consequences:**
- Systems fall through the cracks
- Everyone assumes someone else will report
- Incomplete inventory

**Mitigation:**
- Assign clear responsibility to system owners and department heads
- Include inventory reporting in job descriptions and performance reviews
- Implement consequences for non-compliance (escalation to executive sponsor)
- Conduct regular audits to identify unreported systems
- Celebrate and recognize compliant departments

---

### Pitfall 5: One-Time Exercise Instead of Continuous Process
**Problem:** Inventory treated as a one-time project rather than ongoing business process.

**Consequences:**
- Inventory becomes outdated quickly
- New systems deployed without oversight
- Compliance gaps emerge over time

**Mitigation:**
- Build inventory reporting into system development lifecycle (required step before production deployment)
- Integrate with IT change management process
- Require inventory update for any system changes
- Conduct quarterly inventory reviews
- Include new system reporting in procurement process for vendor AI

---

### Pitfall 6: Lack of Executive Support
**Problem:** Procedure seen as bureaucratic overhead without executive backing.

**Consequences:**
- Low compliance rates
- Business units prioritize other work
- Governance body lacks authority to enforce

**Mitigation:**
- Ensure executive sponsor actively communicates importance
- Include inventory compliance in executive dashboards
- Escalate non-compliance to C-level
- Tie compliance to risk management and regulatory obligations
- Share success stories and benefits of inventory

---

## 5. Practical Examples

### Example 1: Financial Services Company
**Context:** Large bank with 50+ departments, mix of internal and vendor AI systems

**AI Definition Approach:**
- Included all ML-based systems (credit scoring, fraud detection, chatbots)
- Included vendor systems with AI features (CRM with predictive analytics)
- Excluded simple rule-based systems (transaction categorization)
- Included experimental R&D systems processing real customer data

**Form Design:**
- Online form (Microsoft Forms) with conditional logic
- Completion time: 20 minutes average
- Included dropdown menus for common fields (department, AI type)
- Required technical contact for follow-up questions

**Roll-Out Strategy:**
- Executive sponsor (CRO) sent company-wide email
- Mandatory briefing sessions for all department heads
- Dedicated inventory coordinator hired (0.5 FTE)
- 6-week deadline for initial inventory
- Result: 73 AI systems identified in first round

**Key Success Factor:** Executive backing and dedicated resources made compliance non-negotiable.

---

### Example 2: Healthcare Technology Startup
**Context:** Small company (50 employees), primarily internal AI development

**AI Definition Approach:**
- Focused on ML-based diagnostic and treatment recommendation systems
- Included all systems in development pipeline (not just production)
- Excluded employee productivity tools (e.g., Grammarly)

**Form Design:**
- Simple Google Form (10 minutes to complete)
- Only essential fields (name, purpose, owner, risk indicators)
- All employees trained to recognize AI systems

**Roll-Out Strategy:**
- CEO announced procedure in all-hands meeting
- VP Engineering responsible for ensuring compliance
- All developers required to submit form before code merge to main branch
- Result: 8 AI systems identified, all High-Risk (medical devices)

**Key Success Factor:** Integration with development workflow made inventory automatic.

---

### Example 3: E-commerce Retailer
**Context:** Mid-sized online retailer, heavy use of vendor AI (recommendations, search, chatbots)

**AI Definition Approach:**
- Included all vendor systems with AI capabilities
- Required procurement team to flag AI in vendor contracts
- Included marketing automation with predictive features

**Form Design:**
- Word document form (easier for vendor information gathering)
- Separate section for vendor systems (required vendor documentation)
- Completion time: 25 minutes

**Roll-Out Strategy:**
- IT and Procurement teams jointly responsible
- Vendor contracts reviewed for AI features
- Ongoing requirement: procurement must submit form before signing new vendor contracts
- Result: 15 AI systems identified (12 vendor, 3 internal)

**Key Success Factor:** Integration with procurement process caught vendor AI systems.

---

## 6. Related Templates and Documents

The following templates support this activity and are available as separate documents:

- **[LORI-121] AI System Identification Form** - Standardized questionnaire for data collection
- **[LORI-122] AI System Inventory Procedure Document** - Formal procedure template
- **[LORI-123] System Decommissioning Procedure** - Process for removing systems from inventory

These templates should be customized to your organization's specific context and approved by the AI Governance Body.

---

## 7. Timeline and Resource Estimates

### Typical Timeline: 2-3 weeks

| Week | Tasks | Effort (Hours) |
|------|-------|----------------|
| 1 | Assign responsibility, define AI system, design form, draft procedure | 25-35 |
| 2 | Pilot test procedure, collect feedback, refine | 15-20 |
| 3 | Obtain approval, communicate and roll out | 10-15 |

**Total Effort:** 50-70 hours (distributed across sub-group)

### Resource Requirements
- **Sub-Group Lead:** 25-35 hours
- **Sub-Group Members:** 10-15 hours each (2-4 members)
- **Legal Review:** 5-10 hours
- **Pilot Participants:** 2-3 hours each (6-10 people)
- **Communications:** 5-10 hours

---

## 8. Success Metrics

### Immediate Metrics (End of Activity)
- Procedure approved by AI Governance Body: **Yes/No**
- AI definition clarity rating (pilot feedback): **Target >4.0/5.0**
- Form completion time: **Target <30 minutes**
- Pilot participant satisfaction: **Target >3.5/5.0**

### 90-Day Metrics (After Roll-Out)
- Department compliance rate: **Target >80%**
- Forms submitted: **Target: All known AI systems reported**
- Form completion quality: **Target >90% complete on first submission**
- Questions/support requests: **Track volume and common themes**

### 12-Month Metrics
- Inventory completeness (audit validation): **Target >95%**
- Procedure adherence rate: **Target >90%**
- New systems reported within SLA: **Target >85%**
- Procedure effectiveness rating: **Target >4.0/5.0**

---

## 9. Legal and Regulatory References

### EU AI Act References
- **Article 3(1):** Definition of AI system
- **Article 71:** Registration obligations for High-Risk systems (requires inventory)
- **Recital 6:** Emphasizes need for clear identification of AI systems

### Supporting Standards
- **ISO/IEC 5338:2023** - AI system life cycle processes (includes inventory management)
- **NIST AI RMF** - Govern function includes inventory as a key activity

### Best Practice Resources
- **EU AI Act Full Text:** [https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689)
- **OECD AI Principles:** Emphasize transparency and accountability (requires knowing what systems exist)

---

## 10. Next Steps

Upon completion of Activity 1.2, proceed to:

1. **Activity 1.3: Conduct Initial AI System Inventory** - Execute the procedure to identify all existing AI systems
2. **Activity 1.4: Develop Risk Classification Procedure** - Create process for assessing risk level of inventoried systems

The inventory procedure developed in this activity will be used immediately in Activity 1.3 and will become a permanent business process for ongoing compliance.

---

**Document Version:** 2.0  
**Last Updated:** December 2024  
**Next Review Date:** December 2025
