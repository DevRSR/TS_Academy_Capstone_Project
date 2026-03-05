# **TS ACADEMY Capstone Project - Group 19 (March 2026)**

### Title: Brain Cancer Gene Expression Analysis for Subtype Classification and Biomarker Discovery

## Project Overview

This capstone project focuses on the computational analysis of the Brain_GSE50161 dataset, containing 54,676 gene expression features across 130 samples representing four distinct brain cancer types (ependymoma, glioblastoma, medulloblastoma, pilocytic astrocytoma) and normal tissue. The primary objective is to develop machine learning models capable of accurately classifying brain cancer subtypes while identifying potential biomarkers for diagnostic and therapeutic applications.

**Aims and Objectives:**
- Analyze gene expression patterns driving tumor growth and subtype differentiation
- Develop supervised learning models for accurate brain cancer subtype classification
- Identify "Elite" genes (potential biomarkers) with highest diagnostic value
- Evaluate therapeutic insights for precision oncology applications
- Address challenges of high dimensionality and small sample size

---

## Team Members (Group 19)

| S/N | Name | Role | GitHub | Email |
|---|----------|-------------|------------|----------|
| 1 | **EIJE, OLOCHE CELESTINE** | Team Lead | [@Eije1](https://github.com/Eije1) | eijeoloche1@gmail.com |
| 2 | **AREMU, JACOBS OPEYEMI** | Member | [@aremu-jacobs](https://github.com/aremu-jacobs) | jacobsage4ril@gmail.com |
| 3 | **IKHALEA, EMMANUEL** | Member | [@DeveloperIkhalea](https://github.com/DeveloperIkhalea) | Dev.ikhalea@gmail.com |
| 4 | **DAVID, BRAINERD** | Member | [@Brainerd007](https://github.com/Brainerd007) | brainerddavid9@gmail.com |
| 5 | **EZEOKWELUME, MARY** | Member | [@obyokwelume-coder](https://github.com/obyokwelume-coder) | obyokwelume@gmail.com |
| 6 | **ITUNU, IFEOLUWA ADENIJI** | Member | [@Ife-ahav](https://github.com/Ife-ahav/Ife.git) | itunuadeniji31@gmail.com |
| 7 | **AJIBOLA, JOSHUA** | Member | [@JManBoss](https://github.com/JManBoss/joshman.github.io.git) | joshuaajibola00@gmail.com |
| 8 | **RAJI, RIDWANULLAH** | Member | [@DevRSR](https://github.com/DevRSR) | rajiridwanullah25@gmail.com |
| 9 | **SULE, WASIU AYINDE** | Member | [@Engrbolajipraise1](https://github.com/Engrbolajipraise1) | bolajipraise1@gmail.com |
| 10 | **MUHAMMED, OLATUNJI TIAMIYU** | Member | [@olatunjee9](https://github.com/olatunjee9) | tiamiyuolatunji1@gmail.com |

---

## Dataset Description

- **Source:** Gene Expression Omnibus (GEO) - Brain_GSE50161
- **Samples:** 130 patient samples
- **Features:** 54,676 gene expression probes
- **Classes:** 5 categories (4 tumor types + normal tissue)
  - Ependymoma
  - Glioblastoma
  - Medulloblastoma
  - Normal
  - Pilocytic Astrocytoma

### Why This Matters

Brain cancer remains one of the most aggressive malignancies worldwide. Different subtypes (glioblastoma vs ependymoma) require vastly different treatment approaches. Our work demonstrates that:

- **Full genome sequencing isn't necessary** - just 30 genes provide 92%+ accuracy
- **Machine learning can identify subtle genetic patterns** invisible to traditional analysis
- **Cost-effective diagnostic panels** can be developed using our elite gene signature
- **Precision oncology** becomes more accessible with targeted genetic testing


### Model Performance Evolution

| Phase | Model | Features | Accuracy |
|-------|-------|----------|----------|
| 1 | Logistic Regression | 100 | 84.62% |
| 2 | Random Forest | 100 | 88.46% |
| 3 | RFE + Random Forest | 30 | 92.31% |
| 4 | GridSearchCV Tuned | 30 | 92.31% |

### Real-World Applications

- **Clinical Diagnostics**: Develop PCR-based test panels targeting the 30 elite genes
- **Drug Discovery**: Investigate top biomarkers as therapeutic targets
- **Treatment Planning**: Faster, more accurate subtype identification
- **Research Tool**: Open-source pipeline for other cancer type analysis


