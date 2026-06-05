# Stellar Classification Final Project

This repository contains a Jupyter notebook project for a Physics 20B final project.

## Project Summary

The notebook uses the HYG star catalog to classify stars into broad spectral classes:

- O
- B
- A
- F
- G
- K
- M

It includes:

- data loading from a public astronomy catalog
- data cleaning and label extraction from spectral type strings
- exploratory plots (including an H-R style diagram)
- a baseline machine learning classifier (Random Forest)
- model evaluation via classification metrics and confusion matrix

## Files

- `stellar_classification_project.ipynb` - main notebook
- `requirements.txt` - Python dependencies

## Run Instructions

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Open the notebook:

```bash
jupyter notebook stellar_classification_project.ipynb
```

3. Run all cells from top to bottom.

## Dataset Source

- HYG catalog (v4.1) from:
  - https://github.com/astronexus/HYG-Database

Raw CSV used in notebook:

- https://raw.githubusercontent.com/astronexus/HYG-Database/main/hyg/CURRENT/hygdata_v41.csv
