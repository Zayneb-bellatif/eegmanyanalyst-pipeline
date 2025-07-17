# ERN Analysis Pipeline

A reproducible MNE-Python pipeline for preprocessing EEG data and computing ERN components. Developed as part of the *Variability in the Analysis of an Event-Related Potential Dataset by Many Teams* study. Streamlines large-scale EEG analysis with automated quality-based subject inclusion/exclusion.

⸻

## Table of Contents
1. [Study Context](#study-context)  
2. [Features](#features)  
3. [Contributors](#contributors)  

⸻

## Study Context

The pipeline was created for the *Variability in the Analysis of an Event-Related Potential Dataset by Many Teams* study. Its goals:
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
  - `grand_average.py` — Compute grand-average ERN per condition  
  - `corr_anxiety.py` — Correlate dERN amplitude with anxiety scores  
- **Environment:** `mne_env.yml` for a ready-to-use conda environment  

⸻

## Installation

**Requirements**
- Python 3.8+  

⸻

## Contributors
Moreau Q, Bellatif Z  