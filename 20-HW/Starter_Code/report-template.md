# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge:

    The purpose of this analysis is to  identify the creditworthiness of borrowers for a peer to peer lending services company, using historical lending data and using Machine Learning to build prediction models.
     We will try to point out which loans are categorized as healthy (low-risk) [0] vs non-healthy (high-risk) [1] based on the loan status provided by the lending company.
     For this excercise, we will be using 7 different models/methods to see which one has better predictions overall.
     The 7 models are:
         -Logistic Regression
         -SVC Model
         -KNN Model
         -Decision Tree
         -Random Forrest
         -Ada Boost
         -Gradient Boosting



## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

1)Logistic Regression:
    There is an overall accuracy of 0.99. 181 False Negatives. Not great on precision and recal (.86,.9). No Signs of overfitting. Therefore this could be better, maybe using a PCA/Scaler could help out



2)SVC Model:
      There is a reduction on false negatives and an increase of false positives compared to the Logistic Regression
      

3)KNN Model:
      No Signs of Overfitting
      Significant number of false positives
      KNN is better than SVC and Logistic Regression
      
4)Decision Tree
    There are signs of overfitting 
    KNN is still the best one out of the 4 models tested so far
    
5)Random Forrest
    Less overfitting compared to the Decision Tree
    KNN is still a better model


6)Ada Boost
    No overfitting
    Looks like a good model
    KNN and Ada Boost are the top models so far

7)Gradient Boosting
      No overfitting
      This is also a good model
      This one along with KNN and Ada Boost are the top three models


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any:

It is important to note that there is an imbalance in the data because very few people default on their loan (Only 3%)
After performing the analysis and looking at all 7 models, it was proven that the best models for this exercise are KNN,AdaBoost and GradientBoost due to the fact that they do not have signs of overfitting 
My recommendation is to use the k-nearest neighbors algorithm (KNN) since it is easier to explain compared to AdaBoost and GradientBoost
