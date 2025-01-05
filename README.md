# Heart-Disease-Prediction

This repository contains a Jupyter notebook i.e ClassificationTask.ipynb, designed to demonstrate the process of data analysis, preprocessing, model training with logistic regression

# Data Insights 
The data is about that a personal risk to getting heart Disease 
The data columns contain about medical reports and personal things

# Overview
The notebook is structured into multiple sections, covering:

Importing Libraries and Dataset: Loading the required libraries and data for analysis.
Data Insights: Exploring the dataset to uncover patterns, filled missing values mean and for frequent values filled with mode, and other characteristics.
Visualization using pairplot, bar, heatmap, countplot, 3d visualization
Finding Outliers and removing them, And checked if outliers are really impacting the model.
Feature Preparation: Creating feature (x) i.e input varible and target (y) variable for machine learning models.
Feature Scaling: Used StandardScaler

so the dataset give an idea about classification problem, so i used logistic regression.

The dataset is full if imbalanced data, means ther are more false and less true values. 

Without using class weights i got 85 score and 86 accuracy, but there are more false positive and negative in prediction, so it is not good for prediction.
By using class weights in logistic regression it balanced and got score 66, accuracy 67.

By using Confusion matrix i found ther are false positive and false negative.

So the model need more imporvement.
