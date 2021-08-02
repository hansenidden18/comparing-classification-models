## Project Description

In this project I compare three different models for classification problem.

## Dataset
-  Source            : [Loan or No Loan](https://dphi.tech/practice/challenge/54#data)
-  Training dataset  : [Training Dataset](https://raw.githubusercontent.com/dphi-official/Datasets/master/Loan_Data/loan_train.csv)
-  Testing dataset   : [Testing Dataset](https://raw.githubusercontent.com/dphi-official/Datasets/master/Loan_Data/loan_test.csv)

There are 491 training data and 123 testing data in this dataset. In the training dataset, there are 12 independent columns and 1 dependent column.

## Models
1. The first model that I used is XGBoost Classifier. The f1-score for this model is around 88 %.
2. The second model that I used is Logistic Regression. The f1-score for this model is around 92 %.
3. The last model that i used is Random Forest Classifier. The f1-score for this model is around 90 %.

After evaluating all the models, the models that optimal for this problem is Logistic Regression. The conclusion, this caused by lack of data that given in the dataset for training.

## Notebook

You can access the notebook in [here](Notebook/DPhi_Assignment_3_Loan.ipynb)