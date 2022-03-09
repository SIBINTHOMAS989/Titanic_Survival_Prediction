# Titanic_Survival_Prediction
Objective of this project is to create a ML model to predict whether the given passenger will survive or not during the Titanic shipwreck. As a part of Machine Learning competition participants will be provided a training data set with features (Passenger details) &amp; binary labelled target (Survived or Not).  Create a model using the training data set to and predict target value of the test data (without the labels).

Titanic Survival (Kaggle Competition) -Predictive Modelling

•	Libraries – SKlearn, Pandas, Seaborn and NumPy.
•	Dataset - Titanic Data Set from Kaggle.
•	Model – Binary Classification

          Objective of this project is to create a ML model to predict whether the given passenger will survive or not during the Titanic shipwreck. As a part of Machine Learning competition participants will be provided a training data set with features (Passenger details) & binary labelled target (Survived or Not). 
Create a model using the training data set to and predict target value of the test data (without the labels).

1.Exploratory Data Analysis (EDA) has been done with the help of Pandas and Seaborn to understand the behaviour of features and its relation to the labelled targets. 
2.Pre-processing: Applied Information gained through EDA and the input documents used to fill the missing values (NaN) as well as new feature extraction (e.g.: bin the continuous values and create new featured class.
As a part of baseline pre-processing label encoded all the categorical Text features (One Hot encoding must be done to check if that gives better accuracy than label encoding).
Q-Q plot used to check the Gaussian distribution of continuous features and applied feature 
transformation to improve the Gaussian behaviour of the data (for Logistic regression). 
Because of the high percentage of missing values on certain features, I got an innovative idea to create a sub model to predict the missing values (considering the high percentage missing value feature as target) and remaining as feature including the actual feature.
3.Handling Outliers: For the baseline model identified the outliers using Box plot and applied Winsorizing to handle it.
4.Base Line Model: Create a baseline ML model using Traditional ML algorithms KNN classifier, Random Forest, Classifier, SVC and Logistic Regression with default hyper parameter.
Among all Random Forest give the best accuracy 83%. 
5.Hyper Parameter Optimization: To improve accuracy hyperparameter optimization done using Grid search, eventually improved the score to 90%.
6.Ensemble model: Used soft voting method to create a custom ensemble model. Which improved the prediction model compared to best single algorithm model.

Further improvements in accuracy can be done by more detailed EDA and feature pre-processing
or using an ANN model.

Value Addition 
This project helped me to understand more about the techniques in classification model improvements like feature selection, Evaluation & model performance, hyperparameter optimization ,EDA and NaN handling methods.
