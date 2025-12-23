# beta-bank-customer-churn-prediction
Este es el repositorio en el que se creará todo para el proyecto del sprint 11 del curso de Triple Ten 
# Beta Bank Customer Churn Prediction

## Project Description

Beta Bank has identified a gradual but consistent loss of customers each month. Since retaining existing customers is more cost-effective than acquiring new ones, the bank wants to proactively identify clients who are likely to leave.

In this project, a machine learning model is developed to **predict customer churn**, using historical customer behavior data and information about contract termination.

---

## Project Objective

- Build a binary classification model to predict whether a customer will leave the bank
- Maximize the **F1 score**, with a required minimum value of **0.59** on the test set
- Evaluate model performance using both **F1 score** and **AUC-ROC**
- Compare the two metrics to better understand model effectiveness

---

## Dataset Overview

The dataset contains historical information about bank customers, including:

- Demographic data
- Account and service usage behavior
- Contract status and churn indicator

The target variable represents whether the customer has churned.

---

## Methodology

- Data loading and inspection
- Data preprocessing and feature preparation
- Handling class imbalance
- Splitting data into training and test sets
- Training multiple classification models
- Hyperparameter tuning to improve performance
- Evaluating models using F1 score and AUC-ROC

---

## Model Evaluation

- **F1 score** is the primary evaluation metric due to class imbalance
- **AUC-ROC** is computed to assess the model’s ability to distinguish between classes
- A comparison between F1 and AUC-ROC is provided to analyze trade-offs between precision, recall, and overall discrimination power

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Outcome

The final notebook includes:
- A complete churn prediction pipeline
- Performance evaluation on the test dataset
- A clear comparison between F1 score and AUC-ROC
- Data-driven conclusions and recommendations

This project demonstrates practical experience in solving a real-world customer churn problem using machine learning.

