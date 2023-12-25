# Heart Disease Prediction - Handling Imbalanced Data

## Overview
This project aims to predict heart disease using various classification models. A crucial challenge in the dataset is the presence of imbalanced data, where one class significantly outweighs the other. To address this issue, several methods are employed, including oversampling, cross-validation with oversampling, ADASYN (Adaptive Synthetic Sampling), and undersampling. The classification models used for prediction are Logistic Regression, Decision Tree, and Random Forest.

## Repository Contents

1. **Data Description:**
   - Explore the dataset to understand the features and the target variable.

2. **Handling Imbalanced Data:**
   - **Oversampling:**
     - Duplicate instances of the minority class to balance the class distribution.
   - **Cross-Validation with Oversampling:**
     - Apply oversampling techniques during cross-validation to prevent data leakage.
   - **ADASYN (Adaptive Synthetic Sampling):**
     - Generate synthetic samples for the minority class based on the data distribution.
   - **Undersampling:**
     - Reduce the number of instances in the majority class to balance the dataset.

3. **Classification Models:**
   - **Logistic Regression:**
     - Implement logistic regression for binary classification.
   - **Decision Tree:**
     - Utilize a decision tree classifier for heart disease prediction.
   - **Random Forest:**
     - Employ a Random Forest classifier for enhanced predictive performance.

## Instructions

1. **Data Preparation:**
   - Ensure your dataset is structured with the required features and target variable.

2. **Handling Imbalanced Data:**
   - Run each script for oversampling, cross-validation with oversampling, ADASYN, and undersampling to preprocess the data.

3. **Classification Models:**
   - Execute each modeling script (Logistic Regression, Decision Tree, Random Forest) to train and evaluate the respective classifiers.

4. **Results and Analysis:**
   - Review the generated results, model performance metrics, and analysis in each script.
