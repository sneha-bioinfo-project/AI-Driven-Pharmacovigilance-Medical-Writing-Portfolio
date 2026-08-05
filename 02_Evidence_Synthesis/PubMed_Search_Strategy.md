# PubMed / MEDLINE Systematic Literature Search Documentation

**Educational Portfolio Material – Evidence Synthesis Method**  
**Target Subject:** Machine Learning and Natural Language Processing in Pharmacovigilance  
**Language Standard:** UK English  

---

## 1. Research Question Framework (PEO Framework)

To structure the search strategy, the clinical research question was framed using the **Population, Exposure/Intervention, Outcome (PEO)** model:

* **Population (P):** Post-marketing safety databases, spontaneous reporting systems (FAERS, EudraVigilance), electronic health records (EHRs), and clinical narrative text.
* **Exposure / Intervention (E):** Current machine learning (ML), natural language processing (NLP), transformer models, and multi-variable disproportionality algorithms.
* **Outcome (O):** Automated extraction of adverse drug reactions (ADRs), Individual Case Safety Report (ICSR) triage optimization, signal detection sensitivity, and confounding reduction.

---

## 2. Database & Search Parameters

* **Database Searched:** PubMed / MEDLINE (NCBI)
* **Search Execution Date:** 10 February 2026
* **Publication Window:** 1 January 2018 – 31 December 2025
* **Language Filter:** English language only
* **Species Filter:** Humans (where applicable)

---

## 3. Search Terms and Boolean Logic

The search strategy combined Medical Subject Headings (MeSH) and free-text terms using Boolean operators (`OR` within concept blocks, `AND` between concept blocks).

### Block 1: Pharmacovigilance & Drug Safety
* `"Pharmacovigilance"[Mesh]`
* `"Adverse Drug Reaction Reporting Systems"[Mesh]`
* `"Product Surveillance, Postmarketing"[Mesh]`
* `"Drug-Related Side Effects and Adverse Reactions"[Mesh]`
* `"safety signal"` [Text Word] OR `"adverse event mining"` [Text Word]

### Block 2: Machine Learning & Computational Methodology
* `"Machine Learning"[Mesh]`
* `"Natural Language Processing"[Mesh]`
* `"Artificial Intelligence"[Mesh]`
* `"deep learning"` [Text Word] OR `"transformer model"` [Text Word] OR `"named entity recognition"` [Text Word]

### Block 3: Data Streams & Source Text
* `"Electronic Health Records"[Mesh]`
* `"unstructured text"` [Text Word] OR `"clinical notes"` [Text Word] OR `"spontaneous reports"` [Text Word]

---

## 4. Final Consolidated PubMed Search String

```text
(("Pharmacovigilance"[Mesh] OR "Adverse Drug Reaction Reporting Systems"[Mesh] OR "Product Surveillance, Postmarketing"[Mesh] OR "safety signal"[TiAb] OR "adverse event mining"[TiAb])
AND
("Machine Learning"[Mesh] OR "Natural Language Processing"[Mesh] OR "Artificial Intelligence"[Mesh] OR "deep learning"[TiAb] OR "named entity recognition"[TiAb])
AND
("Electronic Health Records"[Mesh] OR "unstructured text"[TiAb] OR "clinical notes"[TiAb] OR "spontaneous reports"[TiAb]))
AND
("2018/01/01"[Date - Publication] : "2025/12/31"[Date - Publication])
AND
English[Language]
