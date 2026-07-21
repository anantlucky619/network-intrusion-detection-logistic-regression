# Network Intrusion Detection using Logistic Regression | Orange Data Mining

## Project Overview

This project develops a machine learning model to identify potential cybersecurity intrusion attempts using Logistic Regression in Orange Data Mining. The objective is to classify network sessions as either normal or malicious based on network activity, authentication behavior, encryption methods, browser information, and IP reputation metrics.

The project follows a complete machine learning workflow, including data preprocessing, feature selection, missing value handling, normalization, model training, evaluation, and prediction. Model performance is assessed using 10-fold Cross Validation with industry-standard metrics such as Accuracy, Precision, Recall, F1-Score, AUC-ROC, Log Loss, ROC Curve, and Confusion Matrix.

## Business Problem

Organizations generate thousands of network sessions every day, making manual identification of malicious activity inefficient and error-prone. An automated classification model can help security teams detect suspicious sessions early, prioritize investigations, and reduce response time while minimizing false alarms.

## Dataset

* Records: 9,537 network sessions
* Features: 10 predictive variables
* Target Variable: `attack_detected` (Binary Classification)

Example features include:

* Network Packet Size
* Protocol Type
* Login Attempts
* Session Duration
* Encryption Used
* IP Reputation Score
* Failed Login Attempts
* Browser Type
* Unusual Time Access

## Project Workflow

* Data Import using Orange Data Mining
* Data Inspection and Validation
* Feature Selection
* Missing Value Treatment
* Data Normalization
* Logistic Regression Model Development
* 10-Fold Cross Validation
* Performance Evaluation
* Confusion Matrix Analysis
* ROC Curve Analysis
* Prediction of Attack Probability

## Tools & Technologies

* Orange Data Mining
* Logistic Regression
* Machine Learning
* Data Preprocessing
* Classification Analysis
* Cross Validation

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Area Under ROC Curve (AUC)
* Log Loss
* Confusion Matrix

## Key Outcome

The project demonstrates how machine learning can support cybersecurity operations by predicting potential intrusion attempts from historical network activity. It showcases practical skills in data preprocessing, supervised machine learning, model evaluation, and analytical interpretation using a no-code visual analytics platform.
