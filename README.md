# wine-detector
##Introduction
This code aims to create a predictive model to solve a classification problem using KNN, following the pipeline seen in class. The dataset contains the results of the chemical analysis of wines produced by three different Italian cultivators. The objective is to determine the type of wine from its chemical values.

##Libraries and Dataset
The code imports the necessary libraries such as sklearn and numpy. The dataset used is the "wine" dataset provided by scikit-learn, which contains the attributes and the class of the wines.

##Exploratory Data Analysis
The code displays the various attributes of the dataset such as target names, feature names, and data shape. It also extracts the feature matrix and the label vector.

##Data Preprocessing
The code shuffles the dataset using numpy and splits it into training and testing sets using the train_test_split function of the sklearn library.

##K-Nearest Neighbors Implementation
The code implements the KNN model using the KNeighborsRegressor function and fits the model to the training data. It then demonstrates two methods for computing the Euclidean distance between two points.

##Conclusion
In conclusion, this code provides a comprehensive guide to implementing KNN to solve a classification problem. It also includes data preprocessing and exploratory data analysis, which are important steps in building any machine learning model.
