# Employee-Attrition

INTRODUCTION:


The link to the dataset is: 
https://www.ibm.com/communities/analytics/watson-analytics-blog/hr-employee-attrition/. 
It is a fictional HR data created by IBM data scientists which includes data for all the current and past employees with all the personal, compensation, and performance details. The 35 variables in the dataset are pretty self-explanatory in explaining the reasons behind an employee leaving the company. Attrition is the dependent variable since it is bivariate. We strive to figure out the factors which cause employee attrition by employing a logistic regression model. The dataset will be divided into test and train data and will be trained and tested accordingly. Independent variables will be chosen via trial and error method based on their significance & ROC curve will be used to check the efficiency of the model. The results from our model will be used to prevent top performers from leaving the company.

PROCEDURES:


(1) Data was collected and cleaned. EDA was performed.
(2) Data was divided into test and train and test: 80% train & 20% test set.
(3) Prediction was made on attrition. The test model was giving output probabilities which ranged from 0 to 1. It didn't make sense as attrition had to be either 0 or 1. The probability limit was set to a particular value in the test model based on trial and error so that maximum model efficiency was possible.
(4) Hit rate was developed, confusion matrix was analyzed, and ROC Curve was produced.
(5) ROC curve was used to check the efficiency of the model.
(6)Two models were created following the above procedures, and the best model was chosen based on model efficiency and cost effectiveness.
