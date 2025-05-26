# Stroke-risk-prediction-ml
Developed a machine learning system to predict early stroke risk using patient data. Used classification models and SHAP for explainability to highlight key risk factors. Aimed to support healthcare professionals in making informed, data-driven decisions.
# 🧠 Early Stroke Risk Prediction System Using Machine Learning

This project focuses on building a machine learning-based system to predict the likelihood of stroke in individuals using health-related data. The model is trained on a structured dataset and saved using Python’s `pickle` library for future use or deployment.

---

## 📊 Dataset

The dataset includes patient health records with the following features:
- Age
- Gender
- Hypertension
- Heart Disease
- Marital Status
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status
- Stroke (Target Variable)

---

## 🎯 Project Objectives

- Preprocess healthcare data (cleaning, encoding, and handling missing values).
- Train classification models to predict stroke risk.
- Evaluate models using metrics such as accuracy, precision, recall, and F1-score.
- Save the best-performing model using `.pkl` for later use without retraining.

---

## 🧰 Libraries Used

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib` & `seaborn` – Data visualization
- `scikit-learn` – Machine learning models and evaluation
- `xgboost` – Gradient boosting classifier
- `pickle` – Model serialization

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/stroke-risk-prediction.git
   cd stroke-risk-prediction






