# Bank Customer Churn Prediction

##Project Overview

This project focuses on predicting customer churn in the banking sector using Machine Learning techniques.

Customer churn refers to customers leaving or discontinuing their relationship with a bank. Predicting potential churn customers can help banks take preventive actions, improve customer satisfaction, and reduce customer loss.

---

##Project Objectives

The main objectives of this project are:

- Analyze customer data to identify factors related to customer churn.
- Perform Exploratory Data Analysis (EDA).
- Preprocess and prepare the dataset for Machine Learning.
- Select relevant features for prediction.
- Train multiple Machine Learning models.
- Evaluate and compare model performance.
- Identify the best-performing model for customer churn prediction.

---

##Problem Domain

**Domain:** Banking and Financial Services

**Problem:**  
Banks need to identify customers who are likely to leave their services so that appropriate retention strategies can be applied.

**Machine Learning Task:**  
Binary Classification

**Target Variable:** `Exited`

- `0` → Customer stayed
- `1` → Customer left

---

##Dataset

The project uses the **Churn Modelling Dataset**.

### Dataset Information

- Number of records: 10,000
- Target variable: `Exited`
- Problem type: Binary Classification

  ###Member Allocations
  
| Member         | EDA Task                  | Preprocessing Task             |
| -------------- | ------------------------- | ------------------------------ |
| **Aathmika**   | Distribution              | Encoding Categorical Variables |
| **Thishan**    | Categorical Feature Graph | Feature Engineering            |
| **Fatheen**    | Churn Proportion          | Normalization                  |
| **Shakeer**    | Correlation               | Outlier Removal                |
| **Sipna**      | Boxplot                   | Standardization                |
| **Lathurshan** | Customer Characteristics  | Handling Missing Values        |

### Main Features

| Feature | Description |
|
| CreditScore | Customer's credit score |
| Geography | Customer's country/region |
| Gender | Customer's gender |
| Age | Customer's age |
| Tenure | Number of years with the bank |
| Balance | Customer's account balance |
| NumOfProducts | Number of bank products used |
| HasCrCard | Whether the customer has a credit card |
| IsActiveMember | Whether the customer is an active member |
| EstimatedSalary | Estimated customer salary |

The following columns are excluded because they are not useful for prediction:

- `RowNumber`
- `CustomerId`
- `Surname`

---

##Project Workflow

The project follows the following Machine Learning workflow:

```text
Data Collection
      ↓
Data Understanding
      ↓
Exploratory Data Analysis
      ↓
Data Preprocessing
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Best Model Selection
