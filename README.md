# CREDIT-CARD-FRAUD-DETECTION
Credit Card Fraud Detection: Utilizing machine learning to identify and prevent unauthorized and fraudulent credit card transactions.
# Credit Card Fraud Detection

## Overview
This Python project focuses on credit card fraud detection using machine learning. It leverages a dataset with transaction information to identify and prevent fraudulent transactions. The project follows these key steps:

## Data and Environment Setup
- Utilizes Python 3 environment with essential analytics libraries.
- Loads credit card transaction data from the provided CSV file.

## Data Exploration
- Analyzes the dataset's structure and statistics.
- Determines the data's class imbalance (only 0.17% fraudulent transactions).

## Model Development
- Prepares the data for training by separating features and labels.
- Splits the dataset into training and testing sets.
- Implements a Random Forest Classifier for fraud detection.

## Model Evaluation
- Evaluates the classifier's performance using various metrics:
  - Accuracy: 99.96%
  - Precision: 97.45%
  - Recall: 78.52%
  - F1 Score: 86.36%
  - Matthews Correlation Coefficient: 0.86907=0.87

## Confusion Matrix Visualization
- Visualizes the confusion matrix to understand model performance.
- Provides insights into true positives, true negatives, false positives, and false negatives.

## Conclusion
This project demonstrates the effectiveness of a Random Forest Classifier in detecting credit card fraud. It achieves high accuracy and precision, making it a valuable tool for financial security.
