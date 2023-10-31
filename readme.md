# credit_risk_classification_challenge
The Module 20 Challenge uses various techniques to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company is used to build a model that can identify the creditworthiness of borrowers.

# Requirements

**Split the Data into Training and Testing Sets***
- Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
- Split the data into training and testing datasets by using train_test_split.

***Create a Logistic Regression Model***
- Fit a logistic regression model by using the training data (X_train and y_train).
- Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model.
- Generate a confusion matrix.
- Generate a classification report.

***Credit Risk Analysis Report***
- Provide an overview that explains the purpose of this analysis.
- Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model.
- Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
