# Obesity Level Classification

**Notebook:** [`obesity_classification.ipynb`](obesity_classification.ipynb)

## Problem
Classify a person's obesity level from eating habits, physical condition, and body measurements.

## Data
[Estimation of obesity levels based on eating habits and physical condition](https://archive.ics.uci.edu/dataset/544/) (UCI).

## Approach
- Converted categorical answers into numeric features and engineered BMI.
- Compared Random Forest and XGBoost classifiers.
- Noticed training accuracy of 1.0 and checked for overfitting on a held-out split.

## Result
**97.6% accuracy** on the test set, re-verified by re-running the notebook. BMI is a strong predictor here because the target is largely defined by it; removing it is the natural next experiment.

---
*Group project from the Vert 2024 data trainee program. See the [main README](../README.md) for context.*
