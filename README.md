# Logistic-Regression
Logistic Regression for Diabetes Prediction

# Project Overview

This project implements Logistic Regression from scratch using Python and NumPy to predict whether a person has diabetes based on medical attributes. The model is trained using a dataset containing health-related features such as glucose level, BMI, blood pressure, and age.

The objective of the project is to understand the working of logistic regression, gradient descent optimization, and model evaluation without relying on machine learning libraries such as scikit-learn.

# Dataset

The model is trained using the Diabetes dataset (diabetes2.csv) which contains medical diagnostic measurements.

# Features in the dataset

• Pregnancies

• Glucose

• Blood Pressure

• Skin Thickness

• Insulin

• BMI

• Diabetes Pedigree Function

• Age

# Target Variable

 Outcome

• 0 → Non-diabetic

• 1 → Diabetic

# Technologies Used

• Python

• NumPy

• Pandas

• Google Colab

# Project Workflow
1. Data Loading

The dataset is loaded using Pandas and converted into feature matrix X and target vector Y.

2. Data Preprocessing

• Training and testing data split

• Feature normalization using mean and standard deviation

• Adding bias term to the feature matrix

3. Logistic Regression Implementation

The logistic regression model is implemented from scratch including:

• Sigmoid function

• Gradient Descent optimization

• Weight parameter updates

• Cost function calculation

4. Model Training

The model is trained for multiple epochs using gradient descent to minimize the loss function.

5. Model Evaluation

The model performance is evaluated using:

• Confusion Matrix

• Accuracy

• Precision

• Recall

• Model Evaluation Metrics

The following metrics are calculated to evaluate the classification performance:

• True Positives (TP)

• True Negatives (TN)

• False Positives (FP)

• False Negatives (FN)

• Accuracy

• Precision

• Recall

# Learning Outcomes

Through this project, the following concepts were implemented and understood:

• Logistic Regression algorithm

• Gradient Descent optimization

• Feature normalization

• Binary classification

• Confusion matrix and evaluation metrics

• Implementation of ML algorithms without external ML libraries
