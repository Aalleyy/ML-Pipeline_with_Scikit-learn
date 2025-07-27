# Telco Customer Churn Prediction - End-to-End ML Pipeline

This project builds a **reusable, production-ready machine learning pipeline** using **Scikit-learn's Pipeline API** to predict customer churn using the **Telco Customer Churn Dataset**.

---

## Objective

- Predict whether a customer will churn using historical data.
- Build a **modular pipeline** that handles preprocessing, modeling, and tuning.
- Export the final pipeline for production deployment.

---

## Tech Stack

- Python
- Scikit-learn
- Pandas
- Joblib

---

## Dataset

- **Name:** Telco Customer Churn
- **Source:** Kaggle
- **Target Column:** `Churn` (Yes/No)

---

## Features & Workflow

### Data Preprocessing
- Numeric & categorical feature handling
- Imputation of missing values
- Standard Scaling for numeric data
- One-hot encoding for categorical data

### Machine Learning Models
- Logistic Regression
- Random Forest Classifier

### Model Selection
- `GridSearchCV` for hyperparameter tuning

### Production Readiness
- Full Scikit-learn pipeline
- Model export using `joblib`

### Exported Artifacts
`churn_pipeline.pkl` – Complete pipeline with preprocessing + best model

Can be reused in production using joblib.load(...)

---

## Future Improvements

- Add Streamlit-based demo app

- Integrate SHAP for explainability

- Add CI pipeline for automated testing

---

## Acknowledgments
Dataset hosted on Kaggle ML-Pipeline_with_Scikit-learn
