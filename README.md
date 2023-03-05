# SupervisedLearningChallenge

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. Here we are using data to create machine learning models to classify the risk level of given loans. Where we will be comparing the Logistic Regression model and Random Forest Classifier.

### Split the Data into Training and Testing Sets
Create the features DataFrame, X, by removing the loan_status column. Create y, the labels set, by using the loan_status column. Split the data into training and testing datasets by using the train_test_split function.

### Create, Fit and Compare Models
Create a Logistic Regression model, fit it to the training data that you created in the previous step. Then, determine the model's score by using the score function and the testing data from the previous step. Do the same for a Random Forest Classifier. You may choose any starting hyperparameters you like.

Review the scores of each model. Which model performed better? How does that compare to your prediction? Write down your results and thoughts in the designated markdown cell.
