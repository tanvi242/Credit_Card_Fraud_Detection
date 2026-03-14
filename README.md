Credit Card Fraud Detection using Machine Learning
Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Fraud detection is crucial for financial institutions to prevent financial losses and identify suspicious activities in real time.

The goal of this project is to build a machine learning model that can classify transactions as fraudulent or legitimate based on transaction features.

Dataset

The dataset contains information about credit card transactions including details such as transaction amount, type, and location.

Features in the dataset include:

TransactionID

TransactionDate

Amount

MerchantID

TransactionType

Location

IsFraud (Target variable)

Where:

0 → Legitimate transaction

1 → Fraudulent transaction

Project Workflow
1. Data Preprocessing

Loading dataset using Pandas

Handling missing values

Dropping irrelevant columns

Encoding categorical variables

2. Exploratory Data Analysis (EDA)

Fraud vs Normal transaction distribution

Data visualization using Seaborn and Matplotlib

3. Handling Imbalanced Data

Fraud detection datasets often have very few fraud cases compared to normal transactions.

To solve this issue, SMOTE (Synthetic Minority Over-sampling Technique) was used to balance the dataset.

4. Machine Learning Models Used
Logistic Regression

Used as a baseline model for classification.

Random Forest Classifier

An ensemble learning method that combines multiple decision trees to improve prediction performance.

5. Model Evaluation

The model performance was evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

ROC Curve

AUC Score

These metrics help measure how effectively the model detects fraudulent transactions.

Visualization

The project includes several visualizations to understand the data and model performance:

Fraud vs Legitimate transaction distribution

Confusion matrix heatmap

ROC Curve

Feature importance plot

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

Joblib

Project Structure
Credit-Card-Fraud-Detection
│
├── Credit_card_fraud_detection.ipynb
├── fraud_detection_model.pkl
├── dataset.csv
└── README.md
Model Saving

The trained model was saved using Joblib so it can be reused later in applications such as:

Fraud detection APIs

Web applications

Real-time monitoring systems

Future Improvements

Hyperparameter tuning

Testing additional models (XGBoost, Gradient Boosting)

Building a real-time fraud detection dashboard

Deploying the model using Flask or Streamlit

Conclusion

This project demonstrates how machine learning can be used to detect fraudulent financial transactions. By analyzing transaction patterns, the model can help identify suspicious activities and assist financial institutions in improving transaction security.

Author

Tanvi Jitendra Bhosale
BCA Student | AI & Cloud Enthusiast | Machine Learning Projects
