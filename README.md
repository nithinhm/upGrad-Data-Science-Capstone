# upGrad Data Science Bootcamp - Capstone Project

## FindDefault (Prediction of Credit Card Fraud)

### Overview:
Welcome to the repository for my capstone project for the upGrad Data Science Bootcamp. In this project, I worked on predicting credit card fraud using machine learning techniques.

### Problem Statement:
Credit card fraud is a serious issue that can lead to financial losses for both customers and credit card companies. The goal of this project is to build a classification model that can predict whether a credit card transaction is fraudulent or not.

### Dataset:
The dataset contains transactions made by credit cards in September 2013 by European cardholders. It consists of 284,807 transactions, out of which 492 are frauds. The dataset is highly unbalanced, with frauds accounting for only 0.172% of all transactions.

### Features:
The dataset contains 29 attributes, including 'Time', 'Amount', and 'Class'. The 'Time' attribute represents the seconds elapsed between each transaction and the first transaction in the dataset. The 'Amount' attribute represents the transaction amount. The 'Class' attribute is the response variable, taking a value of 1 in case of fraud and 0 otherwise.

Most features (V1, V2, ... V28) have undergone PCA (Principal Component Analysis) transformation due to confidentiality issues. PCA is a technique used for dimensionality reduction, which is particularly useful when dealing with datasets with a large number of features. By reducing the number of features, we can improve the efficiency of our machine learning models.

### Approach:
I used machine learning techniques, including XGBoost Classifier and Random Forest Classifier, to build a classification model for predicting credit card fraud. Due to the highly unbalanced nature of the dataset, I employed techniques such as oversampling and undersampling to balance the classes. I also used cross-validation to evaluate the performance of the model.

### Conclusion:
In conclusion, this project demonstrates the use of machine learning techniques to predict credit card fraud. By building a classification model, we can help credit card companies identify fraudulent transactions and take appropriate action to minimize financial losses.

### Repository Structure:
- `/data`: Contains the dataset used for the project.
- `/notebooks`: Contains Jupyter notebooks with the code for data preprocessing, model building, and evaluation.
- `/visuals`: Contains visualizations saved during data analysis and model building.
- `models`: Contains saved models in pickle format.

Feel free to explore the repository and reach out to me if you have any questions or feedback. Thank you for visiting!