# Fraud_with_minority_class_0.17%

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

