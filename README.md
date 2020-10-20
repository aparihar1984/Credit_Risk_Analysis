# Credit_Risk_Analysis
## Overview of the Analysis

The purpose of this exercise was to try and predict credit risk by employing different techniques to build and evaluate models using resampling, specifically the imblanced-learn and scikit-learn libraries.  We first oversampled data with the RandomOverSampler and SMOTE algorithms, then undersampled data using the ClusterCentroids algorithm, followed by a combined approach using the SMOTEENN algorithm.  Finally we compared two new algorithms, BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk.  The performances of all these algorithms were examined to determine if they any of them should be used to predict credit risk.

## Results

Listed below are the precision and the recall/sensitivity scores of all 6 machine learning models:

Native Random Oversampling: Precision Average = 0.99, Recall/Sensitivity Average = 0.57
[GitHub Pictures](https://github.com/aparihar1984/Credit_Risk_Analysis/blob/main/Pictures/Naive_Random_Oversampling.png)

SMOTE Oversampling: Precision Average = 0.99, Recall/Sensitivity Average = 0.68
[GitHub Pictures](https://github.com/aparihar1984/Credit_Risk_Analysis/blob/main/Pictures/SMOTE_Oversampling.png)

ClusterCentroids Undersampling: Precision Average = 0.99, Recall/Sensitivity Average = 0.41
[GitHub Pictures](https://github.com/aparihar1984/Credit_Risk_Analysis/blob/main/Pictures/ClusterCentroids_Undersampling.png)

SMOTEENN Combination: Precision Average = 0.99, Recall/Sensitivity Average = 0.58
[GitHub Pictures](https://github.com/aparihar1984/Credit_Risk_Analysis/blob/main/Pictures/SMOTEENN_Combination.png)

BalancedRandomForestClassifier: Precision Average = 0.99, Recall/Sensitivity Average = 0.87
[GitHub Pictures](https://github.com/aparihar1984/Credit_Risk_Analysis/blob/main/Pictures/BalancedRandomForestClassifier_Algorithm.png)

EasyEnsembleClassifier: Precision Average = 0.99, Recall/Sensitivity Average = 0.94
[GitHub Pictures](https://github.com/aparihar1984/Credit_Risk_Analysis/blob/main/Pictures/EasyEnsembleClassifier_Algorithm.png)

## Summary


