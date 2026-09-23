# Breast Cancer Diagnosis

**Notebook:** [`breast_cancer.ipynb`](breast_cancer.ipynb)

## Problem
Classify breast tumors as malignant or benign from cell nucleus measurements.

## Data
[Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/dataset/17/) (UCI), loaded with `ucimlrepo`.

## Approach
- Exploratory analysis with seaborn and plotly.
- Trained a Random Forest classifier and tuned it with `GridSearchCV`.
- Evaluated with accuracy, a classification report, and a confusion matrix.

## Result
**~96–97% accuracy** (0.96 macro-F1).

---
*Group project from the Vert 2024 data trainee program. See the [main README](../README.md) for context.*
