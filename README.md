# Credit_Risk_Analysis
## Overview
### Sampling
There are various techniques to sample training and testing data in supervised machine learning. Typically these oversampling, undersampling or combination techniques are employed to resolve class imbalance issues in which the existing classes in the dataset aren't equally represented. This could look like a dataset in which there are significantly more cases of one outcome than the other.
#### Oversampling
Oversampling techniques reuse data points from the minority class until it has equal points to the majority class in a training dataset. The issue with oversampling is that the machine can become biased toward the majority class. Two methods of oversampling are random oversampling and synthetic minority oversampling technique (SMOTE).
#### Undersampling
Undersampling techniques drop points from the majority class until it has equal points to the minority class in a training dataset.
### Purpose
The purpose of this project is to compare resampling methods and ensemble learning builds. Oversampling methods RandomOverSampler and SMOTE, undersampling method ClusterCentroids, and a combination sampling method SMOTEENN are compared. Ensemble learners BalancedRandomForestClassifier and EasyEnsembleClassifier are compared.
## Results
## Summary
