# ERN Analysis Pipeline

A reproducible MNE-Python pipeline for preprocessing EEG data and computing ERN components. Developed as part of the *EEG Many Analysts* study https://www.coscience-personality.com/manyanalysts.
⸻

## Table of Contents
1. [Study Context](#study-context)  
2. [Features](#features)  
3. [Contributors](#contributors)  

⸻

## Study Context

The pipeline was created for the *EEG Many Analysts* study. Its goals:
- Provide a full preprocessing and analysis routine for EEG data (on Flanker task)
- Compute difference ERN (dERN) waveforms per condition  
- Correlate dERN amplitude to anxiety measure

All analysis steps are captured on the Jupyter Notebook and can be adapted for general ERP workflows.

⸻

## Features
- **Automated Preprocessing:** filtering, ASR, ICA-based artifact rejection, and epoching via MNE-Python  
- **Quality Control:** Automatic subject inclusion/exclusion using a composite quality metric  
- **ERN Detection:** dERN computation across congruency conditions 
- **Notebooks & Scripts:**  
  - Master Jupyter Notebook (`ern_pipeline.ipynb`)  
  - `grand_average.ipynb` — Compute grand-average ERN per condition  
  - `corr_anxiety..ipynb` — Correlate dERN amplitude with anxiety scores  
⸻

## Contributors
Moreau Q, Bellatif Z  
