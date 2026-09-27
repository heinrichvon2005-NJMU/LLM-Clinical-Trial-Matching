# Clinical Trial Matching Model

## Overview

This repository contains a large language model (LLM)-based clinical trial matching system designed to identify and recommend potentially eligible clinical trials for individual patients.

The model integrates **up-to-date clinical guidelines, real-world clinical data, and contemporary clinical trial information** to improve patient–trial matching and eligibility assessment.

## Training Data

The model was developed using a clinically oriented dataset consisting of:

* **20,000 real-world patient cases** from Jiangsu Province Hospital
* **200 recent clinical trials** covering relevant clinical indications and eligibility criteria
* **Up-to-date clinical guidelines** and evidence-based clinical recommendations

The real-world patient cohort provides clinically grounded patient representations, while the clinical trial dataset captures contemporary eligibility criteria and study characteristics. Clinical guidelines are incorporated to provide additional clinical context for patient–trial matching.

## Key Features

* **Patient–Trial Matching:** Identifies clinical trials that may be suitable for individual patients.
* **Eligibility Assessment:** Evaluates patient characteristics against key inclusion and exclusion criteria.
* **Clinical Guideline Integration:** Incorporates recommendations from the latest clinical guidelines.
* **Real-World Clinical Data:** Trained and developed using 20,000 real clinical cases.
* **Contemporary Trial Knowledge:** Incorporates information from 200 recent clinical trials.
* **LLM-Based Clinical Reasoning:** Uses large language models to interpret complex clinical information and trial eligibility criteria.

## Model Pipeline

The overall workflow consists of:

```text
Patient Clinical Information
            ↓
Clinical Information Extraction
            ↓
Patient Profile Construction
            ↓
Clinical Trial Retrieval
            ↓
Eligibility Criteria Matching
            ↓
Clinical Guideline–Informed Reasoning
            ↓
Candidate Trial Ranking
            ↓
Structured Matching Results
```

## Clinical Data

The model was developed using real-world clinical cases from **Jiangsu Province Hospital**.

Due to patient privacy, institutional policies, and ethical requirements, the original patient-level clinical data are **not publicly released** in this repository.

Only the model implementation, supporting code, and publicly shareable resources are provided.

## Clinical Trial Data

The training and development dataset includes **200 recent clinical trials**. Trial information was structured according to clinically relevant dimensions, including:

* Disease and diagnosis
* Disease stage and severity
* Previous and current treatments
* Biomarker and molecular characteristics
* Laboratory and imaging findings
* Inclusion criteria
* Exclusion criteria
* Treatment-related requirements
* Other protocol-specific eligibility conditions

## Intended Use

This project is intended for:

* Research on AI-assisted clinical trial matching
* Development of clinical decision-support systems
* Medical LLM research
* Patient–trial eligibility assessment
* Clinical trial recruitment research
* Medical AI and healthcare informatics applications

The system is designed as a **research tool** and should not be used as a substitute for professional clinical judgment or formal clinical trial eligibility review.

## Data Privacy and Ethics

All real-world clinical data used during model development were obtained and processed under applicable institutional and ethical requirements.

No identifiable patient information is included in the public repository.

## Project Status

This project is under active development. Future work will focus on:

* Expanding the clinical trial database
* Incorporating continuously updated trial information
* Improving eligibility reasoning
* Multicenter external validation
* Prospective clinical evaluation
* Integration with clinical workflow systems

## Citation

If you use this project or its methodology in your research, please cite the corresponding publication:

```bibtex
@article{
  ...
}
```

## Disclaimer

This repository is intended for **research and educational purposes only**. The model's outputs should not be interpreted as definitive clinical trial eligibility determinations or medical advice. Final eligibility should always be confirmed by qualified clinical investigators according to the official trial protocol.
