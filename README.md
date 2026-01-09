# food-predictor (CSC311)
This project implements a supervised machine learning model to predict a food item from structured survey data. The model was developed as part of **CSC311: Introduction to Machine Learning** and focuses on end to end ML workflows, including data preprocessing, feature engineering, and model evaluation.

The final model achieved **84% accuracy on a held out test set**.

---

## Problem Statement
Given survey responses describing pricing expectations, contextual settings, personal associations, and free text inputs, the goal is to predict the food category associated with each response.

This problem involves both **categorical and numerical features**, as well as **text based inputs**, requiring careful feature design and preprocessing.

---

## Approach
- Preprocessed survey data by handling missing values and encoding categorical responses
- Engineered features from:
  - Multiple-choice questions
  - Numerical price ranges
  - Free text movie associations using one-hot encoding
- Implemented a **multiclass logistic regression model**
- Evaluated performance using accuracy on a held-out test set

---

## Results
- **Test Accuracy:** 84%
- The model generalizes well to unseen data and demonstrates the effectiveness of feature engineering on structured survey datasets.

---
