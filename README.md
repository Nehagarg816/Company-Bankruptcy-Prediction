# Company-Bankruptcy-Prediction
The project focuses on predicting the likelihood of a company going bankrupt using a Machine Learning ALgorithm. The data set is fetched from Kaggle including various observed data of past years, and the goal was to predict the same with the highest possible accuracy.

# Introduction
Company Bankruptcy Prediction is a precise prediction of whether a company will be bankrupt using the Logistic Regression model, a Machine Learning Algorithms classification model.

# Exploratory Data Analysis (EDA)
EDA involves the distribution of bankruptcy and non-bankruptcy classes in the dataset. It includes visualizing the distribution in the form of a bar plot.

![eda](https://github.com/Nehagarg816/Company-Bankruptcy-Prediction/assets/111566521/b70a5388-0dbc-4ee9-9e9d-5e52dfc7f8b1)

Here from the above graph, we can observe that the number of non-bankrupt companies is more than bankrupt companies

# Model Selection
The logistic regression model is employed for predictions.

# Model Training
The SimpleImputer classifier is employed to train the data in categories. SimpleImputer is a class in the sklearn. impute module that can be used to replace missing values in a dataset, using a variety of input strategies.

# Model Evaluation
The performance of the Model is evaluated using recall_score, precison_score, accuracy_score, and f1_score. The Accuracy score predicted after predictions was 93.29% (approx.).

![image](https://github.com/Nehagarg816/Company-Bankruptcy-Prediction/assets/111566521/57d2afa3-6621-44da-83b7-431a156ca72f)
