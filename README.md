# CreditWise Loan Approval Prediction

An end-to-end supervised machine learning project that predicts whether a loan application is likely to be approved based on applicant and financial attributes.

The project demonstrates the complete machine learning workflow — from data exploration and preprocessing to feature engineering, model training, evaluation, and comparison.

## 🚀 Project Overview

Credit approval is a binary classification problem where financial institutions need to determine whether an applicant is eligible for a loan.

This project builds and compares multiple classification algorithms:

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Naive Bayes

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA)
- Understand applicant and loan-related features
- Handle missing and inconsistent data
- Perform data preprocessing
- Apply feature engineering
- Prepare data for binary classification
- Train multiple machine learning models
- Compare model performance
- Evaluate classification results

---

## 🧠 Machine Learning Pipeline

```text
Raw Loan Data
      │
      ▼
Data Exploration
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Feature Encoding / Scaling
      │
      ▼
Train / Test Split
      │
      ├──────────────┬──────────────┐
      ▼              ▼              ▼
     KNN       Logistic Regression  Naive Bayes
      │              │              │
      └──────────────┼──────────────┘
                     ▼
              Model Evaluation
                     │
                     ▼
          Precision / Recall / F1
                     │
                     ▼
             Model Comparison
