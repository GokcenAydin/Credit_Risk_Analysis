# Credit_Risk_Analysis

## Purpose of the Analysis

In this analysis, two machine learning models were applied to evaluate a credit card risk. Different techniques were 
employed to train and evaluate models with unbalanced classes. Using a credit card credit dataset from LendingClub
-a lending services company- data was oversampled and undersampled. Then, a combinatorial approach of over and undersampling
with smoteen algortihm was used to determine which results were better at predicting credit risk. Using these algorithms, the dataset
was resampled, count of the target classes were viewed, a logistic regression classifier was trained, the balanced accuracy score
was calculated, a confusion matrix and a classification report were generated. 

## Results

The related scores of the six machine learning models are as follows:

- Naive Random Oversampling scores:
Balanced accuracy score: 0.661 
Precision: 0.99 
Recall: 0.60
F1: 0.75

![Capture1](https://user-images.githubusercontent.com/104400293/209586517-cead0a7e-2a83-460e-8984-8e85ca83a198.PNG)

- Smote Oversampling scores:
Balanced accuracy score: 0.658
Precision: 0.99 
Recall: 0.69
F1: 0.81

![Capture2](https://user-images.githubusercontent.com/104400293/209586521-433df4e7-c771-4947-b874-693ab2e826b0.PNG)

- Undersampling scores:
Balanced accuracy score: 0.545
Precision: 0.99 
Recall: 0.40
F1: 0.56

![Capture3](https://user-images.githubusercontent.com/104400293/209586528-607abfee-7d98-4305-b5ae-1da47e7b2443.PNG)

- Combination (Over and Under) Sampling scores:
Balanced accuracy score: 0.645
Precision: 0.99 
Recall: 0.57
F1: 0.72

![Capture4](https://user-images.githubusercontent.com/104400293/209586535-bb1696ee-43dd-458a-8a4b-8528246e9792.PNG)

- Balanced Random Forest Classifier scores:
Balanced accuracy score: 0.788
Precision: 0.99 
Recall: 0.87
F1: 0.93

![Capture5](https://user-images.githubusercontent.com/104400293/209586540-6422cdfa-1c66-4715-8d63-581be5917ea9.PNG)

- Easy Emsemble AdaBoost Classifier scores:
Balanced accuracy score: 0.932
Precision: 0.99 
Recall: 0.94
F1: 0.97

![Capture6](https://user-images.githubusercontent.com/104400293/209586545-7f0fccd5-4ed8-4520-b03a-99648a386bea.PNG)

## Summary

When Naive Random Oversampling and Smote Oversampling scores are compared, balanced accuracy score of Naive Random Oversampling method is higher, which tells that
the first logistic regression model did a better job in terms of balanced accuracy. In Smote Oversampling method, recall score is higher, which means a higher percentage 
of the correct positive predictions relative to the actual positives was obtained. Finally when F1 score is compared, Smote Oversampling score is closer to 1, which is a 
better value when compared to Naive Random Oversampling.

When Undersampling algorithm is compared to the methods above, balanced accuracy, recall and F1 scores are all lower than both oversampling methods. Similarly, Combination method
gave the lower scores than the other methods, which still results the Naive Random Oversampling method as the most effective one.

When two ensemble algorithms, Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier are compared, the latter one has a higher value of balanced accuracy score
which is 0.932, a higher recall score of 0.94 and an F1 score of 0.97 which is closer to 1, and these values result in the best performance. 






