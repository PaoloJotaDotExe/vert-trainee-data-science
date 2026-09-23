# Vert Trainee Program: Data Science Projects (2024)

Machine learning, NLP, computer vision, optimization, and data analysis projects built at [Vert](https://www.vert.com.br/) in **2024**, as part of the company's data trainee cohort (*Ninjas Vert 2024*).

> **Group work.** Every project here was developed **as a team** by the trainee cohort, not by me alone. I'm publishing them with that context to document what we learned together and the part I played in it.

## The program

I joined Vert in **November 2023**. Throughout **2024** I rotated through several roles in the company's data area: **requirements analyst, BI analyst, data scientist, and data engineer**. I spent the most time in data science and data engineering. That same year our trainee cohort was mentored in data science and modeling by **Thiago Russo**, a reference for me in the data field. Learning from him was an honor.

In **2025** I was **hired as a data scientist**, the role I held until **May 2026**.

## Projects

Only projects whose core pipeline (data → model → evaluation) runs end to end with solid results are included. Metrics are on held-out test data unless noted. For portfolio publication, I re-ran the notebooks where possible to confirm the numbers.

| # | Project | Techniques | Result | How it was checked |
|---|---|---|---|---|
| 01 | [MNIST digit recognition](01-mnist-digit-recognition) | TensorFlow, Keras, neural networks | **97.6% test accuracy** | `model.evaluate()` output |
| 02 | [Penguin species classification](02-penguin-species-classification) | Random Forest, EDA | **98% accuracy** | re-run |
| 03 | [Obesity level classification](03-obesity-level-classification) | Random Forest, XGBoost, feature engineering | **97.6% accuracy** | re-run |
| 04 | [Breast cancer diagnosis](04-breast-cancer-diagnosis) | Random Forest, GridSearchCV | **96.7% accuracy** | re-run |
| 05 | [Face-based gender classifier](05-face-gender-classifier) | face_recognition embeddings, SVM | 99% on the full dataset* | saved output |
| 06 | [Titanic survival](06-titanic-survival) | Random Forest, feature engineering | 81% accuracy | saved output |
| 07 | [Sudoku solver](07-sudoku-solver-linear-programming) | Integer linear programming (PuLP) | optimal solution | re-run |
| 08 | [N-Queens solver](08-n-queens-solver-linear-programming) | Integer linear programming (PuLP) | optimal solution | re-run |
| 09 | [Spotify tracks EDA](09-spotify-eda) | pandas, seaborn, Random Forest regressor | exploratory analysis | saved output |
| 10 | [Mental health in Brazil EDA](10-mental-health-brazil-eda) | pandas, SQL (sqlite3), seaborn | exploratory analysis | saved output |
| 11 | [Extras](11-extras) | Monty Hall simulation, Zipf's law, airport routes | small exercises | saved output |

\* Evaluated on the whole dataset, training images included, so the number is optimistic. A held-out evaluation is a planned improvement.

## Notes

- **Data.** Datasets come from public sources (Kaggle, UCI, Our World in Data, Keras). They are linked in each project instead of redistributed. Projects that used real personal, clinical, or document data were **left out on purpose**.
- **Notebooks.** They were written in Google Colab, so paths like `/content/...` point to Colab storage. Upload the dataset there, or change the path, to run them.
- **Language.** Notebook comments are mostly in Portuguese; the documentation is in English.
