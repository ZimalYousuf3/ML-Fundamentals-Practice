# California Housing Regression Comparison

Practicing regression modeling on the California Housing dataset. Trains and compares a Linear Regression model against a Random Forest Regressor to predict median house value, and analyzes which features matter most.

## What is covered
- Train/Test split (80/20) on California Housing dataset
- Training a Linear Regression model
- Training a Random Forest Regressor (100 trees)
- Evaluating both models using MSE, RMSE, and R2 score
- Comparing model performance (Random Forest outperforms Linear Regression)
- Feature importance analysis using Random Forest

## Concepts practiced
- Difference between regression and classification
- Why tree-based models (Decision Tree, Random Forest) do not require feature scaling
- Understanding and interpreting MSE, RMSE, and R2 score
- Understanding feature importance from Random Forest
- Comparing multiple models to pick the better one

## Key result
Random Forest performed better than Linear Regression (higher R2, lower RMSE). Median Income (MedInc) was found to be the most important feature in predicting house value.

## Dataset
California Housing dataset from scikit-learn (`fetch_california_housing`)
