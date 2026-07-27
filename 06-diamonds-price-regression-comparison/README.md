# Diamonds Price Regression Comparison

Practicing regression modeling on the Diamonds dataset. Trains and compares a Linear Regression model against a Random Forest Regressor to predict diamond price, and analyzes which features matter most.

## What is covered
- One-hot encoding of categorical columns (cut, color, clarity)
- Train/Test split (80/20) on the Diamonds dataset
- Training a Linear Regression model
- Training a Random Forest Regressor (100 trees)
- Evaluating both models using MSE, RMSE, and R2 score
- Comparing model performance
- Feature importance analysis using Random Forest

## Concepts practiced
- One-hot encoding text/categorical columns before modeling
- Why tree-based models (Decision Tree, Random Forest) do not require feature scaling
- Understanding and interpreting MSE, RMSE, and R2 score
- Understanding feature importance from Random Forest
- Comparing multiple models to pick the better one

## Key result
Random Forest performed better than Linear Regression (higher R2, lower RMSE). Carat was found to be the most important feature in predicting diamond price.

## Dataset
Diamonds dataset from seaborn (`sns.load_dataset('diamonds')`)
