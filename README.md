# Tab2Text
Overview

This repository implements a fact-faithful tabular-to-text generation pipeline for longitudinal clinical data, with a focus on knee osteoarthritis (OA).
The code converts structured tabular records (demographics, imaging, biomarkers, and patient-reported outcomes) into interpretable free-text summaries without hallucination.

The design follows a hybrid architecture:

**Deterministic template verbalizer for guaranteed factual correctness**
**Learnable content selector to decide what information to mention**
