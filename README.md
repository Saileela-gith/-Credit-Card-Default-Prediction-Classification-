1.Project Overview
Credit card default prediction is an important problem in the financial industry. Banks and financial institutions need to identify customers who are likely to default on their payments.
This project builds a machine learning classification model that predicts whether a customer will default on their credit card payment using historical financial data.
The system helps financial institutions reduce risk and improve credit decision making.
2. Dataset
Dataset used: UCI Credit Card Default Dataset
The dataset contains 30,000 credit card customer records with features such as:
-Credit limit
-Gender
-Education level
-Marital status
-Age
-Payment history
-Bill statements
-Previous payment
-Target variable:
#default.payment.next.month
1 → Default
0 → No Default
Project Workflow
# Data Preprocessing
Data cleaning
Handling missing values
Feature scaling
Train-test split
#Exploratory Data Analysis
Distribution of customer demographics
Payment behavior analysis
Default vs Non-default comparison
# Model Training
Multiple machine learning models were trained:
Logistic Regression
Random Forest
XGBoost
Neural Networks
#Model Evaluation
Models were evaluated using:
Accuracy
Precision
Recall
F1 Score
ROC-AUC
#Results
Model	Accuracy
Logistic Regression	80%
Random Forest	82%
XGBoost	85%
Neural Network	84%
Best Performing Model: XGBoost
#Technologies Used
Python
Pandas
NumPy
Scikit-learn
XGBoost
TensorFlow / Keras
Matplotlib
Seaborn
Google Colab
