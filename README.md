# Telecom Customer Churn Analysis

## 📌 Project Overview
This project analyzes a 7,043-record dataset to uncover the key drivers behind telecom customer churn. Through Exploratory Data Analysis (EDA) and data visualization, this notebook identifies customer segments that are most likely to cancel their subscriptions and provides insights into retention strategies.

## 📊 Key Insights
* **Overall Churn:** The baseline churn rate for the dataset is 26.54%.
* **Demographics:** Senior citizens represent a comparatively higher percentage of churned customers.
* **Service Gaps:** Churn rates are noticeably higher among customers who do not have access to or utilize services like Tech Support, Online Backup, and Streaming TV. 
* **Retention Drivers:** Customers who stay tend to have Phone Service, DSL Internet, and Online Security enabled.

## 🛠️ Tools & Libraries Used
* **Python 3**
* **Pandas** (Data manipulation and cleaning)
* **Matplotlib & Seaborn** (Data visualization)

## 📂 Dataset
The dataset (`Customer Churn.csv`) contains 21 features, including:
* Demographic details (Gender, SeniorCitizen, Partner, Dependents)
* Account information (Tenure, Contract type, PaymentMethod, MonthlyCharges, TotalCharges)
* Service subscriptions (InternetService, OnlineSecurity, TechSupport, etc.)
* Target Variable: `Churn` (Yes/No)

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`pip install pandas matplotlib seaborn`).
3. Open `Telecom.ipynb` in Jupyter Notebook or VS Code to view the analysis and visualizations.
