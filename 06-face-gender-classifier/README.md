# Face-Based Gender Classifier

**Notebook:** [`face_gender_classifier.ipynb`](face_gender_classifier.ipynb)

## Problem
Classify face photos into two labeled groups using facial embeddings.

## Data
Public face image dataset from Kaggle (~480 images in two labeled folders). Not redistributed here.

## Approach
- Extracted 128-dimensional face encodings with `face_recognition`.
- Trained a Support Vector Machine (SVC) on the encodings.
- Inspected predictions with a confusion matrix.

## Result
99% on the full dataset (232/233 and 248/251 correct). The evaluation included training images, so this is optimistic; a proper held-out split is the next improvement. Automated gender inference from faces carries known bias and ethics concerns, and this was a learning exercise only.

---
*Group project from the Vert 2024 data trainee program. See the [main README](../README.md) for context.*
