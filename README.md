# 📉 Customer Churn Prediction

### 📌 Project Overview
This project uses **Machine Learning** to predict which customers are likely to leave ("churn") a telecom company. By analyzing customer data—like contract type, monthly charges, and tenure—the AI model identifies "at-risk" customers so the business can take action to keep them.

### ❓ The Problem
* **Churn:** When a customer cancels their subscription.
* **Challenge:** Finding new customers is expensive. It is cheaper to keep existing ones.
* **Goal:** Predict *who* will leave before they actually do.

### 🛠️ Technologies Used
* **Python** (Main Language)
* **Pandas** (Data Cleaning & Manipulation)
* **Scikit-Learn** (Building the AI Model)
* **Random Forest** (The Machine Learning Algorithm)
* **SMOTE** (Technique to fix imbalanced data)
* **Seaborn/Matplotlib** (Data Visualization)

### 📊 Project Workflow
1. **Data Cleaning:** Handled missing values and converted text data (e.g., "Yes/No") into numbers.
2. **EDA (Exploratory Data Analysis):** discovered that **Month-to-Month contracts** and **Electronic Check payments** have the highest churn rates.
3. **Handling Imbalance:** Used **SMOTE** to generate synthetic data because "Loyal Customers" outnumbered "Churners."
4. **Model Training:** Trained a **Random Forest Classifier** to find patterns.
5. **Prediction Interface:** Created a simple dashboard to test new customers and get a "Safe" or "Alert" prediction.

### 📈 Key Results
* The model successfully identifies high-risk customers.
* **Feature Importance** analysis showed that **Contract Type** and **Tenure** are the biggest predictors of churn.

### 🚀 How to Run
1. Open the project in **Google Colab**.
2. Upload the dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`).
