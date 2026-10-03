# EEG/ERP Learning with MNE-Python

This repository documents my hands-on learning of EEG/ERP analysis using
[MNE-Python](https://mne.tools), as part of my PhD in Neuroscience.
All analyses use publicly available datasets.

## Roadmap
- [x] Environment and Git setup
- [x] Loading and exploring raw EEG data
- [ ] Preprocessing: filtering, re-referencing, bad channels
- [ ] Artifact removal with ICA
- [ ] Epoching and ERP computation
- [ ] ERP component measurement and statistics

## Setup
conda env create -f environment.yml
conda activate neuro

## Repository structure
- `notebooks/` – step-by-step analysis notebooks
- `src/` – reusable Python functions
- `figures/` – generated figures

## Author
**Amir Johari Moghadam** – PhD Candidate in Neuroscience
