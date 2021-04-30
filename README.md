# Credit_Risk_Analysis
## Overview
In this project, we are building a credit risk analysis from a dataset that has an unbalanced classification problem. We are looking to identify possibly risky loans out of the good ones. We will be using scikit-learn libraries from Python to create generate machine learning. Through scikit-learn, we will be utilizing ensemble learning and unbalanced learning. We will use a dataset from LendingClub as the basis of our data analysis, and to perform our model prediction evaluations from.

## Purpose
The purpose of our project is to use machine learning to create, train and evaluate a prediction of credit risk. To train our model, we will create four different types of data sampling due to the unbalanced data set we have. We will use Random Oversampling, SMOTE Oversampling, Random Undersampling, and Combination (Over and Under) Sampling/SMOTEENN Sampling.
* We need to use various forms of sampling due to the lower amounts of the High Risk numbers in comparison to the Low Risk numbers.
  * We will be using two forms of Oversampling algorithms: SMOTE (Synthetic Minority Oversampling Technique) and RandomOverSampling (Naive Random Oversampling)
  * For Undersampling, we will be using the ClusterCentroids algoithm
  * For the combination sampling, we will be using the SMOTEENN algorithm
* With Machine Learning, we will be using two different models: BalancedRandomForestClassifier and EasyEnsembleClassifier
