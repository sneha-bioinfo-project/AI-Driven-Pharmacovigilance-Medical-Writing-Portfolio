# Graphical Abstract Specification & Visual Blueprint

## Title

**Integrated Machine Learning Pipeline for Active ADR Detection from EHR Big Data**

---

# Graphical Abstract Layout Schematic

```text
┌───────────────────────────────────────────────────────────────────────┐
│                     GRAPHICAL ABSTRACT WORKFLOW                     │
├───────────────────────────────────────────────────────────────────────┤
│                                                                       │
│ PANEL A                 PANEL B                 PANEL C               │
│ DATA SOURCES            PREPROCESSING           ML ENGINE             │
│                                                                       │
│ Structured EHR Data ─┐  Data Cleaning          Random Forest           │
│ Clinical Notes      ─┼─► Deduplication ─────►  XGBoost                 │
│ FAERS / SIDER       ─┘  RxNorm / MedDRA        CNN / RNN               │
│                       SMOTE Correction          Model Evaluation       │
│                                                                       │
├───────────────────────────────────────────────────────────────────────┤
│                                                                       │
│ PANEL D                                      PANEL E                  │
│ PRIVACY & DEPLOYMENT                         CLINICAL IMPACT           │
│                                                                       │
│ Federated Learning                           Explainable AI Dashboard │
│ Local Hospital Training ───────────────►     Clinical Alerts          │
│ ABDM Integration                             Improved Patient Safety  │
│                                                                       │
└───────────────────────────────────────────────────────────────────────┘
