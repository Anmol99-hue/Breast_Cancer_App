# Breast_Cancer_App
## Project Description

This project focuses on analyzing the Breast Cancer dataset and building a user-friendly, interactive web application using Streamlit. The app enables users to explore the dataset, train an Artificial Neural Network (ANN) model, and view predictions. It also demonstrates key machine learning workflows, including data preprocessing, feature selection, model optimization, and deployment.

## Key Features

1. Dataset Analysis: Preprocess and analyze the Breast Cancer dataset.
2. Feature Selection: Implement feature selection techniques using SelectKBest.
3. Model Training: Train an ANN model using MLPClassifier from sklearn.neural_network.
4. Hyperparameter Tuning: Use Grid Search Cross-Validation to optimize ANN parameters.
5. Interactive App: Build a Streamlit-based app for exploring the dataset and visualizing model predictions.
6. Version Control: Use Git for version control and collaboration.

## Technologies Used

-> Programming Language: Python

-> Libraries:
              
              Data Analysis: pandas, numpy, scikit-learn
              Visualization: matplotlib, seaborn
              Web Application: streamlit

# Project Deliverables:
  This repository includes:
   1. Requirements.txt file
   2. Jupyter Notebook for data preparation, feature selection, model training
   3. .pkl file for scaler and best model for ANN
   4. .py script for app development.

  
# Steps to Create this Project
## 1. Project Set Up:
   Initialized a Git repository.
   Created and activated a virtual environment.
   Installed necessary libraries.

## 2.Dataset Acquisition and Preparation:
   Downloaded the Breast Cancer dataset using sklearn.datasets.
   Loaded the dataset.

## 3. Feature Selection:
   Applied SelectKBest to identify the top features for model training.
   
## 4. Hyperparameter Tuning:
   Used Grid Search Cross-Validation to optimize the parameters of the ANN (MLPClassifier).

## 5. Artificial Neural Network Implementation
   Trained and evaluated an ANN model using the MLPClassifier from sklearn.neural_network.
   Split the dataset into training and testing subsets for evaluation.

## 6. Building the Streamlit App:
   Created an interactive web app with Feature selection through a sidebar and Model training and accuracy display.
    
