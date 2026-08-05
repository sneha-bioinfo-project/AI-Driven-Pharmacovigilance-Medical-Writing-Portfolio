# Key Messages

## 1. Clinical & Health Impact Messages

### High Clinical Burden

Adverse drug reactions (ADRs) account for approximately 5% of hospital admissions worldwide, contributing to patient harm, prolonged hospital stays, and increased healthcare costs.

### Limitations of Passive Monitoring

Traditional spontaneous reporting systems are affected by under-reporting, clinician workload limitations, and delayed signal identification, reducing the effectiveness of early ADR detection.

---

## 2. Technical & Methodological Messages

### Multi-Modal EHR Data Integration

Combining structured Electronic Health Record (EHR) data, including laboratory results and medication records, with unstructured clinical text such as progress notes improves the ability of machine learning models to identify ADR patterns.

### Machine Learning Performance

Supervised learning approaches, including Random Forest, XGBoost, and Deep Neural Networks, demonstrate strong predictive performance across benchmark datasets such as MIMIC-III, FAERS, and SIDER, with reported AUC values ranging from 0.75 to 0.80.

### Essential Data Processing Requirements

Reliable machine learning pipelines require:

- Standardisation of clinical concepts using controlled vocabularies such as RxNorm and MedDRA
- Data preprocessing and quality control
- Management of class imbalance using approaches such as SMOTE

These steps improve reproducibility and model robustness.

---

## 3. Policy & Implementation Messages

### Privacy-Preserving Federated Learning

Federated Learning enables multiple healthcare institutions to collaboratively train machine learning models without transferring sensitive patient-level data, supporting compliance with privacy frameworks such as HIPAA and GDPR.

### Building Clinical Trust Through Explainable AI

Explainable Artificial Intelligence (XAI) approaches provide transparent insights into model predictions, improving clinician confidence and supporting responsible clinical decision-making.

### Integration with National Digital Health Frameworks

Connecting ML-based pharmacovigilance systems with digital health initiatives, such as the Ayushman Bharat Digital Mission (ABDM) in India, may support scalable and equitable nationwide ADR surveillance.

---
