# 📩 SMS Spam Predictor

A machine learning project that classifies SMS messages as **Spam** or **Ham** using natural language processing and the **Naive Bayes algorithm**.

## 🚀 Project Overview

This project uses a dataset of 5,572 SMS messages labeled as spam or ham. It involves:

- Data cleaning and preprocessing (lowercasing, stopword removal, stemming)
- Text vectorization using **TF-IDF**
- Training a **Multinomial Naive Bayes** classifier
- Evaluating performance using accuracy, precision, recall, and F1-score

## 📂 Folder Structure
sms-spam-project/
│
├── data/
│ └── spam.csv
│
├── notebooks/
│ └── sms_spam_detection.ipynb

## 📊 Model Performance
    
                Confusion Matrix:
 [[965   0]
 [ 24 126]]
    
    Classification Report:
               precision    recall  f1-score   support

           0       0.98      1.00      0.99       965
           1       1.00      0.84      0.91       150

    accuracy                           0.98      1115
   macro avg       0.99      0.92      0.95      1115
weighted avg       0.98      0.98      0.98      1115

Overall Accuracy: 97.84%
Weighted Avg F1-score: 0.98


