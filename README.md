# Credit_Risk_Analysis

### Overview of the analysis:

For this project, we are looking at how all the factors in the Loan_Stats file will help predict if someone has a high or low risk status. For this analysis we used imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. 

The techniques that were used to train and evalatue the models were:

- Oversample the data using the RandomOverSampler and SMOTE algorithms
- Undersample the data using the ClusterCentroids algorithm
- Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm
- Compare two machine learning models that reduce bias BalancedRandomForestClassifier & EasyEnsembleClassifier


### Results: 

## Naive Random Oversampling
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/Naive%20Random%20Oversampling.png)
- 

## SMOTE
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/SMOTE%20Oversampling.png)

-

## Cluster Centroids
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/ClusterCentroids.png)

- 

## Balanced Random Forest
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/Balanced%20Random%20Forest%20Classifier.png)

-

## Easy Ensemble
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/Easy%20Ensemble%20AdaBoost%20Classifier.png)

## SMOTEENN
![](https://github.com/mquimi/Credit_Risk_Analysis/blob/main/images/SMOTEENN.png)

-


Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.