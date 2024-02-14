# Telecom_Churn_Case_study

> Analyzing the customer data of a telecom operator for three months in the year 2014, to identify variables that lead to churn. 
  The aim of the study is also to maximise the accuracy score by considering various ML models.

## Table of Contents

  - General information
  - Conclusions
  - Software used

## General Information:

  - The data in question is from a telecom company in the year 2014 and pertains to three months.
  - Data preprocessing and EDA was performed, NaN values were imputed accordingly, new features were derived, correlation charts and distribution plots were made to understand the data.
  - The data was split into train and test sets in the ratio 75:25. RFE and VIF were applied to reduce the feature vectors and multiple models were considered
  - The models considered were Logistic Regression, Logistic Regression with PCA and Random Forests.
  - Finally the models were used to predict on the test set.

## Conclusions:

  - The model using a random forest was selected as it offered the best prediction accuracy.
  - The accuracy were 97% on the train and ~92% on the test sets.
  - It was observed that outgoing calls, in particular when in roaming are the biggest predictors of churn,
    It is hence suggested for the telecom company to offer plans that target the outgoing call experience of consumers and improve their plans that cater to customers that are in roaming.

## Software

- Jupyter - version 3.9.13
- Visual studio code - version 1.83.0
- git - version 2.42.0

## Contact
Created by LeanderAntony - feel free to contact me on antony.leander@gmail.com
