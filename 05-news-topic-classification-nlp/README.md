# News Topic Classification (NLP)

**Notebook:** [`news_classification.ipynb`](news_classification.ipynb)

## Problem
Assign each news article (in Portuguese) to one of 10 topics, such as ecology, education, culture, and solidarity.

## Data
1,092 labeled news articles (title + content) with 10 imbalanced classes.

## Approach
- Text cleaning, stopword removal, and keyword extraction with NLTK and flashtext.
- TF-IDF vectorization.
- SMOTE to balance the minority classes.
- Random Forest classifier, evaluated with a classification report.

## Result
**88% accuracy and 0.88 macro-F1** across 10 classes.

---
*Group project from the Vert 2024 data trainee program. See the [main README](../README.md) for context.*
