# Stroke-risk-prediction-ml
Developed a machine learning system to predict early stroke risk using patient data. Used classification models and SHAP for explainability to highlight key risk factors. Aimed to support healthcare professionals in making informed, data-driven decisions.
# 🧠 Early Stroke Risk Prediction System Using Machine Learning 

This project builds a machine learning pipeline to predict the early risk of stroke based on patient health indicators. It leverages a variety of machine learning models techniques to interpret model predictions and provide healthcare professionals with insights into key risk factors.

---

## 📊 Dataset

The dataset used in this project is publicly available and includes the following features:

- `age`
- `hypertension`
- `heart_disease`
- `ever_married`
- `work_type`
- `Residence_type`
- `avg_glucose_level`
- `bmi`
- `smoking_status`
- `stroke` (Target variable)

It is designed to help predict the likelihood of a stroke based on a combination of demographic, clinical, and lifestyle information.

---

## 🎯 Project Objectives

- Clean and preprocess the dataset (handle missing values, encode categorical variables).
- Visualize data distributions and relationships using various plots.
- Train multiple machine learning models:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - XGBoost Classifier
- Evaluate each model using classification metrics.
- Apply **SHAP (SHapley Additive Explanations)** for model interpretability.
- Identify and visualize the most influential features contributing to stroke risk.

---

## 🧰 Libraries & Tools Used

| Category            | Libraries/Tools                           |
|---------------------|--------------------------------------------|
| Data Handling       | `pandas`, `numpy`                          |
| Data Visualization  | `matplotlib`, `seaborn`                    |
| Machine Learning    | `scikit-learn`, `xgboost`                  |
| Explainable AI      | `shap`                                     |
| Development         | `Jupyter Notebook`                         |

---

## 📈 Model Evaluation Metrics

Each model is evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**
- **ROC-AUC Curve**

---

## 📌 Key Takeaways

- The project demonstrates how various ML models perform on stroke prediction tasks.
- SHAP analysis helps explain which features (e.g., age, hypertension, glucose level) are most influential in the model’s decision-making process.
- Feature importance and visualization aid in clinical decision support.

---

## 🚀 How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/gauravroy061/stroke-risk-prediction.git
   cd stroke-risk-prediction
