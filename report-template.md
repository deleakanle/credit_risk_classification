# Module 12 Report Template

## Overview of the Analysis
The Challenge focuses on buulding a model based on loan risks. I will be using the provided hitsorical datasets by peer-to-peer lending companies who typically connects borrowers to lenders to determine the creditworthiness of potential borrowers.

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of the analysis is to detrmine whether a potential borrowet is likley to default on a loan or is creditworthy for a loan. 
* Explain what financial information the data was on, and what you needed to predict.
The financial information is basically looking at the financial profiles of loan applicants. These includes; the applicants financial history, size of the loan, interest rates, income of the borrower and debt status. The aim is to predict credit worthiness of the applicants. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The variables is the loan_status' healthy loans and high-risk loans.

* Describe the stages of the machine learning process you went through as part of this analysis.
1. Data preprocessing, checked for missimg values, split the dataset and performed the train-test split.
2. Exploratory Data Analysis (EDA). 
3. Model Training, Model evaluation and optimizing.
4. Interpretation of the model.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
Scikt-learn (sklearn) was used for the data processing.
The LogisticRegression was used as a baseline model. 
Confusion matrix was used to evaluate the performance by
comparing actual vs. predicted values. 
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    
    Machine Learning Model 1:
Model 1 Accuracy: Accuracy =  99%.
Model 1 Precision: For healthy loans, the model had a precision of 1.00, which indicates that identified true positive healthy loans with no false positives. For high-risk loans, the precision was .84, meaning that it was effective at identify high-risk loans, however, there were false positives. This is probably okay from an institution standpoint as a manual review of the loan information could indicate if it is a false positive, and this would be unlikely to happen often.
Model 1 Recall: For healthy loans, the model had a recall of .99, which means that it almost perfectly identified healthy loans without any instances of false negatives. For high-risk loans, the model had a recall of .94, indicating a high rating of identifing problematic loans with few false positives. 
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
In summary, the model demonstrates exceptional capability in accurately classifying loan statuses, making it a valuable tool for financial risk assessment. I will defimtely recommend it for use of predicting credtworthiness of loan applicants, based of its high performance. 

* Which one seems to perform best? How do you know it performs best?
All performed well. 

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
