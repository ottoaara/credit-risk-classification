# credit-risk-classification
aomodule 20 Challenge 
An overview of the analysis:  
**The purpose of the analysis ** was to preduct Healthy vs Risky loan performance form a data set of Credit Risk Lending data.  
**The results:
**                 precision    recall  f1-score   support

  Healthy_Loans       1.00      0.99      1.00     18765
High_Risk_Loans       0.85      0.91      0.88       619

       accuracy                           0.99     19384
      macro avg       0.92      0.95      0.94     19384
   weighted avg       0.99      0.99      0.99     19384

   *  The Accuracy score 0.9520479254722232 was high.  Yielding .95 One must keep in consideration trade-offs between recall and F1(.88) scores as well.
      Indicating 'High_Risk_Loans' class indicates a trade-off between precision and recall.
   *  precision Score - showed much higher for Healthy Loans vs Risky 1.00/.85 respectively. The author believes this to be given a larger data set for Healthy Loans
      may have aided in the models ability to predict healthy loans more readably.
   *  I would use recommend using the model. The percision got 85% of the high risk predicted correclty as high risk, while Healthy loands it was perfect.
      The recall was strong showing 91% of actual high risks loans identified.  It does a good job on both predictions although it's
      better at predicting Healthy loans which make sense given Support numbers a much larger population of "healthy Loans"
      with 18765 instances vs only 619 High risk loans.

The caviat should be carved our for a larger training dataset with a larger volume of high-risk loans to train on.  
Additonally, one must take into consideration the risk-appetite of each individual company.  Given the models precision right now
15% of High Risk loans could be missed from a prediction standpoint.  These considerations should be taken into account when determining
a models use for a company and its own ability to manage and absorb the potential for defaults in the portfolio. 

  
