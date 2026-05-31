# California Housing Price Prediction

A supervised machine learning project that predicts California house prices using Linear Regression, built on the California Housing dataset from scikit-learn.

---

## Overview

This project builds and evaluates a Linear Regression model to predict median house prices across California districts. It covers the full ML workflow: data loading, exploratory data analysis, feature correlation, model training, and evaluation.

---

## Dataset

**California Housing Dataset** — sourced from `sklearn.datasets.fetch_california_housing()`

| Feature | Description |
|---|---|
| MedInc | Median income in block group |
| HouseAge | Median house age in block group |
| AveRooms | Average number of rooms per household |
| AveBedrms | Average number of bedrooms per household |
| Population | Block group population |
| AveOccup | Average number of household members |
| Latitude | Block group latitude |
| Longitude | Block group longitude |
| **price** | **Target — median house value (in $100,000s)** |

---

## Workflow

1. Load dataset and convert to a pandas DataFrame
2. Exploratory Data Analysis (EDA) — descriptive statistics and correlation matrix
3. Visualise feature correlations using a heatmap (seaborn)
4. Split data into training and test sets (80/20)
5. Train a Linear Regression model
6. Evaluate on training data using R² and Mean Absolute Error
7. Visualise predicted vs actual prices with a scatter plot

---

## Results

| Metric | Value |
|---|---|
| R² Score | Evaluated on training set |
| Mean Absolute Error | Evaluated on training set |
| Model Coefficients | Printed per feature |
| Intercept | Printed |

---

## Technologies Used

- Python
- NumPy
- pandas
- matplotlib
- seaborn
- scikit-learn

---

## How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook Task-1.ipynb
```

The dataset is fetched automatically via scikit-learn — no manual download required.
