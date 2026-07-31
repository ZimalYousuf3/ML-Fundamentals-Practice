# Breast Cancer Classification

Practicing classification modeling on the Breast Cancer Wisconsin dataset. Trains and compares Logistic Regression and Random Forest Classifier to predict whether a tumor is malignant or benign, and evaluates performance using confusion matrix, precision, recall, and F1 score.

## What is covered
- Train/Test split on Breast Cancer Wisconsin dataset (built-in sklearn dataset)
- Training a Logistic Regression classifier
- Training a Random Forest Classifier (100 trees)
- Model accuracy comparison
- Confusion Matrix (TP, TN, FP, FN) and visualization
- Precision, Recall, and F1 score using classification_report

## Concepts practiced
- Difference between regression and classification
- Why accuracy alone can be misleading, especially on imbalanced/medical data
- Understanding Confusion Matrix (True Positive, True Negative, False Positive, False Negative)
- Difference between Precision (avoiding false alarms) and Recall (avoiding missed cases)
- Why Recall matters more than Precision in medical diagnosis contexts

## Key result
Random Forest achieved slightly higher accuracy (95.6%) than Logistic Regression (93.9%). Recall for the malignant class was 0.95, meaning only 2 out of 41 actual malignant cases were missed.

## Dataset
Breast Cancer Wisconsin dataset from scikit-learn (`load_breast_cancer`)
