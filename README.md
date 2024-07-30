This repository contains a Jupyter Notebook designed for use with AWS Amazon Personalize. The primary purposes of this notebook are:

Data Adjustment and Manipulation:

The notebook includes scripts to preprocess and adjust the dataset so that Amazon Personalize can effectively read and train a model on it.
Geolocation-Based Recommendations:

It also incorporates functionality to match the geolocations of recommended items. This ensures that Amazon Personalize recommends items within available locations and closer distances, enhancing the relevance and accuracy of recommendations based on geographic proximity.
Key Features:
Data Preprocessing:

Cleaning and formatting data for Amazon Personalize.
Handling missing values and ensuring data consistency.
Geolocation Matching:

Mapping item locations to user geolocations.
Adjusting recommendations to prioritize items that are geographically closer to users.
Model Training:

Setting up and training models using Amazon Personalize.
Fine-tuning hyperparameters for optimal performance.
Usage:
Data Preparation:

Import your dataset into the notebook.
Follow the steps to preprocess the data.
Geolocation Integration:

Add geolocation data to your items and users.
Use the provided functions to match and filter recommendations based on location.
Model Training and Evaluation:

Train your Amazon Personalize model using the prepared dataset.
Evaluate and refine your recommendations.
This notebook aims to provide a comprehensive solution for integrating geolocation-based recommendations with Amazon Personalize, improving the accuracy and relevance of your recommendation system.
