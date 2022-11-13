# Credit_Risk_Analysis
## Overview
The purpose of this analysis was to predict the likelihood of a given person being denied for a loan based on credit risk. Credit risk is an unbalanced classification problem as there are many more good loans that risky loans.
## Results
the balanced accuracy test is 64%, the precision for the high_risk has low positivity at 1% and the recall is 61%

the SMOTE oversampling had and accuracy score of 62%, the precision for the high risk loans also has a low positvity at 1% and recall is 66% overall

the Undersampling had an accuracy score of 51% overall, the precision is at 99% and the recall is 44%

Combination(over and undersampling) results: balanced accuracy score is 54.7% the precision is 99% and the recall is 58% overall

Easy Ensemble AdaBoost Classifier resultshad the higest accuracy score with 92%, percison of 99% and recall of 94%.

##conclusion
considering all the models used, it is recomended to use easy ensemble classifier as it was the most accurate and to avoid the cluster centroids model as it was the least accurate. T
