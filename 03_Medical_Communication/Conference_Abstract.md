# Scientific Conference Abstract

## Title

**Machine Learning Applications for Early Adverse Drug Reaction Detection Using Electronic Health Record Big Data: A Narrative Synthesis and Implementation Framework**

---

## Background

Adverse drug reactions (ADRs) cause approximately 5% of global hospital admissions and represent a significant challenge in healthcare safety. Traditional spontaneous reporting frameworks are limited by under-reporting and delayed signal detection.

Machine learning (ML) applied to Electronic Health Records (EHRs) provides a proactive approach for early ADR detection by analysing large-scale clinical data and identifying complex drug–reaction patterns.

---

## Methods

A structured literature search was conducted across major biomedical and technical databases, including:

- PubMed (n = 1,655)
- Web of Science (n = 3,338)
- Embase (n = 2,421)
- IEEE Xplore (n = 66)

Following PRISMA-based screening, 59 studies were included for qualitative synthesis and 33 studies were evaluated for quantitative analysis.

The review examined:

- Machine learning algorithms used for ADR prediction
- Benchmark datasets including MIMIC-III, SIDER, FAERS, and PvPI
- Data preprocessing and engineering approaches
- Clinical implementation challenges
- Emerging policy and technology frameworks

---

## Results

Supervised machine learning algorithms, including Random Forest, XGBoost, and Support Vector Machines, demonstrated strong discriminative performance for ADR prediction using structured EHR data, with reported AUC values ranging from 0.75 to 0.80.

Deep learning architectures, including Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs), showed potential for extracting contextual ADR signals from unstructured clinical notes.

Key computational requirements included:

- Data deduplication
- Standardised vocabulary mapping using systems such as RxNorm and MedDRA
- Class imbalance correction approaches such as SMOTE

Major translational barriers identified include:

- Data heterogeneity
- Privacy and regulatory restrictions (HIPAA and GDPR)
- Limited interpretability of machine learning models in clinical environments

---

## Conclusion

Integrating machine learning algorithms with active EHR-based surveillance systems has the potential to enhance early ADR signal detection and improve patient safety.

Future implementation of Explainable Artificial Intelligence (XAI) and privacy-preserving Federated Learning approaches, aligned with national digital health initiatives such as the Ayushman Bharat Digital Mission, may provide a scalable framework for real-time pharmacovigilance.

---
