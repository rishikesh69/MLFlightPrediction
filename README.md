## Capstone Project – Kiwi.com Flight Delay Prediction:

### Problem Statement:
Kiwi.com is a fastest growing online travel booking company in Czech Republic who offers the reimbursement policy to their customers, in case they missed the connection flight because of the first flight got delayed. 
Our goal is to use the historical data of flight departures and predict how much time, a flight is likely to be delayed.

### Key Challenge:
Lack of features such as weather information, airport geocodes and handling missing airport codes.


### Resolution:

  - Collecting the additional features by using external APIs such as GoogleMaps API and Darksky weather API.
  - Analysing the input data and understanding the problem better by brainstorming possible factors that can impact the flight delay time
  - Performing Data exploration techniques which involves identifying numerical and categorical feature, making inferences about data by plotting distribution using visualization tools such as matplotlib and find the irregularities such as missing values and detecting outliers.
  - Imputing the missing observations and treating outliers or extreme values using log transformation techniques.
  - Apply Feature engineering techniques such as creating meaningful additional features using existing features. Since scikit-learn accepts only numerical variables, convert all categories of nominal variables into numeric types using LabelEncoding or one-hot encoding techniques.
  - Building predictive model by experimenting with various regression algorithms such as Linear Regression, Random Forest Regressor and XGBoostRegressor.
  - Performing model evaluation on test data using k-cross fold validation and comparing the root mean squared error value.
  - Optimize the model by finding the important features and hyperparameter turning using GridSearchCV technique.
