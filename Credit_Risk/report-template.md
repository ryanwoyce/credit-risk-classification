# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    -The purpose was to see if we could predictif a loan is healthy or high risk

* Explain what financial information the data was on, and what you needed to predict.
    -Finacial Information: Debt, Derogatory Marks, Number of Accounts, Borrower Income, Debt to Income, Loan Size, and Interst Rate. They wewre used to predit the state of the laon (Healthy or High Risk)

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    -We trained the data using outcome of the data that was already given. This allowed us to properly test new untrained data to see how accurnate the model really was

* Describe the stages of the machine learning process you went through as part of this analysis.
  -Started with training a Logistic Regression Model, Then tested new data to see how accurate the model was

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
    -I used a Random Over Sampler to sample the data again to hope to improve the model.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:

  * Balanced Accuracy Score: 0.944
  * Precision:
      * Healthy Loans: 1.00
      * High Risk: 0.87
      * Macro Average: 0.94
      * Weighted Average: 0.99
  * Recall 
      * Healthy Loans: 1.00
      * High Risk: 0.89
      * Macro Average: 0.94
      * Weighted Average: 0.99




* Machine Learning Model 2:

* Balanced Accuracy Score: 0.995
  * Precision:
      * Healthy Loans: 1.00
      * High Risk: 0.87
      * Macro Average: 0.94
      * Weighted Average: 0.99
  * Recall 
      * Healthy Loans: 1.00
      * High Risk: 1.00
      * Macro Average: 1.00
      * Weighted Average: 1.00
  
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
    -Both Models worked great. The logistic regression model works better once you put more training data in it. (99% over a 94%)
    -If i could make a recomendation, I would say to continue to improve the model as much as possible. Do more sampling and put more data into the model
