# Module_12_Challenge

Using various techniques to train and evaluate models with imbalanced classes. Using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Split the data into training and testing sets with y and X. 
Used train_test_split function to split the data into training and testing datasetes

Created a Logistic Regression Model with the Original Data by fitting by using the training data and predictions on the testing data. 
Evaluated the model's performance by calculating the accuracy score, generating a confusion matrix, and printing the classification report. 

Predicted a Logistic Regression Model with Resampled Training Data by using RandomOverSampler. 
Then using the LogisticRegression classifier and the resampled data to fit the model and make predictions. 
To evaluate the model's performance, calculated the accuracy score, generated a confusion matrix, and printed the classification report. 


# Credit Risk Analysis Report

Overview: 
Using a logistic regression model to compare two versions of the dataset by using the RandomOverSampler module from the imbalanced-learn library. For both datasets, counted the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated confusion matrix, and generated a classification report. Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method)

Results:
Machine Learning Model 1:
<img width="442" alt="Screen Shot 2022-02-26 at 12 57 59 AM" src="https://user-images.githubusercontent.com/94431259/155837086-933646c5-3886-4c26-a4da-cfebdbbf80cf.png">

* Machine Learning Model 2:
<img width="603" alt="Screen Shot 2022-02-26 at 12 58 44 AM" src="https://user-images.githubusercontent.com/94431259/155837099-fc77aade-1982-4556-99ce-832ae6c02b51.png">

Summary:
Machine Learning Model 1:
The classification report reported 100% precision for healthy loan and 86% precision for high risk loan. Whereas the recall is 91% recall value for high risk loan and 100% loan so I think the results came out good.
Machine Learning Model 2:
The precision for healthy loan was 100% again and 85% for non risky loan. The recall values for both loans are 99%. The original data was 91%. This tells us that the oversampled data was much better.




