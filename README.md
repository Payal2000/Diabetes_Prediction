# Diabetes_Prediction
This repository contains an exploratory data analysis (EDA) and modeling of diabetes risk factors using a publicly available dataset. The goal of this project was to investigate the factors that contribute to the risk of diabetes and to develop predictive models to classify individuals based on their diabetes status.

Introduction
--
Diabetes is a prevalent medical condition that affects a significant portion of the population. Identifying risk factors associated with diabetes can contribute to early diagnosis and preventive measures. In this project, we conducted an in-depth analysis to understand how various factors correlate with diabetes risk.

Dataset
---
The dataset used in this project contains information about individuals' health attributes and whether they have been diagnosed with diabetes or not. The dataset includes features such as BMI (Body Mass Index), cholesterol levels, difficulty in walking, high blood pressure, general health perception, and more.

Exploratory Data Analysis
--
The key exploratory data analysis tasks performed include:

-Correlation analysis to identify variables that correlate with diabetes risk.

-Visualization of the distribution of diabetes cases by age group and gender.

-Examination of the relationship between diabetes and specific health attributes.

Modeling
---
To predict diabetes risk based on the available attributes, we employed two machine learning models: Logistic Regression and Decision Trees. 
Here's an overview of the modeling process:

-Splitting the dataset into training and testing sets using train_test_split.

-Training a Logistic Regression model with various solvers and selecting the best-performing one.

-Employing GridSearchCV to tune hyperparameters for the Decision Tree model.

-Comparing the accuracy and F1 score of both models.






