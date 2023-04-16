## AIC_DATA
### Terrorism Data Analysis and Visualization
This README provides an overview of the code used for analyzing and visualizing terrorist attacks from a given dataset. The code includes data cleaning, statistical analyses, various charts, and interactive maps.

Data Preparation
The code imports necessary libraries and reads the dataset from a CSV file. It then selects relevant columns and performs data cleaning, such as filling missing values and dropping remaining rows with NaN values. The cleaned data is saved to a new CSV file.

Statistical Analyses
The code computes the percentage of terrorist attacks that were claimed and displays the result.

Charts
The code generates several bar charts to visualize the data, including:

Number of attacks per year
Number of attacks by weapon type
Number of attacks by attack type
Number of attacks by weapon sub-type
Number of attacks by country (top 10)
Interactive Maps
The code creates several interactive maps using the Folium library, including:

A global map with clusters of terrorist attacks
Heatmaps for each continent
Maps displaying individual attacks for each continent
A global heatmap
Each map is saved as an HTML file for easy viewing in a web browser.

## AIC_IA


This code is designed to analyze and predict various aspects related to terrorist attacks using machine learning algorithms. It focuses on predicting the number of victims (killed and wounded), the country where the attack took place, the type of weapon used, and the subtype of weapon used.

### Overview
Imports necessary libraries
Loads and preprocesses the dataset
Trains and evaluates a Random Forest Regressor to predict the number of victims (killed and wounded)
Trains and evaluates a Logistic Regression model to predict the country where the attack took place
Trains and evaluates a Neural Network (MLP Regressor) to predict the number of victims (killed and wounded) after selecting the best features
Trains and evaluates a Random Forest Classifier to predict the type and subtype of weapon used in the attack
Visualizes the results, such as confusion matrices, correlation heatmaps, and prediction plots

### Requirements
Python 3
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### Usage
Install the required libraries.
Make sure the dataset file is in the same directory as the code.
Run the code using a Python interpreter or an IDE like Jupyter Notebook, Spyder, or PyCharm.
Evaluate the model's performance using various metrics, such as accuracy, mean squared error, mean absolute error, and R-squared.
Visualize the results using graphs like scatter plots, error distribution plots, and heatmaps.

### Notes
The code uses various machine learning algorithms, such as RandomForestRegressor, LogisticRegression, MLPRegressor, and RandomForestClassifier.
It employs techniques like label encoding, feature scaling, and feature selection to preprocess the data and improve the model's performance.
The code can be easily modified to include other machine learning algorithms or additional features for prediction.
The dataset used may need to be updated or replaced with a more recent version to improve the accuracy of the predictions.
