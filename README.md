## Project Overview

Welcome to the Dragon Real Estates housing price prediction project! 
This project demonstrates a comprehensive machine learning workflow, leveraging various features of the Boston Housing dataset from the UCI Machine Learning Repository. 
The primary objective is to predict housing prices using multiple regression models, including Linear Regression, Decision Tree, and Random Forest. 
The project includes data preprocessing steps, exploratory data analysis, model training, evaluation, and comparison.

## Dataset

The dataset used in this project is the Boston Housing dataset from the UCI Machine Learning Repository. 
It includes various features that describe different aspects of residential homes in Boston, such as crime rate, property tax rate, and the number of rooms.

## Detailed Description

In this project, we begin by loading the Boston Housing dataset and performing initial preprocessing. This includes handling missing values, encoding categorical features, 
and splitting the data into training and testing sets to ensure that our models can generalize well to unseen data. Exploratory Data Analysis (EDA) is conducted to gain insights into the data distribution, detect outliers,
and visualize relationships between features. We use various visualizations, such as histograms to understand the distribution of individual features, scatter plots to explore relationships between different features, 
and a correlation matrix to identify which features are most strongly correlated with the target variable.

To handle missing values, particularly in the CHAS feature, we use simple imputation techniques, filling in missing values with the median of the column. 
This helps in maintaining the integrity of the dataset without losing any data. Feature engineering is performed next, 
where we scale the features using StandardScaler to ensure that all features contribute equally to the model training process. 
This step is crucial for models like Linear Regression, which can be sensitive to the scale of input features.

We then proceed to train and evaluate three different regression models: Linear Regression, Decision Tree, and Random Forest. 
For each model, we train on the training dataset and evaluate its performance on the test dataset using Mean Squared Error (MSE) as the metric. 
Additionally, we perform cross-validation to get a more reliable estimate of the model's performance and to ensure that it generalizes well. 

Linear Regression is our baseline model, providing a straightforward approach to understanding the relationships between features and the target variable. 
The Decision Tree model is then employed to capture non-linear relationships in the data, followed by the Random Forest model, 
which is an ensemble method that combines multiple decision trees to improve performance and reduce overfitting.

Finally, we compare the performance of these models to determine which one fits the data best. 
This comparison is based on their cross-validated MSE scores and their ability to generalize to the test data. 
The project concludes with a summary of our findings and conclusions, highlighting the most effective model for predicting housing prices in the Boston area and 
providing insights into the importance of different features in the prediction process.

### ENJOY !!!
