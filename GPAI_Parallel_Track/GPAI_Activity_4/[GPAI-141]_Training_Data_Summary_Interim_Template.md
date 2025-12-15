[GPAI-141]
Author: Dipl. Ing. Marvie Demit
---

# Training Data Summary (Interim Template)

**Source:** GPAI_Activity_4


*(This template should be used until the official AI Office template is published. It is based on current best practices and the likely requirements of the Act.)*

```markdown
# Training Data Summary for [Model Name] - Version [Version]

**Publication Date:** [Date]

This document provides a summary of the content used to train the [Model Name] GPAI model, in accordance with Article 53(1)(d) of the EU AI Act.

## 1. Overview of the Training Corpus

The training corpus for this model consists of approximately **[e.g., 1.5 trillion]** tokens, comprising a diverse mix of text and code data. The data collection process was completed on **[Date]**.

## 2. Data Source Categories

The corpus is composed of the following categories of data sources. The percentages are approximate and based on token count.

| Data Source Category | Percentage of Corpus | Description |
| :--- | :--- | :--- |
| **Public Web Data** | ~60% | A broad crawl of the public internet, filtered for quality and to remove inappropriate content. Major sources include [e.g., "Common Crawl, Wikipedia"]. |
| **Books** | ~20% | A collection of digitized books from various genres, including fiction, non-fiction, and technical manuals. |
| **Academic Papers** | ~10% | A collection of publicly available research papers from sources like [e.g., "arXiv"]. |
| **Licensed News Archives** | ~5% | Licensed content from reputable news organizations, covering the period [e.g., "1990-2024"]. |
| **Code** | ~5% | Publicly available code from open-source software repositories, primarily from [e.g., "GitHub"]. |

## 3. Data Processing and Filtering

All data underwent a rigorous pre-processing and filtering pipeline before being used for training. This process included:

*   **Quality Filtering:** Low-quality, repetitive, or machine-generated content was identified and removed.
*   **PII Removal:** Automated techniques were used to detect and remove personally identifiable information (PII) such as names, email addresses, and phone numbers.
*   **Toxicity Filtering:** Content identified as hateful, violent, or otherwise toxic was removed from the training set.
*   **Copyright Compliance:** In accordance with our EU Copyright Compliance Policy, we have honored opt-outs from rightsholders who have reserved their rights for text and data mining (TDM). Sources for which TDM rights were reserved have been excluded from this corpus.

## 4. Further Information

For more information on the model's performance, limitations, and intended uses, please refer to the **[Link to Model Card]**.

```