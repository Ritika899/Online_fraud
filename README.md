# 💳 Online Payment Fraud Detection Using Machine Learning

## 📌 Overview

This project focuses on identifying **fraudulent online payment transactions using Machine Learning**.

The objective is to build a classification model that can distinguish between **fraudulent transactions (1)** and **legitimate transactions (0)** by analyzing transaction patterns and customer account information.

## 📂 Dataset

The dataset contains historical online payment transactions and is sourced from Kaggle.

### 🔗 Kaggle Dataset

**[Online Payment Fraud Detection Dataset – Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1)**

## 📊 Dataset Features

| Feature          | Description                                                             |
| ---------------- | ----------------------------------------------------------------------- |
| `step`           | Represents a time unit, where each step corresponds to one hour         |
| `type`           | Type of online transaction                                              |
| `amount`         | Amount involved in the transaction                                      |
| `nameOrig`       | Customer initiating the transaction                                     |
| `oldbalanceOrg`  | Originating customer's balance before the transaction                   |
| `newbalanceOrig` | Originating customer's balance after the transaction                    |
| `nameDest`       | Recipient of the transaction                                            |
| `oldbalanceDest` | Recipient's balance before the transaction                              |
| `newbalanceDest` | Recipient's balance after the transaction                               |
| `isFraud`        | Target variable: `1` for fraudulent and `0` for legitimate transactions |

## 🔍 Project Workflow

* Data loading and exploration
* Data cleaning and preprocessing
* Exploratory Data Analysis
* Feature selection and encoding
* Handling the highly imbalanced fraud data
* Training Machine Learning classification models
* Evaluating model performance using **Precision, Recall and F1-Score**

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🎯 Objective

The main goal is to develop a machine learning model capable of identifying potentially fraudulent online payment transactions and understanding the transaction characteristics associated with fraud.
