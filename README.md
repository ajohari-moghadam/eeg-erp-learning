# EEG/ERP Learning with MNE-Python

This repository documents my hands-on learning of EEG/ERP analysis using
[MNE-Python](https://mne.tools), as part of my PhD in Neuroscience.
All analyses use publicly available datasets.

## Roadmap
- [x] Environment and Git setup
- [x] Loading and exploring raw EEG data
- [ ] Preprocessing
  - [x] Power spectrum and high-pass filtering
  - [x] Resampling
  - [x] Bad channel detection (visual, spectral, and robust statistics)
  - [ ] Re-referencing
- [ ] Artifact removal with ICA
- [ ] Epoching and ERP computation
- [ ] ERP component measurement and statistics

## Setup
```bash
conda env create -f environment.yml
conda activate neuro
```

On Windows, launch VS Code from the activated environment so that the
Jupyter kernel finds the environment's libraries:

```bash
conda activate neuro
cd path\to\eeg-erp-learning
code .
```

## Repository structure
- `notebooks/` – step-by-step analysis notebooks
- `src/` – reusable Python functions
- `figures/` – generated figures

## Author
**Amir Johari Moghadam** – PhD Candidate in Neuroscience
