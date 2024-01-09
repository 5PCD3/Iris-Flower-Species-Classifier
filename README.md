# Iris Flower Species Classification

## Overview
This repository contains a machine learning model for classifying Iris flower species using the K-Nearest Neighbors (KNN) algorithm. The model is trained on the famous Iris dataset, which includes measurements of sepal length, sepal width, petal length, and petal width for three different species: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Dataset
The dataset used for training and testing the model is available in the 'Data' directory as 'IRIS.csv'. It includes both numerical and categorical columns, where numerical columns represent the measurements, and the categorical column ('species') contains the target labels.

## Data Preprocessing
The data preprocessing steps include segregating numerical and categorical columns, mapping categorical labels to numerical values, and splitting the dataset into training and testing sets.

## Feature Scaling
To enhance the performance of the KNN algorithm, the numerical features are standardized using the StandardScaler from scikit-learn.

## Model Training
The KNN classifier is trained on the scaled training data with k=3 (3 neighbors).

## Model Evaluation
The model is evaluated on the scaled test set, and accuracy is calculated using scikit-learn's accuracy_score.

## Model Persistence
Both the trained KNN classifier and the StandardScaler are saved as pickle files for future use. The files are stored in the 'Model' directory as 'IRIS_Classifier.pkl' and 'StandardScalar.pkl', respectively.


