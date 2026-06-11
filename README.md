# PRODIGY_DS_03
Task 3: Decision Tree classifier 
🌳 PRODIGY INFOTECH – Data Science Internship Task 03
Decision Tree Classifier for Customer Purchase Prediction
📌 Overview

This project focuses on building a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The model is trained using the Bank Marketing Dataset, which contains customer information collected during direct marketing campaigns.

The objective is to classify customers into two categories:

Yes – Customer subscribed to the term deposit.
No – Customer did not subscribe to the term deposit.
🎯 Objective
Perform data preprocessing and encoding of categorical variables.
Train a Decision Tree Classification model.
Evaluate model performance using accuracy metrics.
Visualize the generated decision tree for better interpretability.
📂 Dataset

Bank Marketing Dataset

The dataset contains customer-related attributes such as:

Age
Job
Marital Status
Education
Account Balance
Housing Loan
Personal Loan
Contact Type
Campaign Information
Previous Marketing Outcomes
Subscription Status (Target Variable)
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
📊 Project Workflow
1. Data Loading
Import the dataset using Pandas.
Inspect data structure and feature types.
2. Data Preprocessing
Handle categorical variables using Label Encoding.
Separate features and target variable.
3. Train-Test Split
Split dataset into training and testing sets using an 80:20 ratio.
4. Model Building
Train a Decision Tree Classifier on the processed dataset.
5. Model Evaluation
Predict outcomes on test data.
Calculate classification accuracy.
6. Visualization
Plot the Decision Tree structure for interpretation and analysis.
📈 Results

The trained Decision Tree model achieved:

Accuracy: 87.51%

This indicates that the model effectively predicts customer subscription behavior based on the available features.
