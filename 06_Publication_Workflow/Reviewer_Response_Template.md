# Peer Review Response & Manuscript Revision Template

**Educational Portfolio Material – Mock Peer Review Response Document**  
**Document Purpose:** Demonstrates professional medical writing standards for managing editorial and peer-reviewer feedback, structured point-by-point responses, and tracking manuscript revisions.

---

**Date:** 15 October 2026  

**To:** Editorial Board, *Drug Safety*  
**Re:** Response to Reviewer Comments on Manuscript [DSAF-D-26-00123]  
**Title:** *Applications of Current Machine Learning Methodologies in Pharmacovigilance and Signal Detection: A Narrative Synthesis*  

Dear Dr. Editor and Reviewers,

Thank you for the constructive feedback and thorough evaluation of our manuscript. We have revised the document to address all editorial and reviewer comments. 

Below, we provide a point-by-point response detailing how each comment has been addressed, along with line-numbered locations of changes in the revised manuscript. All modified text in the revised manuscript is highlighted in **bold** for ease of review.

---

## Response to Editorial Comments

### Editorial Comment 1
> *Please ensure all terminology aligns with standard pharmacovigilance definitions and that review scope claims are strictly calibrated to the methodology used.*

* **Author Response:** We acknowledge this important guidance. We have systematically reviewed the manuscript to ensure all terminology strictly adheres to MedDRA and ICH E2E guidelines. Furthermore, we have verified that the literature methodology is consistently described as a "structured literature search" rather than a systematic review to reflect the absence of prospective protocol registration (e.g., PROSPERO).
* **Manuscript Revision (Page 3, Line 72):**
  > *Revised from:* "This systematic review analyzes machine learning models..."  
  > *Revised to:* "**This narrative synthesis evaluates evidence gathered through a structured literature search on machine learning models...**"

---

## Response to Reviewer 1

### Reviewer 1, Comment 1
> *The discussion regarding Natural Language Processing (NLP) in clinical notes is informative, but the manuscript should place greater emphasis on the challenges of processing negation and conditional statements (e.g., 'rule out Stevens-Johnson syndrome').*

* **Author Response:** We agree with the reviewer that handling contextual nuances such as negation and conditional clinical phrases represents a major technical hurdle in automated adverse event extraction. We have expanded Section 3.1 and Section 4 to explicitly detail how Named Entity Recognition (NER) models handle negation detection algorithms.
* **Manuscript Revision (Page 6, Lines 142–148):**
  > *Added Text:* "**A persistent challenge in NLP-driven extraction is the accurate resolution of negation and conditional phrasing within unstructured medical narratives (e.g., 'denies rash' or 'evaluate for possible hepatotoxicity'). Recent transformer architectures integrate context-aware attention mechanisms to distinguish between confirmed adverse drug events and ruled-out differential diagnoses, thereby reducing false-positive extraction rates.**"

---

## Response to Reviewer 2

### Reviewer 2, Comment 1
> *The authors note that machine learning models improve disproportionality scoring, but there is insufficient discussion regarding the 'black-box' nature of complex models and regulatory expectations for auditability.*

* **Author Response:** We thank Reviewer 2 for highlighting this crucial point. Algorithmic transparency is paramount in regulatory pharmacovigilance. We have updated Section 4 (Discussion) and the Executive Brief to emphasize the necessity of model interpretability (e.g., SHAP/LIME frameworks) and the central role of human-in-the-loop expert validation.
* **Manuscript Revision (Page 9, Lines 210–218):**
  > *Added Text:* "**From a regulatory compliance perspective, fully opaque 'black-box' machine learning models present auditing challenges during drug safety inspections. Regulatory agencies require transparent decision pathways when generating safety signals. Consequently, explainable AI techniques (such as SHapley Additive exPlanations) and human-in-the-loop oversight remain mandatory to ensure algorithmic outputs undergo rigorous clinical verification prior to regulatory escalation.**"
