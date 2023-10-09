<div align="center">

  <h1>Challenge for BIP Group</h1>
  <h1>Construction of a predictive churn model</h1>
</div>

## Goals.

The main objective is to build a predictive churn model for a telecom company. Churn is understood as the percentage of customers who leave the telecom company to switch to a competitor.

- Estimate which variables are potentially more significant for modeling.
- Create at least one relevant visualization.
- Generate a new binary categorical variable that somehow groups customers by consumption levels.

When building a model to predict churn for the dataset, cover at least one of the following options:
1. Logistic regression + ridge regularization + lasso regularization
2. Logistic regression + second-order polynomial logistic + regularization of your choice
3.  Logistic regression + random forest or ensemble model of your choice

## Data. 

The test dataset can be found in the "churn_dataset.zip" file. Inside, you will find three plain text files:

- churn.all: Contains the complete dataset.
- churn.data and churn.test: These files contain the same data as the previous one but divided into training and test datasets.


## Tools.

1. Sklearn Models.
  * xgboost
  * LogisticRegression
  * Lasso

2. Sklearn Metrics.
  * accuracy_score
  * confusion_matrix
  * classification_report
  * precision_recall_curve

3. Seaborn.
4. Pandas.
