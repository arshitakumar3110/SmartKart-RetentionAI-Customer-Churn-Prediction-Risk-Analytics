# SmartKart RetentionAI 🚀

### Customer Churn Prediction & Risk Analytics

## 📌 Overview

**SmartKart RetentionAI** is a data analytics and machine learning project focused on predicting customer churn and identifying customers who are at high risk of leaving the SmartKart platform.

The project analyzes customer information such as:

* Customer ID
* Age
* Monthly Spending
* Number of Complaints
* Churn Status
* Churn Probability
* Risk Category

The goal is to help SmartKart understand customer behavior and take proactive steps to improve customer retention.

---

## 🎯 Objectives

The main objectives of this project are:

1. To analyze customer characteristics and behavior.
2. To identify patterns associated with customer churn.
3. To predict whether a customer is likely to churn.
4. To calculate the probability of customer churn.
5. To classify customers based on their churn risk.
6. To provide insights that can support customer retention strategies.

---

## 📂 Dataset

The project contains two datasets:

### 1. SmartKart Dirty Dataset

`SmartKart_dirty_100_rows.csv`

This dataset contains **100 customer records** with the following variables:

| Column          | Description                               |
| --------------- | ----------------------------------------- |
| `Customer_ID`   | Unique customer identifier                |
| `Age`           | Age of the customer                       |
| `Monthly_Spend` | Customer's monthly spending               |
| `Complaints`    | Number of complaints made by the customer |
| `Churn`         | Actual customer churn status              |

### 2. Churn Risk Report

`smartkart_churn_risk_report.csv`

This report contains the churn prediction results, including:

| Column              | Description                    |
| ------------------- | ------------------------------ |
| `Customer_ID`       | Unique customer identifier     |
| `Age`               | Customer age                   |
| `Monthly_Spend`     | Monthly customer spending      |
| `Complaints`        | Number of complaints           |
| `Actual_Churn`      | Actual churn status            |
| `Predicted_Churn`   | Model-predicted churn status   |
| `Churn_Probability` | Probability of customer churn  |
| `Risk_Label`        | Customer's churn-risk category |

---

## 🔍 Key Analysis

The project focuses on understanding how customer characteristics are related to churn.

Important factors considered include:

### Monthly Spending

Customer spending patterns can help identify differences between customers who remain active and those who churn.

### Complaints

The number of complaints is an important indicator of customer dissatisfaction and may be associated with a higher likelihood of churn.

### Churn Probability

Each customer can be assigned a probability representing how likely they are to churn.

### Risk Classification

Customers can be categorized according to their predicted churn risk, making it easier for businesses to prioritize retention efforts.

---

## 🤖 Churn Prediction

The churn prediction component uses customer-level data to estimate whether a customer is likely to churn.

The output includes:

* **Actual Churn**
* **Predicted Churn**
* **Churn Probability**
* **Risk Label**

This allows the business to compare model predictions with actual customer outcomes and evaluate the effectiveness of the prediction approach.

---

## 📊 Business Use Case

SmartKart can use the insights from this project to:

* Identify customers at high risk of leaving.
* Offer personalized discounts or incentives.
* Improve customer support for dissatisfied customers.
* Investigate customers with frequent complaints.
* Develop targeted customer retention campaigns.
* Reduce customer acquisition costs by retaining existing customers.

---

## 💡 Expected Outcome

The project aims to transform raw customer data into actionable business insights.

Instead of waiting for customers to leave, SmartKart can use churn-risk predictions to identify potentially dissatisfied customers and take preventive action.

**Predict → Identify → Retain → Grow**

---

## 🛠️ Technologies

The project can be implemented using:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## 📁 Project Structure

```text
SmartKart-RetentionAI/
│
├── data/
│   └── SmartKart_dirty_100_rows.csv
│
├── reports/
│   └── smartkart_churn_risk_report.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── README.md
└── requirements.txt
```

---

## 📈 Future Improvements

Future versions of the project can include:

* More customer behavioral features.
* Advanced machine learning models.
* Interactive dashboards using Power BI or Streamlit.
* Automated customer retention recommendations.
* Real-time churn monitoring.
* Customer segmentation.
* Model performance comparison using multiple algorithms.

---

## 👩‍💻 Project Purpose

This project demonstrates how **data analytics and machine learning can be applied in business and fintech-related decision-making** to understand customer behavior and improve customer retention.

---

## ⭐ Conclusion

**SmartKart RetentionAI** provides a data-driven approach to customer churn prediction. By identifying customers who are likely to churn and understanding the factors associated with customer dissatisfaction, SmartKart can make better retention decisions and build stronger long-term customer relationships.
