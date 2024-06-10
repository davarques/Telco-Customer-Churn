# Telco Customer Churn Analysis

<img src="https://ised-isde.canada.ca/site/mobile-plans/sites/default/files/img/2022/1012_04_21_Telecomm_WebButtons_A.jpg" alt="Telco Customer Churn" width="800">

## Introduction 📋

This repository contains analysis and insights derived from the Telco Customer Churn dataset. The dataset provides valuable information about customer behavior, allowing businesses to predict and mitigate customer churn effectively. By exploring various data points, we aim to identify key factors influencing churn and propose actionable strategies for customer retention.

## Goal & Context 🎯

### Goal:
* Analyze the `Telco Customer Churn` dataset to gain valuable insights and identify specific business actions to reduce customer churn.

### Context:

* Customer churn refers to when a customer stops using a product or service. Analyzing customer churn is crucial for businesses, especially now, given that **retaining customers is equally or more valuable than acquiring new ones**, as losing clients is very costly. This shift reflects a more **product-led mindset** in technological businesses.

### Problem Statement:

* How can we reduce customer churn through action-oriented analysis?


## Dataset 💾

`Source:` [Kaggle: Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)
  
`Size:` 7,043 Rows, 21 Columns

### Key Features (Columns)

- **`customerid`:** Customer identification number.
- **`gender`:** Whether the customer is male or female.
- **`seniorcitizen`:** 0 if the customer is under 65 years old, or 1 if they are 65 or older.
- **`partner`:** Whether the customer has a partner (Yes or No).
- **`dependents`:** Whether the customer has dependents (Yes, No) such as children, parents, etc.
- **`tenure`:** Number of months the customer has stayed with the company.
- **`phoneservice`:** Whether the customer has a phone service (Yes, No).
- **`multiplelines`:** Whether the customer has multiple lines (Yes, No, No phone service).
- **`internetservice`:** Customer’s internet service provider (DSL, Fiber optic, No).
- **`onlinesecurity`:** Whether the customer has online security (Yes, No, No internet service).
- **`onlinebackup`:** Whether the customer has online backup (Yes, No, No internet service).
- **`deviceprotection`:** Whether the customer has device protection (Yes, No, No internet service).
- **`techsupport`:** Whether the customer has tech support (Yes, No, No internet service).
- **`streamingtv`:** Whether the customer has streaming TV (Yes, No, No internet service).
- **`streamingmovies`:** Whether the customer has streaming movies (Yes, No, No internet service).
- **`contract`:** Customer’s current contract type: Month-to-Month, One Year, Two Year.
- **`paperlessbilling`:** Whether the customer has paperless billing (Yes, No).
- **`paymentmethod`:** How the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check.
- **`monthlycharges`:** Customer’s current total monthly charge for all services.
- **`totalcharges`:** Customer’s total charges up to the end of the specified quarter.

**`Target Column`** = **`churn`:** 1 if the customer left the company (Churn=Yes) and 0 if they remained (Churn=No) based on the last quarter.

## Exploratory Data Analysis 🔬
