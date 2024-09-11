# Estimating-the-likelihood-of-loan-failure
This project prioritizes responsible lending practices. I aim to create a model that assists investors in identifying borrowers with a strong repayment history, promoting financial stability for both lenders and borrowers.

## Descritipon about the files in repo
This repository contain a Jupyter notebooks and dataset csv file that follow a machine learning pipeline to estimate the likelihood of loan failure. The steps include:

1. Data Collection
2. Data Cleaning (Data was pre-cleaned and contains no missing values)
3. Correlation Analysis
4. Model Selection and Training
5. Model Analysis


## Data descrition
The dataset used is from LendingClub.com, covering the period 2007-2010. It includes 14 features with around 9,000 examples.

- The output labels of the dataset are imbalance.
- There is weak relation between input features and output labels.


## Model descrition
A Random Forest model was selected due to the low linear dependency of numerical features on the target and high correlation between categorical features and the target.

## Model analysis results 

- The model provide the accuracy of about `69%`.
- On analysing the confusion matrix, the model has a well balance between the label classes(i.e. it is not bias).

## Conclusion


The model performs well in identifying positive (loan repayment) cases, but struggles with negative (loan failure) predictions. Further improvement is needed to enhance its predictive power for failed loans.
