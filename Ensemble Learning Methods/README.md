# Ensemble Learning for Binary Classification
Comparison of Decision Tree, Bagging, AdaBoost, and Gradient Boosting using the Carseats dataset in R.

## Overview
Testing whether ensemble methods improve on a single decision tree for predicting high- vs. low-selling stores, and comparing how Bagging and Boosting each address the baseline model's weaknesses differently.

## Methods
- Decision Tree
- Bagging
- AdaBoost
- Gradient Boosting

## Key Results
- AdaBoost achieved the highest AUC (0.934) and tied with Gradient Boosting for the best accuracy (88.3%)
- Both boosting methods outperformed Bagging (85.0%) and the baseline decision tree (71.7%)
- Most important predictors (consistent across all models): Price, ShelveLoc

## Tools
R · rpart · randomForest · gbm · caret

## Files
- Ensemble Learning Analysis.pdf
- Ensemble Learning Analysis.Rmd
