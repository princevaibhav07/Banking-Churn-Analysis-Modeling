# Customer Churn Prediction for Banking Services
# Overview
This project aims to predict customer churn for a bank using machine learning models. Churn refers to the likelihood of customers discontinuing their banking services. By identifying the key factors that contribute to customer attrition, banks can proactively engage with customers to reduce churn and improve customer retention.

# Project Objective
Analyze the customer churn rate to understand why customers leave the bank.
Train machine learning models to predict the probability of churn and identify the most important factors influencing customer deactivation.
Recommend strategies to reduce customer churn based on model insights.
# Dataset
The dataset contains customer information from a bank, including demographic details, account features, and transactional behaviors. The key columns include:

CustomerID: Unique identifier for each customer
CreditScore: Credit score of the customer
Geography: Customer's country of residence
Gender: Gender of the customer
Age: Age of the customer
Tenure: Number of years the customer has been with the bank
Balance: Account balance
NumOfProducts: Number of products the customer has
HasCrCard: Whether the customer has a credit card (1 = Yes, 0 = No)
IsActiveMember: Whether the customer is an active member (1 = Yes, 0 = No)
EstimatedSalary: Customer's estimated salary
Exited: Whether the customer churned (1 = Yes, 0 = No)
# Models Used
Several machine learning models were explored, including:

Decision Tree Classifier
you can also use Random Forest Classifier ,Logistic Regression
The final model was selected based on the following metrics:

Accuracy: Evaluating the correctness of predictions on both training and test sets.
F1 Score, Precision, and Recall: Measuring the model’s ability to correctly identify churn while minimizing false positives.
AUC (Area Under the Curve): Assessing the model's discriminatory power between churned and non-churned customers.
# Key Findings
Top Features Influencing Churn: The most important factors identified by the model include Total Products, Age, IsActiveMember, Gender, and Geography.
Model Performance: The final model achieved:
90% accuracy on training data
85% accuracy on test data
F1 score, recall, and precision values near 0.8
An AUC score above 0.8, indicating strong discriminatory power.
# Recommendations
Encourage more products: Customers with fewer than two products are more likely to churn. Banks should encourage customers to hold at least two banking products.
Engage senior customers: Special schemes can be designed for older customers to reduce their likelihood of deactivating services.
Customer Retention Programs: Offer rewards and incentives, maintain regular communication, and improve digital services to keep customers engaged and active.

# Tools & Libraries Used
Python
Pandas and NumPy for data manipulation
Matplotlib and Seaborn for data visualization
scikit-learn for machine learning algorithms
