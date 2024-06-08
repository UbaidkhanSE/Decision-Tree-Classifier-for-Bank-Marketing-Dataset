# Decision-Tree-Classifier-for-Bank-Marketing-Dataset
This repository contains a comprehensive implementation of a Decision Tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used is the Bank Marketing dataset.

# Dataset
The dataset contains various features related to customers' demographic and behavioral information. The target variable is whether the customer has purchased the product (y).

# Features
age: Age of the customer
job: Type of job
marital: Marital status
education: Level of education
default: Has credit in default?
balance: Average yearly balance
housing: Has a housing loan?
loan: Has a personal loan?
contact: Contact communication type
day: Last contact day of the month
month: Last contact month of year
duration: Last contact duration
campaign: Number of contacts performed during this campaign
pdays: Days since the client was last contacted from a previous campaign
previous: Number of contacts performed before this campaign
poutcome: Outcome of the previous marketing campaign
y: Has the client subscribed to the product? (Target variable)
# Project Structure
bank.csv: The dataset file.
decision_tree_classifier.py: Python script with the implementation.
README.md: This file.
# Implementation Details
The implementation includes the following steps:

Data Loading: Load the dataset using Pandas.
Data Preprocessing: Encode categorical variables, split the data into features and target, and apply SMOTE for handling imbalanced data.
Model Training: Use GridSearchCV to find the best hyperparameters for the Decision Tree classifier and train the model.
Model Evaluation: Evaluate the model using accuracy, classification report, and confusion matrix.
Visualization: Visualize the Decision Tree, feature importance, and confusion matrix.
# Prerequisites
Python 3.x
Pandas
Scikit-learn
Imbalanced-learn
Matplotlib
Seaborn
Installation
Clone the repository:

# Results
Accuracy: The model achieves an accuracy of 0.89 on the test set.
Classification Report: Detailed precision, recall, and f1-score for each class.
Confusion Matrix: Visual representation of the model's performance.
# Visualization
Decision Tree: Visual representation of the trained Decision Tree.
Feature Importance: Bar plot showing the importance of each feature.
Confusion Matrix: Heatmap of the confusion matrix.
# Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
