# Customer Purchase Prediction

## Dataset
https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing

## Overview
I implemented a Logistic Regression model to 
predict purchases based on factors like ad type, total ads seen, day the person
saw the most ads, and the hour the person saw the most ads

## Libraries
pandas
numpy
matplotlib
scikit-learn
    - sklearn.model_selection (train_test_split)
    - sklearn.linear_model (LogisticRegression)
    - sklearn.preprocessing (FunctionTransformer, StandardScaler)
    - sklearn.pipeline (Pipeline)
    - sklearn.metrics (roc_auc_score, classification_report, RocCurveDisplay)

## Key Results
- AUC: 85.5%
- Total ads seen was the strongest predictor of purchase
