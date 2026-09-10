# 🫀 Heart Disease Prediction using Machine Learning

Predicting the presence of heart disease from clinical data using **Logistic Regression** and proper feature selection.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-80.33%25-brightgreen)

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. This project builds a machine learning model that can predict whether a patient is likely to have heart disease based on medical attributes.

**Dataset**: Classic UCI Heart Disease dataset (303 patients, 14 features)

**Final Model Accuracy**: **80.33%**

---

## 🛠️ Techniques Used

- Exploratory Data Analysis (EDA)
- Outlier detection using boxplots
- Multicollinearity handling using **Variance Inflation Factor (VIF)**
- Feature selection (removed high VIF features)
- Logistic Regression
- Model evaluation (Accuracy + Confusion Matrix)

---

## 📊 Features After Selection

After removing features with high multicollinearity, the final model used:

| Feature   | Description                          |
|-----------|--------------------------------------|
| sex       | Gender (1 = male, 0 = female)        |
| fbs       | Fasting blood sugar > 120 mg/dl      |
| restecg   | Resting electrocardiographic results |
| exang     | Exercise induced angina              |
| oldpeak   | ST depression induced by exercise    |
| slope     | Slope of the peak exercise ST segment|
| ca        | Number of major vessels              |

**Dropped features** (high VIF): `cp`, `trestbps`, `chol`, `thalach`, `thal`

---

## 📈 Results

- **Accuracy**: 80.33%
- **Confusion Matrix**: