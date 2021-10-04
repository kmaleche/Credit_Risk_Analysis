# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
The purpose of this analysis is to analze machine learning models and their accuracy in predicting loan risk.

## Resources:
 - Credit card credit dataset from LendingClub, a peer-to-peer lending services company 

## Results:

####  **RandomOverSampler** 
     - Balanced Accuracy: 0.72
     - Precision: 0.02 for minority class; 0.99 for majority
     - Recall: .73 avg

 #### **SMOTE**
     - Balanced Accuracy: 0.73
     - Precision: 0.02 for minority class; 0.99 for majority
     - Recall: .73 avg
    
####  **ClusterCentroids**
     - Balanced Accuracy: 0.71
     - Precision: 0.02 for minority class; 1.00 for majority
     - Recall: .66 avg
    
 #### **SMOTEENN** 
     - Balanced Accuracy: 0.64
     - Precision: 0.01 for minority class; 1.00 for majority
     - Recall: .58 avg

 #### **BalancedRandomForestClassifier**
     - Balanced Accuracy: 0.76
     - Precision: 0.02 for minority class; 0.99 for majority
     - Recall: .73 avg
    
 #### **EasyEnsembleClassifier**
     - Balanced Accuracy: 0.93
     - Precision: 0.09 for minority class; 1.00 for majority
     - Recall: .94 avg

## Summary:
Of the models tested here, the EasyEnsembleClassifier performed best by measures of Accuracy, Precision, and Recall. However, it is recommended that additional models be explored, given that the precision for the minority group is 0.09 using the EasyEnsembleClassifier.
