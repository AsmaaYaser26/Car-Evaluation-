# Car-Evaluation-
Machine Learning Car Classification on the Car Evaluation Database for predicting car acceptability


## Introduction

This project is based on the Car Evaluation Database, a popular dataset used in machine learning and data mining. The database evaluates cars according to several attributes such as buying price, maintenance price, number of doors, capacity in terms of persons to carry, the size of luggage boot, and estimated safety of the car.

The goal of this project is to classify cars into four different categories based on these attributes.

## Data

The data used in this project is the Car Evaluation Database, which directly relates CAR to six input attributes: buying, maint, doors, persons, lug_boot, safety. The dataset is available on platforms like Kaggle: https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set
and UCI Machine Learning Repository.

## Methodology

I used three machine learning algorithms for this classification task:

1. **Logistic Regression**: Logistic Regression is a statistical model that uses a logistic function to model a binary dependent variable.

2. **XGBoost**: XGBoost is an optimized distributed gradient boosting library designed to be highly efficient, flexible, and portable.

3. **Random Forest**: Random Forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting.

## Results

After training our models on the Car Evaluation Database, we evaluated their performance using a separate test set. Here are the results:

1. **Logistic Regression**: The logistic regression model achieved an accuracy of 81%.

2. **XGBoost**: The XGBoost model outperformed the logistic regression model with an accuracy of 98%.

3. **Random Forest**: The random forest model had comparable results with an accuracy of 96%.
   

## Conclusion

From our analysis, it is clear that the XGBoost model performed the best on the Car Evaluation Database, closely followed by the Random Forest model. The logistic regression model, while simpler, was not able to capture the complexity of the data as well as the other two models.

These results highlight the importance of choosing the right algorithm for the task at hand. While logistic regression is a powerful tool, it may not always be the best choice for complex, non-linear data.

