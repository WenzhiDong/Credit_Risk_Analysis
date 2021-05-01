# Credit_Risk_Analysis


## Overview of the analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I will need to employ different techniques to train and evaluate models with unbalanced classes. I am asked to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I will split the data into training and validation sets and:
  - oversample the data using RandomOverSampler and SMOTE algorithms
  - undersample the data using the ClusterCentroids algorithm
  - combinatorial approach of over- and undersampling using the SMOTEENN algorithm

Next, I  will compare two new machine learning models that reduce bias:
  - BalancedRandomForestClassifier
  - EasyEnsembleClassifier
  
I will evaluate the performance of these models.

## Results

### RandomOverSampler
The accuracy is 64.42%

confusion matrix is:

[  54,    33]
[5689, 11429]

![a](Resources/RandomOverSampler.png)

### SMOTE
![b](Resources/SMOTE.png)

### ClusterCentroids
![c](Resources/Undersampling.png)

### SMOTEENN
![d](Resources/Combination.png)

### BalancedRandomForestClassifier
![e](Resources/Forest.png)
### EasyEnsembleClassifier
![f](Resources/AdaBoost.png)
## Summary
