# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

The loan prediction risk analysis was an exploration of supervised machine learning. The project utilized credit risk analysis data and required various methods of oversampling, undersampling, machine learning models that reduce bias, and other algorithms to analyze data. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we were able to run a variety of models to predict and analyze the loan status data to determine which model most effectively accesses credit risk. We utilized six different supervised learning models: oversampling, SMOTE oversampling, undersampling, combination over/under sampling (SMOTEEN), and ensemble learners: Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier. 

We are looking at three specific scores:
- Precision – What percent of your predictions were correct?
- Recall – What percent of the positive cases did you catch?
- Balanced Accuracy Score - How balanced was the model? 

## Results:

The results for the analysis of the six models are as follows in the areas of balanced accuracy score and the precision and recall scores for each:

- OVERSAMPLING
Precision Score: 0.99      
Recall Score: 0.60
Balanced Accuracy Score :  0.660760553955302

---
![Oversampling](https://github.com/lllohr/Credit_Risk_Analysis/blob/9ba40d390ecafde3ba85254fee5668bd6d21ba80/Resources/images/oversampling.png)
---

- SMOTE OVERSAMPLING
Precision Score: 0.99      
Recall Score : 0.68 
Balanced Accuracy Score :  0.6581261172188313

---
![SMOTE](https://github.com/lllohr/Credit_Risk_Analysis/blob/b9131e5799ab827074ce1de909f5df0d5437abcf/Resources/images/smote_oversamplling.png)
---

- UNDERSAMPLING
Precision Score : 0.99      
Recall Score : 0.40
Balanced Accuracy Score :  0.5442369453268994

---
![Undersampling](https://github.com/lllohr/Credit_Risk_Analysis/blob/9ba40d390ecafde3ba85254fee5668bd6d21ba80/Resources/images/undersampling.png)
---

- COMBINATION OVER/UNDER SAMPLING (SMOTEEN)
Precision Score : 0.99      
Recall Score : 0.60
Balanced Accuracy Score :  0.6723570538765757

---
![SMOTEEN](https://github.com/lllohr/Credit_Risk_Analysis/blob/9ba40d390ecafde3ba85254fee5668bd6d21ba80/Resources/images/SMOTEEN_combo_sampling.png)
---

- BALANCED FOREST CLASSIFIER
Precision Score : 0.99      
Recall Score : 0.87
Balanced Accuracy Score :  0.7885466545953005

---
![Balanced Forest Classifier](https://github.com/lllohr/Credit_Risk_Analysis/blob/9ba40d390ecafde3ba85254fee5668bd6d21ba80/Resources/images/balanced_forest_classifier.png)
---

- EASY ENSEMBLE ADABOOST CLASSIFIER
Precision Score : 0.99      
Recall Score : 0.94
Balanced Accuracy Score :  0.9316600714093861

---
![Easy Ensemble AdaBoost Classifier](https://github.com/lllohr/Credit_Risk_Analysis/blob/9ba40d390ecafde3ba85254fee5668bd6d21ba80/Resources/images/easy_ensemble_adaboost_classifier.png)
---

## Summary:

Based on the results of the performance of the six models on the data set, I would choose the Easy Ensemble AdaBoost Classifier. The reason I would use this model is that the performance was better than with the other models. I would use either of the ensemble learners for the data, as both had a higher performance on the balanced accuracy score. Looking at the predicitions and the actual accuracy on these models was much better than the 

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
