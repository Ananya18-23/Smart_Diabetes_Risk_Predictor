# 🏥 Diabetes Prediction System

### 📌 Overview
An AI-powered Risk Assessment Tool designed to predict the likelihood of diabetes based on clinical parameters. It uses Machine Learning models trained on historical health metrics to evaluate risk profiles instantly through an interactive web-based dashboard.

### 🚀 Features
* **🧠 Advanced ML Diagnostics:** Preprocessing pipeline using Support Vector Machine (SVM) and Random Forest Classifier for highly dependable risk classification.
* **📊 Interactive Analytical Dashboard:** User-friendly web interface with responsive sidebars, custom input forms, and dynamic visual status gauges.
* **🔍 Smart Risk Metrics:** Automated assessment that highlights specific physical risk factors alongside positive biological indicators based on clinical input ranges.
* **💡 Actionable Clinical Insights:** Instant dynamic suggestions and healthcare recommendations mapped accurately to the evaluation outcome.

### 🛠️ Tech Stack
* **Python** (Core Development)
* **Streamlit** (Web Application & Interactive UI)
* **Pandas & NumPy** (Data Preprocessing & Array Manipulations)
* **Scikit-Learn** (Standard Scaler, SVM Core, and Evaluation Metrics)
* **Joblib** (Model Serialization & Deployment Pipeline)
* **Plotly** (Visual Gauges & Quantitative Charts)

### 📂 Project Structure
```bash
├── diabetes.prediction.ipynb  # Jupyter Notebook for EDA, Preprocessing, & Model Training
├── app.py                     # Streamlit Web Application Source Code
├── diabetes.csv               # PIMA Indians Dataset (Patient Clinical Records)
├── diabetes_model.pkl         # Trained Machine Learning Model (Serialized File)
├── scaler_svm.pkl             # Fitted StandardScaler Object for input normalization
└── README.md                  # Project Documentation
