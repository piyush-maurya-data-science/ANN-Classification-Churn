# Customer Churn Prediction

## Problem Statement

The banking industry faces significant challenges in retaining customers, as customer churn directly impacts revenue and business growth. This dataset aims to address the following problem:

- **Objective**: Develop a machine learning model to predict customer churn based on historical data, enabling the bank to take proactive measures to retain customers.

- **Key Challenges**:
  - Identifying patterns and factors that influence customer churn.
  - Handling imbalanced data where churn cases may be fewer than non-churn cases.
  - Choosing appropriate features and engineering new ones for better model performance.

By leveraging this dataset, businesses can gain insights into customer behavior and improve their customer retention strategies.

# `Dataset Description`
Dataset consists customer information for a customer churn prediction problem. It includes the following columns:

* **RowNumber**: Index of the row (not a predictive feature).

* **CustomerID**: Unique identifier for each customer (not predictive).

* **Surname**: Customer's surname (not predictive).

* **Age: Age of the customer.**

* **Gender**: Gender of the customer (Male or Female).

* **CreditScore**: Customer's credit score.

* **Geography**: Country of the customer (categorical, e.g., France, Germany, Spain).

* **Tenure**: Number of years the customer has been with the bank.

* **Balance**: Account balance.

* **NumOfProducts**: Number of bank products the customer is using.

* **HasCrCard**: Binary indicator (1 = customer has a credit card, 0 = doesn't).

* **IsActiveMember**: Binary indicator of whether the customer is active.

* **EstimatedSalary**: Customer's estimated salary.

* **Exited**: Target variable (1 = customer churned, 0 = customer stayed).


## Applications

This dataset is ideal for:

1. **Binary Classification**
   - Predicting churn (Exited = 1 or 0).

2. **Exploratory Data Analysis (EDA)**
   - Analyzing customer demographics and behavior.

3. **Feature Engineering**
   - Creating derived features like Age group or Product usage ratio.

4. **Machine Learning Models**
   - Building predictive models using:
     - Logistic Regression
     - Decision Trees
     - Random Forest
     - Gradient Boosting (e.g., XGBoost, LightGBM)
     - Neural Networks (Deep Learning).
