# supervised_machine_learning_challenge

Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

Create machine learning models to classify the risk level of given loans. Specifically, compare the Logistic Regression model and Random Forest Classifier.

Split the Data into Training and Testing Sets: 

- Created the features DataFrame, X, by removing the loan_status column. Created y, the labels set, by using the loan_status column. Split the data into training and testing datasets by using the train_test_split function.

Create, Fit and Compare Models: 

- Created a Logistic Regression model and Random Forest classifier model, fit it to the training data that was created in the previous step. Then,       determined the model's score by using the score function and the testing data from the previous step.


- Both models performed well, when compared logistic regression model performed little better than Random forest model.

- Random forest is time consuming.

- Training score and testing score is very close in both models, the difference is much lesser in logistic regression which indicates overfitting is little less in logistic regression compared to random forest.
