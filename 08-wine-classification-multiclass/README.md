# Wine Classification (Multi-class)

Practicing multi-class classification on the Wine dataset. Trains and compares Logistic Regression and Random Forest Classifier to predict which of 3 grape cultivars a wine sample belongs to, based on its chemical properties.

## What is covered
- Train/Test split on the Wine dataset (built-in sklearn dataset)
- Feature scaling using StandardScaler (fit on train, transform on test)
- Training a Logistic Regression classifier
- Training a Random Forest Classifier (100 trees)
- Model accuracy comparison
- Handling and resolving a ConvergenceWarning in Logistic Regression

## Concepts practiced
- Multi-class classification (predicting 1 of 3 categories, not just 2)
- Why Logistic Regression needs feature scaling, but Random Forest does not
- Why we fit the scaler only on training data, and only transform on test data (avoiding data leakage)
- Understanding why features with very different scales (like Proline vs Hue) can cause convergence issues

## Dataset
Wine dataset from scikit-learn (`load_wine`), containing chemical analysis results of wines from 3 different cultivars grown in the same region in Italy.
