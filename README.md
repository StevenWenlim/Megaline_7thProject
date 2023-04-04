# Megaline_7thProject
This project is my project in sprint 2, which is Introduction to Machine Learning.

In this srpint i learn the basics of machine learning and the Scikit Learn library.

# Project Overview
As a Data Scientist at Megaline mobile operator company, I have been tasked with developing a model that can analyze consumer behavior and recommend one of the two latest Megaline packages: Smart or Ultra, with a minimum accuracy of 0.75.

After analyzing and creating the model, the following is a summary of the project:
In this project, I created a simple machine learning model using the Random Forest algorithm because it was found to have the highest accuracy compared to the Decision Tree and Logistic Regression models.

Initially, the model I created had an accuracy of only 0.74. However, after performing hyperparameter tuning using the GridSearchCV method, the accuracy increased to 0.81 with a value of n_estimators equal to 88. Although the accuracy decreased in the test dataset with n=88, a sanity check showed that an n value of 88 was still better than n=10
