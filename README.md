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

## 🎯 Objectives

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

## 🔍 Exploratory Data Analysis (EDA)

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
customer-churn-analysis-python-Exploratory-Data-Analysis-project-6/
│
├── assests/                          # Folder for images or other assets
│
├── dataset/                          # Folder containing the raw data
│ └── Customer Churn.csv              # The main dataset file
│
├── jupyter notebook/                 # Folder for the analysis notebook
│ └── customer churn analysis.ipynb   # Main Jupyter Notebook with the EDA code
│
├── LICENSE                           # MIT License file
│
└── README.md                         # Project overview and instructions (this file)
```

---

## ▶ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/Alamin-refat/customer-churn-analysis-python-Exploratory-Data-Analysis-project-6.git
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

## 🔮 Future Improvements

* Build a **machine learning model** to predict churn
* Perform **feature engineering**
* Deploy an **interactive dashboard**
* Implement **customer segmentation**

---

## 👤 Author

**Alamin Refat**

**Data Analyst | Machine Learning Engineer** Passionate about turning raw data into meaningful stories through **Advanced Data Analysis** and **Business Intelligence**. I focus on creating **interactive dashboards** and **modular ML projects** that bridge the gap between technical data and business strategy.

Expertise in: **Microsoft Excel (Advanced), SQL, Python, Power BI, Tableau and Machine Learning.**

---

### 🔗 Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-Alamin--refat-black?logo=github)](https://github.com/Alamin-refat)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alamin%20Refat-blue?logo=linkedin)](https://www.linkedin.com/in/alaminrefat1/)
[![Gmail](https://img.shields.io/badge/Gmail-Contact-red?logo=gmail&logoColor=white)](mailto:alaminrefat2017@gmail.com)

---

## ⭐ Support

If you found this project useful, consider **starring the repository** to support the work.

---

## ⚖️ License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project for personal or commercial purposes, provided that proper credit is given to the original author.

See the LICENSE file for more details.

---

