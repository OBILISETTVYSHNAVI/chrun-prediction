# chrun-prediction
Customer Churn Predictor


# 📉 Customer Churn Predictor – Streamlit App (Colab Compatible)

This project is a machine learning-based churn prediction system that allows users to input customer details and receive real-time churn predictions via a Streamlit web interface.

It runs entirely in **Google Colab**, with deployment handled via **ngrok**, so no setup is needed on your local machine.

---

## 🚀 Open in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OBILISETTVYSHNAVI/https://github.com/OBILISETTVYSHNAVI/chrun-prediction/blob/main/churn_predictor_colab.ipynb)

---

## 🧠 Model Overview

- **Algorithm**: Random Forest Classifier
- **Dataset**: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Features Used**:
  - Gender
  - Senior Citizen
  - Partner
  - Dependents
  - Tenure
  - Monthly Charges
  - Total Charges
  - Contract Type
  - Paperless Billing
  - Payment Method

---

## 📦 Project Files

```text
├── churn_predictor_colab.ipynb     # Google Colab notebook (main app + training + deployment)
├── model.pkl                       # Trained model file (generated in Colab)
├── README.md                       # Project overview and instructions
├── requirements.txt                # Required Python packages
