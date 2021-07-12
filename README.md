# Telecom-Data-Analysis
This repository contains dataset for different telecom operators, It contains the features like Network Type, Call Drop Category, In Out Travelling, Latitude, Longitude, State Names, Average Data Upload and Download Speeds, Average Signal Strength and some demographic features such as Population, Literacy Rate, Rainfall and Area of the state.

In Univariate and Bivariate Analysis file, I explore the data firstly by analyse a single feature at a time and then I try to find out the correlations in between various features, For categorical data, chi square test is used and for continuous data, Correlation matrix is used.

In the Regression Models Files, I build four different regression models to predict Average Data upload and download speeds and Average upload and download signal strengths. In feature Engineering part, I handled Outliers, Missing Values, Encoding for categorical data and feature scaling. In feature Selection part, I used Random Forest Regressor to find out the feature importance's. Finally, I tested Several models, compare their performance metrics such as MSE and R-Squared values and select the best model for prediction.

In the Classification Models Files, I build two different Machine Learning models to predict Network Type and Call Drop Category. In feature Engineering part, I handled Outliers, Missing Values, Encoding for categorical data and feature scaling and imbalanced data. In feature Selection part, I used Random Forest Classifier, Correlation Matrix to find out the feature importance's. Finally, I tested several models, used K fold Cross Validation for the assurance of results, compare their performance metrics such as Accuracy, Precision, F-Beta, Recall and select the best models for prediction.

In Clustering Model File, I classified the callers into 3,5,10 clusters using Kmodes ( Handled categorical and continuous data both) and try to find some patterns in the data.
