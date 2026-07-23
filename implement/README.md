# Heart Disease Prediction - ML Model Comparison

This folder contains multiple machine learning models applied to the **`heart.csv`** dataset, which holds patient health records used to predict the presence of heart disease. The goal is to build, evaluate, and compare different classification algorithms on the same dataset.

## Dataset

- **File:** `heart.csv`
- **Description:** Contains patient medical attributes (e.g. age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, max heart rate, etc.) along with a target column indicating presence/absence of heart disease.
- **Target variable:** `target` (1 = heart disease present, 0 = no heart disease) — rename based on your actual column name.

## Models Implemented

| Algorithm | File | Notes |
|---|---|---|
| K-Nearest Neighbors | `knn_heart.py` | Distance-based classification |
| Logistic Regression | `logistic_heart.py` | Linear probabilistic classifier |
| Naive Bayes | `naive_bayes_heart.py` | Probabilistic classifier based on Bayes' theorem |

## Workflow

1. **Data Loading & Cleaning** — Load `heart.csv`, handle missing values, check data types
2. **Exploratory Data Analysis (EDA)** — Visualize feature distributions, correlations with target
3. **Preprocessing** — Feature scaling/normalization, train-test split
4. **Model Training** — Fit KNN, Logistic Regression, and Naive Bayes separately
5. **Evaluation** — Compare models using accuracy, precision, recall, F1-score, confusion matrix

## Model Comparison

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| KNN | 0.93 | 0.92| 0.95 | 0.93 |
| Logistic Regression | 0.79 | 0.75 | 0.87 | 0.81 |
| Naive Bayes | 0.80 | 0.75 | 0.89 | 0.81 |

---
