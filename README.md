# 📊 Credit Risk Predictor (Production-Ready ML System)

An end-to-end **machine learning-powered credit risk evaluation system** designed to help financial institutions assess loan applicants with high accuracy, interpretability, and speed.

This system predicts **probability of default (PD)**, assigns **credit scores**, and classifies applicants into actionable **risk tiers**, enabling faster and more reliable lending decisions.

---

## 💡 Problem Statement

Traditional credit risk assessment is:

* Manual and time-consuming
* Prone to human bias
* Difficult to scale

This project solves that by building a **data-driven, automated risk evaluation system** that delivers consistent and explainable predictions.

---

## 🎯 Key Features

* 📊 Predicts **Probability of Default (PD)** for each applicant
* 🧮 Generates **Credit Score (300–900 range)** with risk categorization
* 🧠 Classifies users into:

  * Poor (300–499)
  * Average (500–649)
  * Good (650–749)
  * Excellent (750–900)
* ⚡ Real-time predictions via **Streamlit UI + FastAPI backend**
* 🔍 High interpretability using model coefficients and feature importance

---

## 📈 Model Performance

| Metric              | Value                         |
| ------------------- | ----------------------------- |
| Accuracy            | **92%+**                      |
| Recall (Defaulters) | **94%**                       |
| KS Statistic        | **86.2**                      |
| Model Type          | Logistic Regression + XGBoost |

👉 Strong recall ensures **better defaulter detection**
👉 High KS indicates **clear separation between good vs bad borrowers**

---

## 🧠 ML Approach

* Performed **EDA & feature engineering** on financial data
* Engineered high-impact features:

  * Loan-to-Income Ratio
  * Credit Utilization Ratio
  * Delinquency Ratio
* Applied **SMOTE-Tomek** for class imbalance handling
* Used **Optuna for hyperparameter tuning**
* Benchmarked using:

  * AUC
  * Gini
  * KS Statistic
  * Recall

---

## 🏗️ System Architecture

* **Frontend:** Streamlit (interactive UI for loan officers)
* **Backend:** FastAPI (API-based prediction service)
* **ML Stack:**

  * Python, Pandas, NumPy
  * Scikit-learn, XGBoost
* **Deployment:** Streamlit Cloud

---

## ⚙️ Input Features

* Applicant demographics (age, income)
* Loan details (amount, tenure, type)
* Credit behavior:

  * Delinquency rate
  * Credit utilization
  * Open loan accounts
* Categorical inputs:

  * Residence type
  * Loan purpose

---

## 🔍 Explainability

* Logistic Regression coefficients used for **model transparency**
* Helps business stakeholders:

  * Understand risk drivers
  * Improve lending strategies
  * Build trust in ML predictions

---

## 🧩 Project Structure

```
ml-project-credit-risk-modelling/
│
├── artifacts/
│   └── model_data.joblib
│
├── backend/
│   ├── logging_setup.py
│   ├── prediction.py
│   └── server_cr.py
│
├── main.py
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/NISHU8875/Credit_Risk_Predictor
cd ml-project-credit-risk-modelling
pip install -r requirements.txt
streamlit run main.py
```

---

## 🌐 Live Demo

👉 https://ml-project-credit-riskprediction-model-nishu-om.streamlit.app/

---

## 🎯 Business Impact

* ⏱️ Reduced loan decision time significantly
* 🎯 Improved risk prediction accuracy and consistency
* 📉 Enhanced defaulter identification (high recall)
* 📊 Enabled data-driven lending decisions

---

## 🧠 Skills Demonstrated

* Machine Learning (Logistic Regression, XGBoost)
* Feature Engineering & Model Optimization
* Model Evaluation (AUC, KS, Gini, Recall)
* Backend Development (FastAPI)
* UI Development (Streamlit)
* End-to-End ML System Design

---

## 🔥 Why This Project Stands Out

This is not just a model — it is a **production-ready ML system** combining:

* Strong statistical modeling
* Real-world financial metrics
* End-to-end deployment
* Business-focused evaluation

---

## 📌 Author

**NISHU KUMAR**
AI/ML Engineer | IIT Delhi & IIT Jodhpur
Specializing in LLMs, RAG, and Production AI Systems

## Live App

Check out the **live demo**:  
[Streamlit Cloud Link](#) *(https://ml-project-credit-riskprediction-model-nishu-om.streamlit.app/)*




