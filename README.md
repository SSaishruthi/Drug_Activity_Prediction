# Drug_Activity_Prediction

## Problem Statement

Determine whether a compound is active (1) or not (0).

## Solution

Feature selection method is implemented to reduce dimension and consider only important
feature for prediction. Using selected features different classifiers are validated for maximum F1
score as the data is highly imbalanced.

## Challenge

Dataset is completely unbalanced

## Methodology
1.	Splitting train data into train and validation set. It is split in the same ratio as training data 
2.	Perform dimensionality reduction
3.	Perform cross validation and check F1 score
4.	Validate F1 score of set of classifiers 

Detailed report added to the repo

