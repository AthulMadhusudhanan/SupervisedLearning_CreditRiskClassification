# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
  -> The purpose of the analysis is to evaluate the model based on creditworthiness of borrowers.
  
* Explain what financial information the data was on, and what you needed to predict.
  -> The data was based on loans and I would predict borrowers' creditworthiness & sorting out healthy and unhealthy loans.
  
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
  -> I used '.head()' to arrange the data in ascending order, '.drop()' to drop a column as I have separated one column, '.fit' for building a model & '.predict' for predictions.
  
* Describe the stages of the machine learning process you went through as part of this analysis.
  -> The first stage is splitting the data into training and testing sets. It is a model validation procedure that allows you to simulate how a model would perform on new/unseen data, followed by logistic regression which is a supervised machine learning algorithm that accomplishes binary classification tasks by predicting the probability of an outcome, event, or observation.
  
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  -> Balanced Accuracy Score: 95.20% --> this means that when taking into account the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model, the balanced prediction accuracy was 95.2%
  -> Precision Score: 92% --> This means 92% of predicted positives were correct
  -> Recall Score: 95% --> this means that the model was 95% precise in measuring true positive values our of all positive predictions made
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
  -> Considering the performance, I would say healthy loans performs the best over unhealthy loans and by using logistic regression model which has a 95% accuracy in predicting the outcome of the repayment of the initial loan. That accuracy range could be easily molded into a business risk profile to ensure sufficient capital flow for the lenders to remain in business/make a profit.
  
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
 -> I would say yes.
  
If you do not recommend any of the models, please justify your reasoning.
