💳 Credit Card Fraud Detection

📌 Project Overview

This project implements a machine learning-based system to detect fraudulent credit card transactions. Fraud detection is a critical problem for financial institutions, as unauthorized transactions can lead to significant financial losses.

The goal of this project is to analyze transaction data and build a model that can accurately classify transactions as fraudulent or legitimate using machine learning algorithms.

📊 Dataset

The dataset contains information about credit card transactions including transaction details such as amount, type, location, and fraud label.

Target variable

IsFraud
0 → Legitimate transaction
1 → Fraudulent transaction

Fraud detection datasets are typically highly imbalanced, meaning fraudulent transactions are much fewer compared to legitimate ones, making the classification task challenging.

⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

Joblib

🔎 Project Workflow
1️⃣ Data Preprocessing

Loading dataset

Handling missing values

Dropping irrelevant columns

Encoding categorical variables

2️⃣ Exploratory Data Analysis

Fraud vs normal transaction distribution

Visualizing transaction patterns

3️⃣ Handling Imbalanced Data

To improve model performance on fraud cases, SMOTE (Synthetic Minority Over-sampling Technique) was applied to balance the dataset.

4️⃣ Model Training

Two machine learning models were used:

Logistic Regression – baseline classification model

Random Forest Classifier – ensemble model for improved prediction performance

5️⃣ Model Evaluation

Model performance was evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

ROC Curve

Feature Importance

📈 Results

The trained model learns patterns in transaction data and identifies suspicious transactions that may indicate fraudulent activity.

Key evaluation methods used:

Confusion Matrix visualization

ROC curve analysis

Feature importance analysis

💾 Model Saving

The trained model was saved using Joblib so it can be reused later in applications such as fraud detection systems or APIs.

🚀 Future Improvements

Possible improvements for this project include:

Hyperparameter tuning

Using advanced models (XGBoost, LightGBM)

Building a real-time fraud detection API

Deploying the model with Flask or Streamlit

👩‍💻 Author

Tanvi Jitendra Bhosale
BCA Student | Machine Learning & AI Enthusiast
