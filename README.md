# Android Health Check Project

## Overview

Welcome to the Android Health Check project! This repository contains code for a Machine Learning project aimed at predicting android operating system health-related outcomes based on a dataset with 215 features and 1 target variable.

## Data Preprocessing

- **Features:** 215
- **Target Variable:** 1

The dataset has undergone preprocessing, including handling missing values by replacing them with NaN and subsequently dropping those rows.

## Feature Selection

To enhance model efficiency and interpretability, the top 30 features were selected using the SelectKBest function.

## Data Splitting

The dataset was divided into training and testing sets with an 80-20 split, respectively.

## Machine Learning Algorithms

The following machine learning algorithms were employed to build predictive models:

1. Random Forest Classifier
2. Gradient Boosting Classifier
3. Support Vector Machine - Linear Kernel
4. Support Vector Machine - RBF Kernel
5. K-Nearest Neighbors
6. Multi-Layer Perceptron Classifier
7. Gaussian Naive Bayes
8. Logistic Regression
9. Decision Tree Classifier
10. Adaptive Boosting Classifier
11. XGBoost Classifier

## Evaluation Metrics

For each algorithm, the model performance was evaluated using the following metrics:

- Accuracy
- Classification Report
- Confusion Matrix
- ROC Curve

These metrics provide a comprehensive understanding of the model's performance and its ability to predict health outcomes accurately.

## Instructions for Running the Code

1. Ensure you have the necessary dependencies installed.
2. Clone the repository to your local machine.
3. Run the code provided in the respective algorithm files.

Feel free to explore and contribute to the Android Health Check project. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.

Happy coding! 🚀
