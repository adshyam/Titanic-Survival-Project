Titanic Survival Prediction

This project aims to predict the survival rate of passengers on the Titanic using machine learning algorithms. The goal is to build a model that can 
accurately predict which passengers are likely to survive based on their age, gender, class, and other features.

Dataset:

The dataset used in this project is the Titanic dataset, which contains information about the passengers. The dataset has 891 rows and 12 columns. The 
columns include information such as age, sex, passenger class, and whether the passenger survived or not.
Here is a link of dataset used : https://raw.githubusercontent.com/SowjanyaPatnaik/Data-Science-notes/main/train.csv


Data Preprocessing:

The data was preprocessed by handling missing values, transforming categorical data into numerical data and scaling the data. The missing values 
in the Age feature were filled with the mean age, while the missing values in the Embarked feature were filled with 'S'. The categorical 
features (Sex and Embarked) were transformed into numerical features using one-hot encoding, and the continuous features (Age and Fare) were scaled 
using StandardScaler.

Feature Engineering:

The features used in this model were Sex, Age, Pclass, SibSp, Parch, and Fare. The Name and Ticket features were dropped, and the Cabin feature was 
excluded due to its high percentage of missing values. New feature 'Alone' was created to extract more meaningful information from the existing features.

Modeling:

The model was trained using Random Forest Classifier algorithm, which achieved an accuracy score of 0.88 on the test set. The model was evaluated 
using precision, recall, and F1-score. A classification report was also used to visualize the model's performance.

Results:

The model achieved an accuracy of 0.88 on the test set. The classification report showed that the model had a high accuracy rate for predicting survivors,
but a slightly lower accuracy rate for predicting non-survivors.
