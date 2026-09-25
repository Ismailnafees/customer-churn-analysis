# Customer Churn Analysis & Prediction

## 📊 Project Overview

This project analyzes customer churn data to identify customer behavior patterns, churn trends, and factors associated with customer attrition.

The project combines **Python, Pandas, SQL, Exploratory Data Analysis (EDA), Machine Learning, and Power BI** to transform customer data into meaningful business insights.

---

## 🎯 Project Objectives

- Analyze customer churn patterns
- Clean and prepare customer data
- Perform Exploratory Data Analysis (EDA)
- Calculate important churn KPIs
- Analyze churn across customer segments
- Perform SQL-based analysis
- Build a machine learning model for churn prediction
- Prepare data for Power BI dashboard development
- Identify factors associated with customer churn

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- SQLite
- Scikit-learn
- Power BI
- Google Colab
- Git & GitHub

---

## 📁 Dataset

The project uses the **IBM Telco Customer Churn sample dataset**.

The dataset contains customer information related to:

- Customer demographics
- Tenure
- Contract type
- Internet services
- Payment methods
- Monthly charges
- Total charges
- Additional services
- Customer churn

**Dataset size:** 7,043 customers and 21 columns.

> Note: The dataset represents sample data for a fictional telecommunications company.

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Converted `TotalCharges` to numeric format
- Handled missing values
- Removed duplicate records
- Converted `SeniorCitizen` into categorical labels
- Created a numerical `Churn_Flag`
- Created customer tenure groups
- Created a service-count feature

---

## 🔎 Exploratory Data Analysis

The analysis examined churn across:

- Contract type
- Internet service
- Payment method
- Customer tenure
- Monthly charges
- Total charges
- Senior citizen status
- Tech support
- Online security
- Customer services
- Customer characteristics

---

## 📈 Key KPIs

The project calculates:

| KPI | Description |
|---|---|
| Total Customers | Total number of customers |
| Churned Customers | Customers who left the service |
| Churn Rate | Percentage of customers who churned |
| Average Monthly Charges | Average monthly customer charges |
| Average Tenure | Average customer tenure |
| Average Total Charges | Average accumulated customer charges |

---

## 🗄️ SQL Analysis

SQL analysis was performed using SQLite.

Queries were created to analyze:

- Total customers
- Churned customers
- Overall churn rate
- Churn by contract
- Average monthly charges
- Churn by internet service
- High monthly-charge churned customers

---

## 🤖 Machine Learning

A **Logistic Regression** classification model was developed to predict customer churn.

### Machine Learning Workflow

1. Feature preparation
2. Train/test split
3. Numerical feature scaling
4. Categorical feature encoding
5. Logistic Regression model training
6. Churn prediction
7. Model evaluation

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The model's feature coefficients were also analyzed to identify variables associated with higher or lower churn predictions.

> Model associations should not be interpreted as proof that a variable directly causes customer churn.

---

## 📊 Power BI Dashboard

The cleaned dataset was prepared for Power BI dashboard development.

### Planned Dashboard KPIs

- Total Customers
- Churned Customers
- Churn Rate
- Average Monthly Charges
- Average Tenure

### Planned Visualizations

- Churn by Contract
- Churn by Internet Service
- Churn by Payment Method
- Churn by Tenure Group
- Churn by Tech Support
- Churn by Online Security

---

## 💡 Business Insights

The analysis helps identify customer segments with different levels of churn and provides a structured view of customer behavior.

The results can support further investigation into:

- Customer retention
- Contract strategies
- Service offerings
- Customer support
- Pricing and monthly charges
- High-risk customer segments

---

## 📂 Project Files

```text
customer_churn_analysis.ipynb
customer_churn_cleaned.csv
customer_churn.db
churn_kpi_summary.csv
churn_by_contract.csv
churn_by_internet_service.csv
churn_by_payment_method.csv
churn_by_tenure.csv
churn_feature_importance.csv
README.md
