# credit-risk-classification

-This purpose of this assignment was to analyze lending activity to build a model to identify creditworthiness of borrowers. The information in the dataset included loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, and loan status. Loan status was handled as a yes or no as to whether or not a loan was 'healthy' or 'high risk'. The loan status column was seperated and used as the y variable and the rest of the columns were used as the X variable. Using train_test_split the data was split into training and testing groups for both y and X. A logistic regression model was created and fit using the training data. Then a prediction was made using the test data. The model had an accuracy score of 0.99. Finally a confusion matrix and a classfication report were created.

               precision    recall   f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384

-At 99%, the accuracy score indicates that this is a well performing model.
-For class 0 (healthy loans), a perfect precision score of 1.00 and recall of 0.99 show that there were very few false positives.
-For class 1 (high risk loans) the precision score was 84% and the recall was 94%. This shows that there were more false positives than in class 0 but at 94% the recall is still pretty high.

-Overall this is a good model to use. It could be more precise in class 2 but overall performs well. The high recall means that 94% of actual instances of an unhealthy loans were correctly predicted, which would be good when assessing loan risk.


