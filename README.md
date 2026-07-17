# 📊 Customer Churn Prediction & Retention Analytics

An end-to-end data analytics and machine learning project designed to identify customers at risk of churn and provide actionable retention recommendations.

The project combines **Python, Machine Learning, SQL, and Power BI** to analyze customer behavior, predict churn probability, identify key churn drivers, segment customers by risk level, and visualize insights through an interactive dashboard.

---

## 🎯 Project Objective

Customer churn is a major challenge for subscription-based businesses. Retaining existing customers is often more cost-effective than acquiring new ones.

The objectives of this project are to:

- Analyze customer churn patterns
- Identify the main factors influencing customer churn
- Build and compare machine learning classification models
- Predict customer churn probability
- Segment customers into Low, Medium, and High Risk groups
- Generate recommended retention actions
- Develop an interactive Power BI dashboard for business analysis

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an overview of customer churn and retention analytics, including:

- Total Customers
- Churned Customers
- Churn Rate
- Average Monthly Charges
- Churned Customers by Contract Type
- Churned Customers by Internet Service
- Customer Risk Level Distribution
- Top Factors Influencing Customer Churn
- Customer-Level Risk and Retention Recommendations

![Customer Churn Prediction and Retention Analytics Dashboard](images/dashboard.png)

---

## 📌 Key Business Insights

The analysis identified several important patterns associated with customer churn:

- Customers with **month-to-month contracts** have significantly higher churn.
- **Customer tenure** is one of the strongest factors influencing churn.
- Customers using **fiber optic internet service** show higher churn levels.
- **Monthly Charges** and **Total Charges** are important predictors of customer behavior.
- Customers without services such as **Online Security** and **Tech Support** may have higher churn risk.
- Customer risk segmentation can help businesses prioritize retention campaigns.

---

## 🤖 Machine Learning Models

Three classification models were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest

The models were compared using classification metrics and ROC-AUC performance.

### ROC-AUC Results

| Model | ROC-AUC |
|---|---:|
| Logistic Regression | 0.84 |
| Decision Tree | 0.83 |
| Random Forest | 0.83 |

Logistic Regression achieved the highest ROC-AUC score and was used as a strong baseline model for customer churn prediction.

---

## 📈 ROC Curve Comparison

The ROC curve compares the predictive performance of the three machine learning models.

![ROC Curve Comparison](images/roc_curve_comparison.png)

---

## 🎯 Confusion Matrix

The confusion matrix below shows the classification results for the Logistic Regression model.

![Logistic Regression Confusion Matrix](images/confusion_matrix.png)

---

## 🔍 Top Factors Influencing Customer Churn

Feature importance analysis was used to identify the variables that contribute most strongly to churn prediction.

Important factors include:

- Tenure
- Month-to-month contracts
- Total Charges
- Monthly Charges
- Two-year contracts
- Online Security
- Tech Support
- Fiber Optic Internet Service
- Electronic Check Payment Method

![Top Factors Influencing Customer Churn](images/feature_importance.png)

---

## ⚠️ Customer Risk Segmentation

Customers are segmented into three risk categories based on their predicted churn probability:

| Risk Level | Description | Recommended Action |
|---|---|---|
| Low Risk | Customers with low predicted churn probability | Maintain regular engagement |
| Medium Risk | Customers showing moderate churn risk | Send personalized loyalty offers |
| High Risk | Customers with high predicted churn probability | Offer targeted retention incentives |

This segmentation allows businesses to focus retention efforts on customers who are most likely to leave.

---

## 💡 Retention Recommendations

Based on the analysis, businesses can consider the following retention strategies:

- Encourage month-to-month customers to switch to annual or long-term contracts.
- Provide targeted discounts or incentives to high-risk customers.
- Promote Online Security and Tech Support services.
- Develop personalized loyalty offers for medium-risk customers.
- Monitor customers with high monthly charges and short tenure.
- Prioritize retention campaigns using churn probability and risk segmentation.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **SQL / SQLite**
- **Power BI**
- **Jupyter Notebook / Google Colab**

---

## 📂 Project Workflow

The project follows an end-to-end analytics and machine learning workflow:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Machine Learning Model Training
6. Model Evaluation
7. ROC-AUC Comparison
8. Feature Importance Analysis
9. Customer Churn Probability Prediction
10. Customer Risk Segmentation
11. Retention Recommendation Generation
12. SQL Data Storage
13. Power BI Dashboard Development

---

## 📊 Dataset Summary

- **Total Customers:** 7,032
- **Churned Customers:** 1,869
- **Churn Rate:** 26.58%
- **Average Monthly Charges:** 64.80

The dataset contains customer demographic information, account details, subscribed services, contract information, payment methods, and churn status.

---

## 📁 Repository Contents

The repository contains:

- Machine learning analysis notebook
- Customer churn dataset
- Power BI dashboard file
- Customer churn predictions
- Feature importance results
- Model performance results
- KPI summary
- SQLite database
- ROC curve visualization
- Confusion matrix
- Feature importance visualization
- Power BI dashboard screenshot

---

## 🚀 How to Run the Project

1. Clone this repository.
2. Open the Jupyter Notebook or upload it to Google Colab.
3. Install the required Python libraries.
4. Run the notebook cells in sequence.
5. Review the generated machine learning results and visualizations.
6. Open the `.pbix` file using Power BI Desktop to explore the interactive dashboard.

---

## 🔮 Future Improvements

Future versions of this project could include:

- Hyperparameter tuning
- XGBoost or LightGBM models
- SHAP-based model explainability
- Automated model retraining
- Real-time churn prediction API
- Deployment of the dashboard to Power BI Service
- Integration with CRM systems for automated retention campaigns

---

## 👨‍💻 Author

**Eric Rathod**

Master's in Artificial Intelligence – Design and Development  
Seneca Polytechnic, Toronto, Canada

---

## ⭐ Project Summary

This project demonstrates an end-to-end approach to solving a real-world customer retention problem by combining **data analytics, machine learning, SQL, and business intelligence**.

The final solution not only predicts customer churn but also converts machine learning predictions into customer risk levels and actionable retention recommendations that can support data-driven business decisions.
