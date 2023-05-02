# Titanic_survival_prediction

This repository contains an analysis of the Titanic dataset, which includes information on passengers who were aboard the Titanic when it sank.

Data Cleaning
The dataset was cleaned using a series of user-defined functions. Null and missing values were filled using the following methods:

Age: median value for each sex
Embarked: mode value
Cabin: converted to binary based on whether the value was missing or not
Fare: median value
Data Preparation
After cleaning the data, numerical values were scaled using StandardScaler from the sklearn.preprocessing module. Categorical variables were one-hot encoded One-Hot Encoder.

Model Selection
A train-test split was performed using 80% of the data for training and 20% for testing. The following models were tested using grid search CV:

Logistic Regression
Decision Tree Classifier
KNN Classifier
Random Forest Classifier

Results
The best accuracy was achieved using the KNN Classifier with a score of 0.8. Predictions were made using this model and visualizations were created to display the results.

Files
titanic survival prediction.ipynb: Jupyter notebook containing the analysis
train.csv: training dataset
test.csv: testing dataset
README.md: this file

Requirements
This analysis was performed using Python 3.9. The following modules were used:

pandas
numpy
matplotlib
seaborn
scikit-learn

Running the Notebook
To run the analysis, you can download the repository and open the titanic.ipynb notebook in Jupyter. Make sure you have installed the required modules before running the code.
