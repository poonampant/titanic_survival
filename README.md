# Titanic-survival

Predicting the survival of passenger using logistic regression in python.

Dataset has been taken from kaggle
Files included :

* Titanic_train.csv - Training dataset
* titanic_test.csv - Testing dataset

Libraries used :

* Pandas
* numpy
* matplotlib
* seaborn
* sklearn

Problem type : Classification

Machine learning algorithm used : Logistic Regression,Decision TRee ,Random Forest.

Algorithm :

* importing the required libraries
* Read and input the training and test data from the CSV files
* Exploring whwther the data contain null values  
* Exploratory analysis to check which all features are highly correlated with outout value
* Cleaning the training and test data
* processing the categorical values and other unwanted features
* Separating and assigning the features and output parameters for the training and test dataset
* Fitting all the  model using the training data
* calculate the accuracy for each model using evaluation metrics
* compare the accuracy of each model to check which model predict the output more accurately. 
* Use the trained  model which have higher accuracy  to predict the survival of passengers in the test data.
