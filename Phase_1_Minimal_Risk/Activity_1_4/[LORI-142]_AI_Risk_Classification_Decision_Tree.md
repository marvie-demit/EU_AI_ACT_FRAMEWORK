[LORI-142]
Author: Dipl. Ing. Marvie Demit
---

# AI Risk Classification Decision Tree

**Source:** Activity_1_4


*This flowchart is the core of the procedure and should be followed sequentially.*

```mermaid
graph TD
    A[Start: AI System from Inventory] --> B{Step 1: Check for Unacceptable Risk (Art. 5)};
    B -->|Yes| C[Result: UNACCEPTABLE RISK - Prohibited];
    B -->|No| D{Step 2: Check for High-Risk Categories (Art. 6 & Annex III)};
    D -->|Yes| E{Does it pose a significant risk of harm to health, safety, or fundamental rights?};
    E -->|Yes| F[Result: HIGH-RISK];
    E -->|No| G[Result: MINIMAL RISK (Exempted High-Risk)];
    D -->|No| H{Step 3: Check for Limited Risk (Art. 52)};
    H -->|Yes| I[Result: LIMITED RISK];
    H -->|No| J[Step 4: Default to Minimal Risk];
    J --> K[Result: MINIMAL RISK];

    subgraph Step 1 Criteria
        B1[Manipulative techniques?]
        B2[Exploits vulnerabilities?]
        B3[Social scoring?]
        B4[Real-time remote biometric ID in public spaces?]
    end

    subgraph Step 2 Criteria
        D1[Is it a safety component of a product?]
        D2[Is it in a listed Annex III area? e.g., Biometric ID, Critical Infrastructure, Education, Employment, Essential Services, Law Enforcement, Migration, Justice]
    end

    subgraph Step 3 Criteria
        H1[Interacts with humans (chatbot)?]
        H2[Generates content (deepfake)?]
        H3[Infers emotions/biometric categorization?]
    end
```