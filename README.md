# <p align=center> Assignment 5.1: Will the Customer Accept the Coupon?

## Quick links
* Link to the dataset used in this analysis can be found <a href="https://github.com/Cxpher/bankclassy/blob/main/data/bank-additional-full.csv">here</a>.
* Link to Jupiter Notebook containing code and visualization for the performed analysis can be found <a href="https://github.com/Cxpher/bankclassy/blob/main/prompt_III.ipynb">here</a>.
* Link to folder containing all saved visualized plots depicted in the Jupiter Notebook can be found <a href="https://github.com/Cxpher/bankclassy/tree/main/data/images">here</a>.

## Business problem aka Problem #4
My goal is to conduct a classification exercise with different models to predict whether the client will subscribe a term deposit accurately.

## Problem #1: Understanding the Data
### To gain a better understanding of the data, please read the information provided in the UCI link above, and examine the Materials and Methods section of the paper. How many marketing campaigns does this data represent?

It represents 17 marketing campaigns!

## Problem 7: A Baseline Model
### Before we build our first model, we want to establish a baseline. What is the baseline performance that our classifier should aim to beat?

It should have a baseline performance of at least 80% accuracy

## Problem 10: Model Comparisons
### Now, we aim to compare the performance of the Logistic Regression model to our KNN algorithm, Decision Tree, and SVM models. Using the default settings for each of the models, fit and score each. Also, be sure to compare the fit time of each of the models. Present your findings in a DataFrame similar to that below:

###Model	Train Time	Train Accuracy	Test Accuracy
###.	.

                 Model  Train Time  Train Accuracy  Test Accuracy
0  Logistic Regression      0.0269          0.8998         0.9012
1                  KNN      0.0014          0.9115         0.8955
2        Decision Tree      0.1099          0.9954         0.8410
3                  SVM     26.1599          0.9092         0.9003

## Problem 11: Improving the Model
### Now that we have some basic models on the board, we want to try to improve these. Below, we list a few things to explore in this pursuit.
### More feature engineering and exploration. For example, should we keep the gender feature? Why or why not?
### Hyperparameter tuning and grid search. All of our models have additional hyperparameters to tune and explore. For example the number of neighbors in KNN or the maximum depth of a Decision Tree.
### Adjust your performance metric

Not sure if this was a trick question but there was never a gender feature to begin with!

## Table of findings - Concluding hypothesis

|No. | Findings | Remarks |
|:--- |:---	  |:---      |
|1.  | KNN and SVM models seem to perform the best both on the training and test sets. |      |		
|2.  | SVM takes very long to train compared to the rest. |      |
|3.  | Other accuracy scoring mechanisms seems to have an effect on hyperparameters for the model (eg. KNN with accuracy vs F1. |      |
