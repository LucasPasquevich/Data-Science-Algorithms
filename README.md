# Data-Science-Algorithms
Hi! It´s my porfolio/repository of Data Science proyects. 
Here you can find this folds:

- KNN_LR_NB_Cluster: Is a proyect of Stars, Galaxys and Quasars classification using K-NN, Linear Regression and Naive Bayes algorithms. 
Additionally I applied and explained clustering algorithms (K-means, hierarchical and DBSCAN) for practice, 
as you can see in the code it did not give anything reasonable either.

- Linear Regresion (S-PLUS): Is a regression proyect to predict galaxys redshifts. Here I use a classical Linear Regression and a Random Forest Regression
algorithm. 

- Santander Customer Transaction Prediction: In this project I applied boosting techniques (Ensemble, Random Forest, Ada boosting, Gradient boosting, XBG and Cat boosting), balancing with Imbalanced Learn, and LIME for feature analysis. 
I am going to work with a dataset provided in Kaggle by "Banco Santander", where they describe the dataset as:
"You are provided with an anonymized dataset containing numeric feature variables, the binary target column, and a string ID_code column.
The task is to predict the value of target column in the test set."
Was uploaded as a competition on the site 4 years ago: "In this challenge, we invite Kagglers to help us identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted. The data provided for this competition has the same structure as the real data we have available to solve this problem".

- Times Series of Energy Consumption: PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia. The hourly power consumption data comes from PJM's website and are in megawatts (MW). I use PJM East Region: 2001-2018 (PJME). The regions have changed over the years so data may only appear for certain dates per region.
In this notebook I used and compared basic algorithms such as mean (as null hypothesis), OLS, residual corrections with ARIMA and a last model with XGBoost. There is also a small implementation of pipelines which is still in progress.
