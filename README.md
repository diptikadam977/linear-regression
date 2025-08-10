# Linear Regression Analysis

## Task
This project implements **Simple & Multiple Linear Regression** on a housing dataset.

### Steps:
1. Import & preprocess the dataset (`linearregression.csv`).
2. Handle missing values and encode categorical features.
3. Train-test split (80/20).
4. Fit a **Multiple Linear Regression** model using `scikit-learn`.
5. Evaluate the model using **MAE**, **MSE**, and **R²** score.
6. Identify the feature most correlated with the target (`price`) and fit a **Simple Linear Regression**.
7. Plot results.

## Dataset
`linearregression.csv` — contains housing price data.

Target column: **price**

Top correlated numeric feature with `price`: **area**.

## Evaluation Results (Multiple Linear Regression)
- **MAE**: 970,043.40
- **MSE**: 1,754,318,687,330.66
- **R²**: 0.6529

## Files
- `linearregression.csv` — dataset
- `linear_regression_analysis.py` — script with preprocessing, training, and evaluation
- `linear_regression_analysis.ipynb` — notebook with the same code + explanations
- `README.md` — project overview

## Requirements
```
pip install pandas numpy scikit-learn matplotlib
```

## How to Run
### Script
```
python linear_regression_analysis.py
```

### Notebook
Open `linear_regression_analysis.ipynb` in Jupyter or VS Code and run cells.
