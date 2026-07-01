# Regression Projects

## Overview
- A collection of three notebooks illustrating core regression techniques:
  - Practical Simple Linear Regression.ipynb
  - Multiple Linear Regression- Economics Dataset.ipynb
  - Polynomial Regression Implementation.ipynb
- Datasets included: height-weight.csv, economic_index.csv.

## What You’ll Learn
- Simple Linear Regression: modeling one predictor and interpreting slope/intercept.
- Multiple Linear Regression: handling multiple predictors and multicollinearity checks.
- Polynomial Regression: introducing nonlinearity with polynomial features and comparing fit.

## Setup
```bash
cd "Regression Projects"
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Run the Notebooks
```bash
jupyter notebook
```
- Open each notebook and run cells sequentially.
- Ensure file paths in the data loading cells point to the provided CSVs in this folder.

## Typical Workflow
1. Explore distributions and relationships (scatter plots, correlation).
2. Split train/test and fit baseline models.
3. Evaluate with MAE/MSE/RMSE and R².
4. Visualize fitted lines/curves and residuals.
5. Compare models and discuss bias–variance trade-offs.

## Tips
- Standardize features where appropriate, especially for polynomial terms of high degree.
- Use cross-validation and regularization (Ridge/Lasso) when moving beyond demonstration.

