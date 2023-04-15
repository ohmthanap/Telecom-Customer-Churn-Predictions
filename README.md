# Churn Predictions Telecom Customer
 
1. Introduction

    This is the final project, named "Telco Customer Churn Prediction", for the course "CS 513 - Knowledge Discovery and Data Mining" at Stevens Institute of Technology. The project was conducted in collaboration among three Computer Science students, namely Shiva Rama Krishna Mandadapu, Hantao Gao, and Thanapoom Phatthanaphan. 
 
    The objective of the project is to provide a comprehensive overview of Data Exploratory and Analysis (EDA) principles, specifically for analyzing all relevant customer data of a telecommunications company. This process aims to gain a clear understanding of the dataset. Additionally, the project will involve the implementation of nine different machine learning models to predict whether a customer is likely to churn (leave) a telecommunications company's service or not. Furthermore, we will evaluate the performance of each model by presenting the classification report and confusion matrix to determine the optimal one.

2. Problem Statement
 
    Develop a classification model to predict whether a customer will churn (leave) a telecommunications company’s service or not

3. Dataset Description
    
    The dataset contains information on telecom customers such as their demographics, usage patterns, and account information. The target variable is  whether the customer churned (1) or not (0). The dataset has 7,043 observations and 20 input features.
    - Customers who left within the last month – the column is called Churn
    - Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
    - Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
    - Demographic info about customers – gender, age range, and if they have partners and dependents

    Source of Dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

4. Implementation Strategy and Algorithms used
    1. Decision Trees
    2. Naive Bayes Classifier
    3. AdaBoost Classifier
    4. Multilayer Perceptron
    5. Bagging along with Random Forest
    6. K-nearest neighbor with Grid Search CV
    7. Logistic Regression with Grid Search CV
    8. Random Forest with Randomized Search CV
    9. Support Vector Machine with Grid Search CV
