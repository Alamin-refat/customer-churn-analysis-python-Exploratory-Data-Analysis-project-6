# 🔍 Customer Churn Analysis Project | Exploratory Data Analysis with Python

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-teal)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-green)
![Dataset](https://img.shields.io/badge/Dataset-Customer%20Churn-red)

## 📌 Project Overview

This project focuses on analyzing **customer churn behavior** using data analysis and visualization techniques in Python. The goal is to identify patterns and key factors that influence customer churn so businesses can take proactive steps to improve customer retention.

Using exploratory data analysis (EDA), the dataset is cleaned, transformed, and visualized to uncover meaningful insights about customer demographics, service usage, and billing patterns that contribute to churn.

---

## Objectives

* Understand the distribution of churned vs retained customers
* Identify factors that influence customer churn
* Perform data cleaning and preprocessing
* Analyze relationships between customer features and churn
* Generate visual insights to support business decision-making

---

## 📂 Dataset Information

The dataset contains **7043 customer records** with **21 features**, including:

* Customer demographics
* Account information
* Service subscriptions
* Billing details
* Churn status

### Key Features

* `customerID` – Unique customer identifier
* `gender` – Customer gender
* `SeniorCitizen` – Whether the customer is a senior citizen
* `tenure` – Number of months the customer has stayed
* `PhoneService` – Whether the customer has phone service
* `InternetService` – Type of internet service
* `Contract` – Contract type
* `MonthlyCharges` – Monthly billing amount
* `TotalCharges` – Total charges billed
* `Churn` – Whether the customer left the company

---

## 🧹 Data Cleaning & Preprocessing

Several preprocessing steps were performed to prepare the data for analysis:

* Replaced blank values in **TotalCharges**
* Converted **TotalCharges** to numeric format
* Checked data types and missing values
* Ensured data consistency for analysis

---

## Exploratory Data Analysis (EDA)

The project includes multiple visualizations to analyze churn behavior, such as:

* Churn distribution
* Gender vs churn comparison
* Senior citizen churn analysis
* Contract type vs churn
* Tenure vs churn relationship
* Monthly charges vs churn trends
* Service usage vs churn patterns

Visualization tools like **Matplotlib** and **Seaborn** were used to create clear and informative charts.

---

## 📈 Key Insights

Some important insights from the analysis include:

* Customers with **month-to-month contracts** have a higher churn rate.
* **Short-tenure customers** are more likely to churn.
* Customers with **higher monthly charges** tend to churn more frequently.
* Certain **service combinations** influence customer retention.

These insights can help businesses design better **customer retention strategies**.

---

## 🛠 Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📁 Project Structure

```
Customer-Churn-Analysis
│
├── Customer Churn.csv
├── customer churn analysis.ipynb
└── README.md
```

---

## How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-analysis.git
```

2. Navigate to the project folder

```bash
cd customer-churn-analysis
```

3. Open the Jupyter Notebook

```bash
jupyter notebook
```

4. Run the notebook **customer churn analysis.ipynb**

---

## Future Improvements

* Build a **machine learning model** to predict churn
* Perform **feature engineering**
* Deploy an **interactive dashboard**
* Implement **customer segmentation**

---

## Author

**Alamin Refat**

Aspiring **Data Analyst** passionate about transforming data into actionable insights through analysis and visualization.
