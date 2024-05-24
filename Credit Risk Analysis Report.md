
## Credit Risk Analysis

* The purpose of this analysis is to identify the creditworthiness of borrowers, based on loan risk. The data used is the historical lending activity from a peer-to-peer lending services company. I needed to predict the credit worthiness of the borrower. I am predicting healthy loan vs high-risk loan.
 

* Stages of machine learning process for this analysis:
    1. Split the data into training and test sets
    2. Create the machine learning model with the original data
    3. Write the Credit Risk Analysis Report
    

* Below are the steps performed as part of this analysis:
    1. Import the required packages
    2. Read the data from csv file
    3. Create the labels set (`y`)  from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.
    4. Split the data into training and testing datasets by using `train_test_split`.
    5. Fit a logistic regression model by using the training data (`X_train` and `y_train`).
    6. Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.
    7. Evaluate the model’s performance using accuracy score, confusion matrix and classification report.


* Results of the Analysis: 
    * Below are the model's performance measures:
    
          *  Accuracy Score: 99.2% --> this means that when taking into account the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model, the prediction accuracy was 99.2%
          *  Precision Score: 92% --> This means 92% of predicted positives were correct.
          *  Recall Score: 95% --> this means that the model was 95% precise in measuring true positive values out of all positive predictions made.
        

* Summary: 

 I would recommend using this model to predict the creditworthiness of borrowers, because it has over 99% accuracy in predicting the outcome of the repayment of the loan. This accuracy rate helps company to make dicisions on running capital and lending to customers with higher confidence. 


