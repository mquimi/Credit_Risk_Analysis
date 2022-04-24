# Credit_Risk_Analysis

### Overview of the analysis:

For this project, we are looking at how all the factors in the Loan_Stats file will help predict if someone has a high or low risk status. For this analysis we used imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. 

The techniques that were used to train and evalatue the models were:

- Oversample the data using the RandomOverSampler and SMOTE algorithms
- Undersample the data using the ClusterCentroids algorithm
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm
- Compare two machine learning models that reduce bias BalancedRandomForestClassifier & EasyEnsembleClassifier


### Results: 

# Naive Random Oversampling
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/Naive%20Random%20Oversampling.png)

- Balanced Accuracy is: 65%
- High Risk is 1% with a 62% sensitivity making F1 2%.
-  Since there is a high number of low risk population the percision is close to 100% and has a sensitivity of 68%

## SMOTE
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/SMOTE%20Oversampling.png)

- Balanced Accuracy is: 64%
- High Risk is 1% with a 63% sensitivity making F1 2%
- Since there is a high number of low rish population the percision is close to 100% and has a sensitivity of 66%

## Cluster Centroids
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/ClusterCentroids.png)

- Balanced Accuracy is: 53%
- High Risk is 1% with a sensitivity of 63% making F1 1%
- Since there is a high number of false positivies the low risk sensitivity is 40%

## Balanced Random Forest
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/Balanced%20Random%20Forest%20Classifier.png)

- Balanced Accuracy is: 79%
- High Risk is
- 

## Easy Ensemble
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/Easy%20Ensemble%20AdaBoost%20Classifier.png)

- Balanced Accuracy is: 93%
- High Risk is
- 

## SMOTEENN
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/SMOTEENN.png)

- Balanced Accuracy is: 62%
- High Risk is
- 


### Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.