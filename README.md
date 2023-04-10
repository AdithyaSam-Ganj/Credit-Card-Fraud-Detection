# Credit Card Fraud Detection 

This is a project where I have tried to implement industry standard practices for analysing highly unbalanced datasets. I have used the a dataset of European cardholders. The data was collected in Septemberr 2013 . Link to the dataset - https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the original features are not provided. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


## Techniques used for modelling 

1. Random Forest Classifers without sampling 

2. Undersampling (Nearmiss) of data after performing 5 fold cross validation. 


Models -  
a. Logistic regressing
b. Random Forest 
c. Support Vector Classifier
d. Decision Tree Classifier
e. K nearest Neighbours



Metrics - F1score , ROCAUC curve 

3. Oversampling(SMOTE - Systemic Minority OverSampling Technique) of data after performing 5 fold cross validation.


Models - 
a. Logistic regressing
b. Random Forest 
c. Support Vector Classifier
d. Decision Tree Classifier
e. K nearest Neighbours



Metrics - ROC curve, Accuracy, CVScore, Recall Score 

## Learning outcomes 

I learnt how to deal with extremly skewed datasets by using both undersampling and oversampling techniques. Learnt what kind of models to use for a given dataset. LEarnt to develope python pipelines 


## Installation 

This is a Jupyter Notebook. Package requirments are included in requirments.txt. Use the following command for installing requirments - pip3 install -r requirments.txt. 
