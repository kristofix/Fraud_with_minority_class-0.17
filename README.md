# Credit Card Fraud Detection

The dataset contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

This is my approach to solve popular fraud problem from kaggle.com

Main results:

## LGBM with randomoversampler and hiperparameters found with BayesSearch:

              precision    recall  f1-score   support

           0       1.00      1.00      1.00     56864
           1       0.88      0.87      0.87        98

    accuracy                           1.00     56962


## Neural network:

              precision    recall  f1-score   support

           0       1.00      1.00      1.00     56864
           1       0.61      0.83      0.70        98

    accuracy                           1.00     56962

