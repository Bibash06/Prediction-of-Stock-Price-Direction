# Prediction-of-Stock-Price-Direction
## Table of Contents

1. [Assignment](#assignment)
2. [Data Exploration](#data-exploration)
3. [Feature Engineering](#feature-engineering)
4. [Classical Machine Learning Algorithms](#classical-machine-learning-algorithms)
   - [Logistic Regression](#logistic-regression)
   - [Decision Tree](#decision-tree)
   - [Random Forest](#random-forest)
   - [Gradient Boosting Ensemble](#gradient-boosting-ensemble)
5. [Deep Learning Algorithm](#deep-learning-algorithm)
6. [Conclusion](#conclusion)


---

## Assignment
The task is to predict the day price direction of Amazon.com, Inc. (AMZN). The goal is a binary classification of whether the next day's closing price will be higher than the opening price. The dataset spans from 1997 to 2020, split into training (1997-2016), validation (2016-2018), and testing (2018-2020) periods. Dataset files: AMZN_train.csv, AMZN_val.csv, and AMZN_test.csv.
The stock market is very complex and highly volatile. In order to be profitable, we do not need to predict the correct price, but rather, the price direction: whether it will be higher or lower than the price that is today. If we predict it to be higher, we might as well buy some stocks, else, we should probably sell.
Therefore, the target would be a binary classification of whether the next-day closing price will be higher than the opening price.


### Data Exploration

In our initial exploration, we load the datasets and analyze the data attributes. We plot stock prices over time and explore trends.

...

## Conclusion

The gradient boosting classifier yielded the best AUC score on the validation set. The next section evaluates its performance on the test set and includes a feature importance analysis.

This README provides a comprehensive overview of the data project, from initial exploration to classical machine learning and deep learning models, concluding with the best-performing model's evaluation on the test set and feature importance analysis.
