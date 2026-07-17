# 📊 Customer Churn Prediction & Retention Analytics Platform

An end-to-end data analytics and machine learning project designed to analyze customer churn, identify key churn drivers, predict at-risk customers, and provide actionable retention recommendations.

The project combines **Python, SQL, Machine Learning, and Power BI** to transform raw telecom customer data into meaningful business insights and customer retention strategies.

---

## 📌 Project Overview

Customer churn is a major challenge for subscription-based businesses. Retaining existing customers is often more cost-effective than acquiring new ones.

This project analyzes telecom customer behavior to answer key business questions:

- How many customers are churning?
- What factors contribute most to customer churn?
- Which customers are at high risk of leaving?
- Which machine learning model performs best for churn prediction?
- What retention actions can be recommended for at-risk customers?

The final solution includes an interactive **Power BI dashboard**, machine learning models, SQL analysis, and customer-level churn risk predictions.

---

## 📊 Power BI Dashboard

The Power BI dashboard provides a business-focused overview of customer churn and retention analytics.

### Key KPIs

- **Total Customers:** 7,032
- **Churned Customers:** 1,869
- **Churn Rate:** 26.58%
- **Average Monthly Charges:** $64.80

### Dashboard Features

- Churned Customers by Contract
- Churned Customers by Internet Service
- Customer Risk Level Distribution
- Top Factors Influencing Customer Churn
- High-Risk Customer Identification
- Recommended Retention Actions

![Customer Churn Dashboard](images/dashboard.png)

---

## 🤖 Machine Learning Models

Three classification algorithms were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest

Model performance was compared using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### ROC-AUC Results

| Model | ROC-AUC |
|---|---:|
| Logistic Regression | 0.84 |
| Decision Tree | 0.83 |
| Random Forest | 0.83 |

Logistic Regression achieved the highest ROC-AUC score in the model comparison.

![ROC Curve Comparison](images/roc_curve.png)

---

## 🎯 Confusion Matrix

The Logistic Regression confusion matrix provides insight into the model's churn classification performance.

- **723** customers who stayed were correctly classified.
- **298** churned customers were correctly identified.
- **310** customers who stayed were predicted as churned.
- **76** churned customers were predicted as staying.

![Confusion Matrix](images/confusion_matrix.png)

---

## 🔍 Key Churn Factors

The analysis identified several important factors influencing customer churn.

Some of the strongest factors include:

- Customer tenure
- Month-to-month contracts
- Total charges
- Monthly charges
- Two-year contracts
- Online security
- Technical support
- Fiber optic internet service
- Electronic check payment method

![Feature Importance](images/feature_importance.png)

---

## 💡 Key Business Insights

The analysis highlights several important customer churn patterns:

- Customers with **month-to-month contracts** have the highest churn volume.
- Customers using **fiber optic internet service** show higher churn compared with other internet service categories.
- **Customer tenure** is one of the strongest factors influencing churn.
- Contract type and monthly charges are important indicators of customer retention behavior.
- Customers without services such as **online security** and **technical support** may have increased churn risk.

These insights can help businesses identify vulnerable customer segments and develop targeted retention strategies.

---

## 🎯 Customer Risk Segmentation

Customers are classified into three risk categories based on predicted churn probability:

- **Low Risk**
- **Medium Risk**
- **High Risk**

The platform also provides recommended actions based on customer risk.

Examples include:

- Maintain regular engagement
- Send personalized loyalty offers
- Offer discounted annual contracts

This transforms machine learning predictions into actionable business recommendations.

---

## 🛠️ Technologies Used

### Programming & Data Analysis

- Python
- Pandas
- NumPy

### Database

- SQL
- SQLite

### Machine Learning

- Scikit-learn
- Logistic Regression
- Decision Tree
- Random Forest

### Data Visualization

- Matplotlib
- Power BI

### Development Environment

- Google Colab
- Jupyter Notebook

---

## 📁 Project Structure

```text
Customer-Churn-Prediction-Retention-Analytics/
│
├── data/
│   ├── customer_churn_powerbi.csv
│   ├── feature_importance.csv
│   ├── kpi_summary.csv
│   └── model_performance.csv
│
├── database/
│   └── customer_churn.db
│
├── notebook/
│   └── Customer_Churn_Prediction_Retention_Analytics_Platform.ipynb
│
├── powerbi/
│   └── Customer_Churn_Prediction_Retention_Analytics_Dashboard.pbix
│
├── images/
│   ├── dashboard.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── roc_curve.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## ⚙️ Project Workflow

**Raw Customer Data**

↓

**Data Cleaning & Preprocessing**

↓

**Exploratory Data Analysis**

↓

**SQL Analysis**

↓

**Feature Engineering**

↓

**Machine Learning Model Training**

↓

**Model Evaluation**

↓

**Customer Churn Risk Prediction**

↓

**Retention Recommendations**

↓

**Power BI Dashboard**

---

## 📈 Business Value

This project demonstrates how data analytics and machine learning can support customer retention strategies.

The solution can help businesses:

- Identify customers at risk of churn
- Understand the main factors contributing to churn
- Segment customers based on churn risk
- Develop targeted retention campaigns
- Support data-driven decision-making

---

## 🚀 Future Improvements

Future versions of the project could include:

- Hyperparameter tuning for machine learning models
- XGBoost or LightGBM models
- SHAP-based model explainability
- Real-time churn prediction API
- Automated model retraining
- Cloud deployment
- Power BI Service integration

---

## 👤 Author

**Eric Rathod**

Master of Artificial Intelligence – Design and Development  
Seneca Polytechnic, Toronto, Canada

### Skills

`Python` `SQL` `Machine Learning` `Power BI` `Data Analytics` `Scikit-learn` `Pandas` `Business Intelligence`

---
