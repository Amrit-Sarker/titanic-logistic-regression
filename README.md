# 🚢 Titanic Survival Prediction — Logistic Regression Baseline

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Kaggle Score](https://img.shields.io/badge/Kaggle%20Score-0.77033-brightgreen)

## 🧠 Project Overview

This project implements a **supervised machine learning pipeline** to predict passenger survival in the Titanic disaster using the Kaggle Titanic dataset.

The objective is to build a strong, interpretable baseline model and understand the socio-demographic factors influencing survival outcomes.

This work follows a complete data science workflow:  
**data preprocessing → feature engineering → model training → evaluation → submission**

---

## 🎯 Problem Definition

The Titanic disaster provides a classic binary classification problem:

> Predict whether a passenger survived or not based on available features.

Formally:

- Target variable: `Survived ∈ {0, 1}`  
- Task type: Binary classification  

---

## 📊 Dataset

Source: Kaggle Titanic Competition

Key attributes:

- Passenger class (Pclass)
- Sex
- Age
- SibSp (siblings/spouses aboard)
- Parch (parents/children aboard)
- Fare
- Embarked (port of embarkation)

Missing values were carefully handled using statistically sound imputation strategies.

---

## ⚙️ Methodology

### 🔹 Data Preprocessing
- Missing value imputation (Age, Embarked)
- Encoding categorical variables (One-Hot Encoding)
- Feature selection for interpretability and performance

### 🔹 Model
- Logistic Regression (Baseline linear classifier)
- Chosen for:
  - Interpretability
  - Efficiency
  - Strong baseline performance on tabular data

### 🔹 Training Strategy
- Train-validation split using scikit-learn
- Model trained on processed feature matrix
- Evaluation using accuracy metric

---

## 📈 Results

- **Model:** Logistic Regression  
- **Kaggle Public Score:** ⭐ **0.77033**

This score demonstrates a strong baseline performance without advanced feature engineering or ensemble methods.

---

## 🔍 Key Insights

- Gender is the most influential survival predictor
- Simple linear models can perform competitively with proper preprocessing

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook 

---

## 🚀 Future Improvements

- Feature engineering (Title extraction, Family size, Age bins)
- Ensemble models (Random Forest, XGBoost, LightGBM)
- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Cross-validation for robustness
- Model stacking for performance boost

---

## 🏁 Conclusion

This project demonstrates how a **well-structured machine learning pipeline** can achieve strong predictive performance even with a simple model. It emphasizes that data preprocessing and feature representation often matter more than model complexity.

---

## 👨‍💻 Author

**Amrit Sarker**  
Applied Statistics and Data Science,  
University of Dhaka

---
