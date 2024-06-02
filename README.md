# Code_Alpha_Disease_Prediction
This repository contains code for predicting diseases based on features extracted from medical data using machine learning models. The models included are K-Nearest Neighbors (KNN), Random Forest, and Logistic Regression. The models are trained and tested on a dataset containing medical features and associated disease labels.

#Dataset : 
The dataset used for training and testing the models is located at /content/drive/MyDrive/data/dataset.csv. This dataset contains information about medical features and their associated diseases.

#Preprocessing : 
Check for missing values in the dataset and drop rows with missing values.
Split the dataset into features (X) and target (y).

#Model Training : 
Train KNN, Random Forest, and Logistic Regression models on the training data.
Evaluate the trained models using accuracy metrics and confusion matrices.

#Input Features : 
You can provide custom input features to the trained models for predicting diseases based on medical data features. Input features should be standardized using the StandardScaler before making predictions.

#Saved Models : 
The trained models (KNN, Random Forest, and Logistic Regression) are saved and can be loaded for making predictions on new data.

#Evaluation : 
The performance of each model is evaluated using accuracy metrics and confusion matrices.
Accuracy scores are calculated on the test set, and confusion matrices are plotted to visualize the performance.
