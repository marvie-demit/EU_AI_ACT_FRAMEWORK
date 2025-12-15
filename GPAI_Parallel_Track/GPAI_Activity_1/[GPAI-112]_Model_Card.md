[GPAI-112]
Author: Dipl. Ing. Marvie Demit
---

# Model Card

**Source:** GPAI_Activity_1


```markdown
# Model Card for [Model Name]

## Model Details

*   **Model Name:** [e.g., "EnterpriseHelper-7B"]
*   **Version:** [e.g., 2.1.0]
*   **Date:** [Date]
*   **Model Type:** [e.g., "Generative Pre-trained Transformer (GPT) for Text Generation"]
*   **License:** [e.g., "Apache 2.0"]

## Intended Use

*   **Primary Intended Uses:** This model is designed for [e.g., "summarization of business documents, drafting emails, and answering questions based on a provided knowledge base"].
*   **Known Out-of-Scope Uses:** This model is **not** intended for [e.g., "providing medical, legal, or financial advice, or for use in high-stakes decision-making without human oversight"].

## Training Data

*   **Data Summary:** The model was trained on a corpus of [e.g., "1.5 trillion tokens consisting of publicly available web data, books, and a curated set of internal company documents (non-sensitive)"].
*   **Data Pre-processing:** [e.g., "Data was filtered to remove personally identifiable information (PII) and toxic content. A de-duplication process was applied."]

## Evaluation

*   **Evaluation Datasets:** The model was evaluated on standard academic benchmarks, including [e.g., "MMLU, HellaSwag, and TruthfulQA"], as well as an internal test set of 10,000 business-related prompts.
*   **Performance Metrics:**
    *   **MMLU (5-shot):** 78.5%
    *   **Toxicity (RealToxicityPrompts):** 0.5% generation of toxic content
    *   **Bias (BBQ Benchmark):** 65% accuracy (indicating some social biases are present)

## Ethical Considerations & Limitations

*   **Risks:** The model may produce factually incorrect information ("hallucinations"), reflect societal biases present in the training data, or be used to generate harmful content.
*   **Mitigations:** [e.g., "Fine-tuning was performed to reduce hallucinations. Users should be informed that the model can make mistakes. Downstream providers are advised to implement content filters."]

## Environmental Impact

*   **Estimated Energy Consumption:** Training for this model is estimated to have consumed approximately [e.g., "700,000 kWh"], with a carbon footprint of [e.g., "300 tCO2e"], using a cloud provider in a region powered by [e.g., "50% renewable energy"].
```