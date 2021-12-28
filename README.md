# Churn_Prediction_Classification-Algorithms
Classification Algorithms

## Abstract
### AFA Company

The goal of this project is to use classification models to predict customers who are going to churn from a Telecom company called AFA. Predicting future churn rate will assist the AFA company to identify and improve areas where customer service is lacking. In addition to gaining a better understanding of future expected revenue.

## Design

The project uses data of AFA company to build the classification models contains several features such as customer ID, gender, monthly charges, payment method...etc. We used a Random Forest, Decision Tree, KNN, Ada Boost, Naive Bayes, Logistic Regression and SVM to predict the customer churn.

## Data
The dataset contains information around 8000 customers of a telecom company. There are numeric columns and categorical columns. There are several types of contracts and payment methods.

## Algorithms

### Feature Engineering

1-Separating numeric and categorical columns.

2-Converting categorical features to binary dummy variables.

3-Combining dummies and ranges of numeric features to gain clear insights during EDA. 

4-Calculating correlation between features and Churn label.

5-Creating several data visualizations to build an understanding of the properties of data features.

### Model Evaluation and Selection

The dataset was split into 80/20 train vs. test, and all scores reported below were calculated with 10-fold cross validation:
