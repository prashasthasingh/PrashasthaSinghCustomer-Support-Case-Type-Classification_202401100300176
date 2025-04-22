# PrashasthaSinghCustomer-Support-Case-Type-Classification_202401100300176
# Customer Support Case Type Classification

This project classifies customer support cases into one of three categories: **billing**, **technical**, or **general** using machine learning techniques. It includes model training, evaluation, and visualization using a confusion matrix heatmap.

## 📁 Dataset

The dataset includes:
- `message_length`: The number of characters in the customer's message.
- `response_time`: Time taken by support to respond (in minutes).
- `case_type`: The labeled category (`billing`, `technical`, or `general`).

## 🧠 Model

A **Random Forest Classifier** is used for this multiclass classification problem. The model is evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **Confusion Matrix Heatmap**

## 📊 Results

The classifier achieved:
- **Accuracy**: 55%
- **Precision**: ~57.8%
- **Recall**: 55%

Confusion matrix visualization helps understand per-class performance.


