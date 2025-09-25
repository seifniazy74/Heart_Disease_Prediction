# Heart Disease Prediction Project

This project aims to build a predictive system for heart disease diagnosis using machine learning techniques. The notebook walks through the entire process, from data loading and exploration to model training and evaluation.

## Project Overview

- **Objective:** Predict whether a person has heart disease based on clinical and demographic features.
- **Dataset:** The data consists of patient records with features such as age, sex, chest pain type, blood pressure, cholesterol, and more, along with a target variable indicating the presence of heart disease.

## Notebook Structure

1. **Importing Libraries:** Essential Python libraries for data manipulation, visualization, and machine learning are imported.
2. **Data Loading & Exploration:** The dataset is loaded and explored to understand its structure, check for missing values, duplicates, and outliers.
3. **Data Visualization:** Various plots are used to visualize feature distributions and relationships with the target variable.
4. **Outlier Handling:** Outliers in numerical features are detected and handled to improve model performance.
5. **Data Preparation:** Features and target are separated, and the data is split into training and testing sets.
6. **Model Training:** A Logistic Regression model is trained on the processed data.
7. **Model Evaluation:** The model's predictions are evaluated using accuracy score, confusion matrix, and visualizations.
8. **Predictive System:** A sample input is used to demonstrate how the trained model can predict heart disease for new data.

## Key Steps & Techniques

- **Data Cleaning:** Removal of duplicates and handling of missing values.
- **Visualization:** Use of seaborn and matplotlib for insightful plots.
- **Outlier Treatment:** Median imputation for outlier values.
- **Machine Learning:** Logistic Regression for binary classification.
- **Evaluation Metrics:** Accuracy score, confusion matrix, and classification report.

## Results

- The model achieves a reasonable accuracy in predicting heart disease.
- Visualizations and metrics provide insights into model performance and data characteristics.

## Conclusion

This notebook provides a complete workflow for building a heart disease prediction system, demonstrating best practices in data science and machine learning. The approach can be extended with more advanced models and feature engineering for improved accuracy.
