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

The oversampling model had a 66% balanced accuracy score. The recall was 60%. The precision score was 99%. While the precision score was very good, the model was not very balanced and while it did catch the majority of the positive cases, it missed 40%. 

---
![Oversampling](https://github.com/lllohr/Credit_Risk_Analysis/blob/9052b6e758becd5bc3fd82a39d607bd24cf98758/Resources/images/oversampling.png)
---

- SMOTE OVERSAMPLING

SMOTE oversampling performed similarly to the first oversampling model. The precision score was 99%, the recall score was 68%, and the balanced accuracy score was 66%. 

---
![SMOTE](https://github.com/lllohr/Credit_Risk_Analysis/blob/b9131e5799ab827074ce1de909f5df0d5437abcf/Resources/images/smote_oversamplling.png)
---

- UNDERSAMPLING

Undersampling performed worse than the oversampling models. The precision score was 99%, the recall score 40%, and the balanced accuracy score was 54%. 

---
![Undersampling](https://github.com/lllohr/Credit_Risk_Analysis/blob/9052b6e758becd5bc3fd82a39d607bd24cf98758/Resources/images/undersampling.png)
---

- COMBINATION OVER/UNDER SAMPLING (SMOTEEN)

The combination of over and under sampling using the SMOTEEN model had a precision score of 99%, a recall score of 60%, and a balanced accuracy score of 67%. The combination did comparable to the other models. There was an avantage to the undersampling. 
Precision Score : 0.99      

Recall Score : 0.60

Balanced Accuracy Score :  0.6723570538765757

---
![SMOTEEN](https://github.com/lllohr/Credit_Risk_Analysis/blob/9ba40d390ecafde3ba85254fee5668bd6d21ba80/Resources/images/SMOTEEN_combo_sampling.png)
---

- BALANCED FOREST CLASSIFIER

The ensemble models did significantly better than the previous models. The precision score was 99%, the recall score was 87%, meaning is caught more of the positive cases. This meant that if was more accurate at predicting the high risk better than the previous models. 

---
![Balanced Forest Classifier](https://github.com/lllohr/Credit_Risk_Analysis/blob/9052b6e758becd5bc3fd82a39d607bd24cf98758/Resources/images/balanced_forest_classifier.png)
---

- EASY ENSEMBLE ADABOOST CLASSIFIER

The last model performed nearly perfectly! With a precision score of 99%, a recall score of 94%, and a balanced accuracy score ot 93%, I think we can declare it the winner in this analysis!

---
![Easy Ensemble AdaBoost Classifier](https://github.com/lllohr/Credit_Risk_Analysis/blob/9ba40d390ecafde3ba85254fee5668bd6d21ba80/Resources/images/easy_ensemble_adaboost_classifier.png)
---

## Summary:

Based on the results of the performance of the six models on the data set, I would choose the Easy Ensemble AdaBoost Classifier. The reason I would use this model is that the performance was better than with the other models. I would use either of the ensemble learners for the data, as both had a higher performance on the balanced accuracy score, the precision, and the recall. 


