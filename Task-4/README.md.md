
# Logistic Regression Binary Classification - Breast Cancer Dataset

## Overview
This project demonstrates **Logistic Regression** for binary classification using the **Breast Cancer Wisconsin Dataset** from Scikit-learn.

## Steps Performed
1. Loaded and cleaned the dataset.
2. Split data into training and testing sets (80/20).
3. Standardized features using `StandardScaler`.
4. Trained a Logistic Regression model.
5. Evaluated performance using:
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC Score and Curve
6. Visualized the **Sigmoid Function** and **ROC Curve**.

##  Results
- **Accuracy:** 0.9737
- **ROC-AUC Score:** 0.9974

### Confusion Matrix
[[41  2]
 [ 1 70]]

### Classification Report
| Metric | Precision | Recall | F1-score | Support |
|---------|------------|---------|-----------|----------|
| Class 0 | 0.98 | 0.95 | 0.96 | 43 |
| Class 1 | 0.97 | 0.99 | 0.98 | 71 |

##  Visualizations
- `ROC_Curve_LogisticRegression.png`
- `Sigmoid_Function.png`

