# Adult Income Prediction

## What This Project Does
Predicts whether a person earns more than $50,000 per year using demographic and employment data (age, education, occupation, hours worked, etc.).

## Results (TL;DR)

| Model | Accuracy | F1 Score | ROC AUC |
|-------|----------|----------|---------|
| Logistic Regression | 84.6% | 0.640 | 0.898 |
| Random Forest | 86.1% | 0.675 | 0.911 |
| **HistGradientBoosting** | **87.2%** | **0.705** | **0.927** |

> **Best model:** HistGradientBoosting

## What I Did

| Step | Description |
|------|-------------|
| **Data Cleaning** | Handled missing values, removed duplicates, fixed formatting |
| **Feature Engineering** | One-hot encoding, log transformation for skewed features |
| **EDA** | Analyzed distributions, correlations, and income patterns |
| **Clustering** | K-means (3 clusters) visualized with PCA |
| **Models** | Logistic Regression, Random Forest, Gradient Boosting |
| **Tuning** | Grid search for hyperparameter optimization |

## Key Insights

- **Education** is the strongest predictor of high income
- **Married individuals** are 8x more likely to earn >50K than singles
- **Men** are 3x more likely to earn >50K than women
- **Capital gains** are zero for 90% of people

## Tech Stack

Python · pandas · scikit-learn · matplotlib · seaborn · Jupyter

## Author

Anastasiya Vikhrova
