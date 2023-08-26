Employee Attrition Prediction Model Comparison

Overview
This repository contains a comparison of three different models for predicting employee attrition based on various features. The models used are Logistic Regression, Naive Bayes, and k-Nearest Neighbors (KNN). The dataset includes features such as Age, BusinessTravel, Education, MaritalStatus, OverTime, EmployeeNumber, DailyRate, Gender, and accepted for the interview.

Models and Evaluation

Logistic Regression
Accuracy: 0.91
Classification Report:

              precision    recall  f1-score   support
       False       0.92      0.98      0.95       402
        True       0.63      0.26      0.37        46
   accuracy                           0.91       448
   macro avg       0.78      0.62      0.66       448
weighted avg       0.89      0.91      0.89       448

Confusion Matrix:
395   7
 34  12


Naive Bayes
Accuracy: 0.88
Classification Report:

              precision    recall  f1-score   support
       False       0.99      0.88      0.93       402
        True       0.47      0.96      0.63        46
   accuracy                           0.88       448
   macro avg       0.73      0.92      0.78       448
weighted avg       0.94      0.88      0.90       448

Confusion Matrix:
352  50
 2   44

k-Nearest Neighbors (KNN)
Accuracy: 0.97
Classification Report:

              precision    recall  f1-score   support
       False       0.97      1.00      0.98       402
        True       0.97      0.72      0.82        46
   accuracy                           0.97       448
   macro avg       0.97      0.86      0.90       448
weighted avg       0.97      0.97      0.97       448

Confusion Matrix:
401   1
 13   33

Model Selection
The models were evaluated using accuracy, precision, recall, and F1-score metrics. The choice of models depends on the trade-off between precision and recall, as well as the overall accuracy. In this scenario:

Logistic Regression achieved good accuracy but had relatively lower recall for the positive class (True).

Naive Bayes had a balanced recall for both classes but slightly lower accuracy.

k-Nearest Neighbors achieved high accuracy and a good balance between precision and recall.

Considering the specific goals and requirements of the application, the appropriate model can be chosen.

Conclusion
The comparison of three models for employee attrition prediction showcased their strengths and weaknesses. The selection of the final model should be based on the application's priorities regarding precision, recall, and overall accuracy. The insights gained from this comparison can aid in making an informed decision.
