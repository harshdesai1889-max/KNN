# KNN

## Introduction:
This project is made to predict the result of students from their study hours and sleep hours using KNN.

## Data Descprition:
In this project x describes (study hours,sleep hours) and y gives the result(0=fail,1=pass)

## Models Used:
1) KNN: K-Nearest Neighbors is a hyperparameter model. The working principle is that it collects data from its neighbor's prediction and for classifier(binary): class with most votes and for regressor: average of the result.
2) Numpy: Used to convert data into array for computation.
3) Matplotlib: To plot data.
4) train_test_split: Model by scikit learn is to split data into different parts for training, evaluation and test model. (Syntax: test_size[0,1) to tell  how much to split.
5) Accuracy Score: To check how much accurate the data prediction is.
6) Standard Scaler: Used to convert data in a range of 0-1 to compute.
## Hyperparamater models.
7) Cross Validation: In this system data is folded and packed and tested through different parameters(here neighbors) and help us know which parameter is the best.
8) GridSearchCV: This is a tool for the cross validation which checks data with all the parameters mentioned and gives the best parameter automatically.
9) Pipeline: This  is used to create pipeline between two or more models.

## Problems Solved:
1) Preventing Data leakage using pipeline.
2) Saves time using GridSearchCV to find best parameter fastly.
3) Less memory allocation using StandardScaler.

## Moto of the project:
To see how works:
1) KNN
2) hyperparameter predictions.

## Future projects:
To create a model using CatBoost for category based dataset and stacking models.

## Author
Harsh
