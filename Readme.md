# Ransomware Classification Project

This project aims to classify ransomware files from benign files using machine learning models.

## Overview

Ransomware is a type of malicious software that encrypts files and demands payment (ransom) from the victim to restore access to their data. Identifying ransomware files is crucial for cybersecurity to prevent potential data breaches and financial losses.

This project uses machine learning techniques to classify files as ransomware or benign based on their features. We explore various machine learning algorithms such as Random Forest, XGBoost, and Artificial Neural Networks (ANN) to build and evaluate classification models.


## Project Structure

- `Ransomware_Classification_P−M−20240420−I−AIML_10.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, evaluation, and inference.
- `data_file.csv`: CSV file containing the dataset used for training and testing the models.
- `new_data_file.csv`: CSV file containing new data for inference.
- `selected_features_data.csv`: CSV file containing new data for inference.
- `random_forest_model.pkl`: Pickle file containing the trained Random Forest model.
- `xgboost_model.pkl`: Pickle file containing the trained XGBoost model.
- `dnn_model/`: Directory containing the saved Artificial Neural Network model.

## Getting Started

To run the project, follow these steps:

1. Upload the `.ipynb` file on Google colab. 
2. Run all code snippets sequentially.

## Results

- Random Forest Model Accuracy: 99.92%
- XGBoost Model Accuracy: 99.81%
- ANN Model Accuracy: 98.58%