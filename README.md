# 📊 Telecom Customer Churn Analysis

## Overview

Customer churn is one of the most important business challenges faced by subscription-based companies. Acquiring a new customer is often significantly more expensive than retaining an existing one.

This project performs an **Exploratory Data Analysis (EDA)** on a telecom customer dataset containing information for **7,043 customers**. The objective is to identify the major factors influencing customer churn and provide actionable business recommendations to improve customer retention.

---

## Business Problem

The telecom company experiences customer attrition that directly impacts recurring revenue and customer lifetime value.

This analysis aims to answer questions such as:

* Which customers are most likely to churn?
* Does customer tenure influence churn?
* How do contract types affect retention?
* Which services reduce churn?
* Do payment methods influence customer loyalty?
* Which customer segments should receive targeted retention strategies?

---

## Dataset

**Source:** Kaggle – Telecom Customer Churn Dataset

### Dataset Summary

* **Total Customers:** 7,043
* **Features:** 21
* **Target Variable:** `Churn`
* **Data Type:** Customer demographics, subscribed services, billing information, contracts, and payment methods.

### Key Variables

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn

---

## Objectives

* Perform comprehensive data cleaning.
* Explore customer demographics.
* Analyze churn distribution.
* Study relationships between churn and customer tenure.
* Evaluate contract types.
* Investigate subscribed services.
* Examine payment methods.
* Generate business-driven insights through visualization.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Cleaning

The following preprocessing steps were performed before analysis:

* Converted `TotalCharges` to numeric format.
* Handled blank values.
* Checked for missing values.
* Verified duplicate records.
* Corrected data types.
* Generated descriptive statistics.
* Validated dataset integrity.

---

## Exploratory Data Analysis

The project includes visualizations and analysis for:

### Customer Distribution

* Overall churn rate
* Customer retention rate

### Demographic Analysis

* Gender vs Churn
* Senior Citizen vs Churn
* Partner vs Churn
* Dependents vs Churn

### Customer Lifetime Analysis

* Tenure distribution
* Tenure vs Churn
* Monthly Charges distribution
* Total Charges distribution

### Service Analysis

* Phone Service
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies

### Contract & Billing Analysis

* Contract Type
* Paperless Billing
* Payment Method

---

## Key Insights

### Customer Churn

* **26.54%** of customers churned.
* Approximately **1 in every 4 customers** leaves the company.

---

### Early Tenure Customers Are High Risk

Customers with very low tenure exhibit the highest churn rates.

**Business Insight**

The first few months after customer acquisition represent the most critical retention period.

---

### Contract Type Strongly Influences Retention

* Month-to-month contracts have the highest churn.
* One-year contracts reduce churn.
* Two-year contracts show the strongest customer retention.

---

### Value-Added Services Reduce Churn

Customers subscribing to the following services demonstrate better retention:

* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming Services

These services increase customer engagement and perceived value.

---

### Payment Method Matters

Customers paying through **Electronic Check** exhibit the highest churn.

Automatic payment methods are associated with better customer retention.

---

### Senior Citizens Are More Likely to Churn

Senior customers experience higher churn than non-senior customers, suggesting the need for more personalized support and simplified service offerings.

---

### Gender Has Minimal Impact

Male and female customers display similar churn behavior, indicating that gender is not a significant predictor of customer attrition.

---

## Business Recommendations

Based on the analysis, the following strategies can improve customer retention:

* Focus retention efforts during the first six months of customer onboarding.
* Encourage migration from month-to-month to long-term contracts.
* Promote Online Security, Backup, Device Protection, and Tech Support services.
* Offer incentives for automatic payment methods.
* Develop targeted retention programs for senior citizens.
* Create bundled service packages to increase customer engagement.

---

## Project Structure

```
Telecom-Customer-Churn-Analysis/
│
├── data/
│   └── telecom_customer_churn.csv
│
├── notebooks/
│   └── Telecom_Customer_Churn_EDA.ipynb
│
├── images/
│   ├── churn_distribution.png
│   ├── tenure_analysis.png
│   ├── contract_type.png
│   ├── payment_method.png
│   └── service_analysis.png
│
├── README.md
└── requirements.txt
```

---

## Sample Visualizations

The notebook contains numerous visualizations including:

* Bar Charts
* Count Plots
* Histograms
* Box Plots
* KDE Plots
* Stacked Percentage Charts
* Correlation Analysis

---

## Future Work

* Build predictive machine learning models for churn prediction.
* Address class imbalance using SMOTE or other resampling techniques.
* Perform feature engineering.
* Apply feature importance techniques such as SHAP.
* Develop an interactive Power BI or Tableau dashboard.
* Deploy a churn prediction application using Streamlit.

---

## Results

The analysis demonstrates that customer churn is primarily driven by:

* Low customer tenure
* Month-to-month contracts
* Lack of support and security services
* Electronic Check payment method
* Senior citizen customer segment

These findings can help telecom companies prioritize customer retention initiatives, reduce revenue loss, and improve long-term customer lifetime value.

---

## Author

**Jayanta**

Final-Year Statistics Undergraduate

**Skills**

* Python
* SQL
* Statistics
* Exploratory Data Analysis (EDA)
* Data Visualization
* Machine Learning (Beginner)

Feel free to connect or provide feedback on this project.
