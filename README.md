# **Credit Card Fraud Detection using Sampling Techniques and Machine Learning Models** 

## Overview

This project investigates different sampling techniques to address the issue of class imbalance in datasets. The Credit Card Fraud Detection dataset is used as a case study. We apply five sampling methods to balance the dataset and train five machine learning models to evaluate their effectiveness in identifying fraudulent transactions.

## Dataset

The dataset used in this project is available for download from the following link: [Credit Card Data CSV](https://github.com/AnjulaMehto/Sampling_Assignment/blob/f0c491556cded07517283c75e603bccb70112c26/Creditcard_data.csv).

## Data Description

- Class: Target variable, where 1 indicates a fraudulent transaction, and 0 indicates a legitimate transaction.

- V1 to V28: Features derived from the original dataset, representing various transaction details.

## Objective

- Load the dataset and handle the class imbalance problem using sampling techniques.
- Apply five different sampling strategies to the dataset.
- Evaluate the effectiveness of these techniques using five machine learning algorithms.
- Compare and analyze results to determine the most effective combination for detecting fraud.

## Sampling Techniques

- Random Undersampling: Reduces the majority class size by randomly selecting a subset of examples.

- Random Oversampling: Increases the minority class size by duplicating its examples.

- Tomek Links: Removes overlapping instances between the majority and minority classes.

- SMOTE (Synthetic Minority Oversampling Technique): Creates synthetic examples for the minority class.

- NearMiss: Selects majority class examples that are closest to the minority class examples.

## Machine Learning Models

- Logistic Regression (LogReg)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Each model was trained and tested with all five sampling techniques, and accuracy was used as the primary evaluation metric.

## Results Summary
The performance of each sampling technique with various machine learning models is summarized in the table below:

![My Image](image.png)

## Key Insights

- Random Forest with Random Oversampling and Smote yielded the highest accuracy of 1.000, making it the most effective combination for detecting fraudulent transactions.
- Tomek Links with SVM and Random Oversampling with KNN also demonstrated strong performance, showcasing their potential in handling imbalanced datasets effectively.
