# Prognostic Modeling of Conversion from Mild Cognitive Impairment to Alzheimer’s Disease

## Overview

This repository contains documentation and reproducibility materials for the ongoing project:

**Prognostic Modeling of Conversion from Mild Cognitive Impairment to Alzheimer’s Disease Using Cognitive, Functional, and CSF Biomarkers in ADNI**

The study evaluates time to conversion from mild cognitive impairment (MCI) to Alzheimer’s disease (AD) using baseline demographic, cognitive, functional, genetic, and cerebrospinal fluid (CSF) biomarkers from the Alzheimer’s Disease Neuroimaging Initiative (ADNI). External validation using the Australian Imaging, Biomarkers and Lifestyle (AIBL) study is planned.

## Study Objectives

- Evaluate associations between baseline predictors and time to conversion from MCI to AD.
- Compare conventional and machine-learning survival approaches.
- Assess discrimination, prediction error, risk stratification, and clinical utility.
- Examine model interpretability and external generalizability.

## Methods

The project includes:

- Kaplan–Meier estimation and log-rank testing
- Cox proportional hazards regression
- Elastic Net Cox regression
- Random survival forest
- Gradient-boosted Cox modeling with XGBoost
- Harrell’s concordance index
- Time-dependent AUC
- IPCW Brier scores
- Decision curve analysis
- SHAP-based model interpretation
- External validation using AIBL data (planned)

## Repository Structure

```text
R/          Analysis scripts
figures/    Generated figures
 tables/     Generated tables
 docs/       Project documentation and manuscript materials
 data/       Data-access instructions only; no participant-level data
```

## Data Availability

Participant-level ADNI and AIBL data are not included in this repository. Researchers must obtain access directly from the respective data providers and comply with all applicable data-use agreements. Do not commit raw, derived, or identifying participant-level data to this repository.

## Project Status

Manuscript in preparation. The repository will be updated as the analysis, external validation, and manuscript are finalized.

## Author

Salah Uddin  
M.S. in Applied Statistics, Minnesota State University, Mankato
