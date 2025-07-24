# Random-Forest-vs-Gradient-Boosting-Sklearn-Based-Comparison-on-Breast-Cancer-Dataset
ensemble learning methods to classify breast cancer cases using the Wisconsin Breast Cancer Dataset from scikit-learn. It compares two powerful ensemble techniques—Random Forests and Gradient Boosting—highlighting their strengths, accuracy, ROC curves, and feature importance insights.
# Breast Cancer Classification Using Ensemble Learning

## Overview
This project applies ensemble learning models to classify breast cancer tumors (malignant vs benign) using the popular Wisconsin Breast Cancer Dataset. By comparing **Random Forest** and **Gradient Boosting**, the notebook analyzes their predictive power, performance metrics, and feature importance.

## Techniques Used
- 🧠 Random Forest Classifier (Bagging-based)
- 🚀 Gradient Boosting Classifier (Boosting-based)
- 📊 Confusion Matrix & ROC Curve Analysis
- 📈 Feature Importance Visualization

## Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- Features: 30 real-valued tumor characteristics
- Target: Binary classification (0 = malignant, 1 = benign)

## Results Summary
| Model             | Accuracy | ROC AUC | Highlights                                  |
|------------------|----------|--------|---------------------------------------------|
| Random Forest     | 96.5%    | 1.00   | Automatic feature selection, low overfitting |
| Gradient Boosting | 95.6%    | 1.00   | Sequential learning, better class boundaries |

## Why Use Ensemble Methods?
Ensemble methods combine multiple models to improve predictive performance and robustness:
- ✅ Random Forest reduces overfitting via decorrelated trees.
- 🔁 Gradient Boosting focuses on correcting previous mistakes for strong generalization.

## Installation
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
