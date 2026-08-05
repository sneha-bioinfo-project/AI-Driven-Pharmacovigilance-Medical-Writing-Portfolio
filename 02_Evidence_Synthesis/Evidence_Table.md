# Evidence Table: Machine Learning Applications in ADR Detection

## Overview

This evidence table summarises key data sources, computational approaches, and applications discussed in the review manuscript on machine learning-based adverse drug reaction (ADR) detection using electronic health records (EHRs) and healthcare big data.

The table focuses on major resources and methodological categories relevant to pharmacovigilance research.

---

## Evidence Summary

| Evidence Source / Approach | Data Type | Application in ADR Research | Key Contribution |
|---|---|---|---|
| Electronic Health Records (EHRs) | Structured and unstructured clinical data | ADR prediction and risk modelling | Enables analysis of patient demographics, laboratory results, prescriptions, diagnoses, and clinical notes |
| FAERS (FDA Adverse Event Reporting System) | Spontaneous adverse event reports | Post-marketing safety surveillance and signal detection | Supports large-scale pharmacovigilance analysis using reported drug-event associations |
| SIDER Database | Drug–side effect associations | Drug safety modelling and ADR relationship analysis | Provides curated information linking drugs with known side effects |
| MIMIC-III Database | Critical care EHR data | Clinical prediction and healthcare machine learning research | Provides longitudinal patient records including medications, diagnoses, and outcomes |
| EHRSHOT Benchmark | Clinical prediction dataset | Evaluation of machine learning approaches in healthcare scenarios | Supports development and assessment of predictive models |
| PvPI (Pharmacovigilance Programme of India) | ADR case reports | Indian pharmacovigilance monitoring | Represents national-level ADR reporting infrastructure |

---

## Machine Learning Approaches

| Methodology | Data Application | Role in ADR Detection |
|---|---|---|
| Random Forest | Structured clinical data | Drug risk prediction and classification |
| Decision Trees | Patient and medication features | Interpretable ADR prediction models |
| XGBoost / Gradient Boosting | Structured healthcare datasets | Improved predictive performance for classification tasks |
| Support Vector Machines (SVM) | Feature-based clinical datasets | Pattern recognition and ADR classification |
| Deep Learning Models | Clinical notes and complex healthcare data | Extraction of complex patterns from high-dimensional datasets |
| Natural Language Processing (NLP) | Unstructured clinical text | Identification of ADR mentions and drug-event relationships |

---

## Evidence Synthesis Notes

- Machine learning approaches demonstrate potential for improving ADR signal detection compared with traditional pharmacovigilance methods.
- Model performance depends on data quality, preprocessing strategies, dataset characteristics, and validation approaches.
- Major implementation challenges include data heterogeneity, class imbalance, privacy concerns, interpretability, and clinical integration.
- External validation and explainable AI approaches remain important requirements for real-world deployment.
