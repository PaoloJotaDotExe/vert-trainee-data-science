# Penguin Species Classification

**Notebook:** [`penguins_classification.ipynb`](penguins_classification.ipynb)

## Problem
Predict a penguin's species (Adélie, Chinstrap, Gentoo) from body measurements.

## Data
[Palmer Penguins](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data) (`penguins_lter.csv`).

## Approach
- Exploratory analysis of each variable and renamed columns for clarity.
- Handled missing values and encoded categorical features.
- Trained a Random Forest classifier and evaluated it with a confusion matrix.

## Result
**98% accuracy** on the test set (0.98 macro-F1), re-verified by re-running the notebook.

---
*Group project from the Vert 2024 data trainee program. See the [main README](../README.md) for context.*
