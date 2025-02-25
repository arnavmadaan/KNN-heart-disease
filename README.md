# KNN-heart-disease
This repository contains a machine learning model that predicts the risk of heart disease using patient medical data. The dataset used is `hf.csv.csv`, which includes features such as age, blood pressure, serum creatinine, and other relevant medical indicators. The model employs K-Nearest Neighbors (KNN) for classification.

## Table of Contents
- [Overview](#overview)
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Implementation](#model-implementation)
- [Results](#results)

## Overview
This project aims to provide an early prediction of heart disease based on medical parameters. It serves as a practical example of applying machine learning techniques in healthcare. **Note:** This project was originally developed during my high school years as a learning exercise. While it is a basic implementation, it demonstrates foundational concepts in data preprocessing, model training, and prediction. The code has been refined and documented to serve as an educational resource for beginners and enthusiasts in machine learning.

## Project Description
This project demonstrates the application of machine learning to predict heart disease risk based on patient medical data. It utilizes a dataset comprising patient age, blood pressure, serum creatinine, and several other key medical indicators. The classification model, built with the K-Nearest Neighbors (KNN) algorithm, categorizes patients into risk groups for heart disease. Although the project started as a high school endeavor and remains relatively basic, it effectively illustrates essential concepts of data processing, model building, and evaluation using Python and relevant libraries. It is ideal for beginners looking to understand how machine learning can be applied in healthcare.

## Dataset
- **File Name:** `hf.csv.csv`
- **Number of Records:** 299
- **Number of Features:** 12 (excluding the target column `DEATH_EVENT`)
- **Target Variable:** `DEATH_EVENT` (1 = Risk of heart disease, 0 = No risk)

## Technologies Used
- Python
- Pandas, NumPy (Data Processing)
- Scikit-Learn (Machine Learning - KNN Classifier, Data Preprocessing)
- Keras (Neural Network Implementation - Optional)
- Jupyter Notebook

## Installation
Clone this repository and install the required dependencies.
```sh
$ git clone https://github.com/arnavmadaan/KNN-heart-disease.git
$ cd KNN-heart-disease
$ pip install -r requirements.txt
```
## Usage

1. Open the Jupyter Notebook:
```sh
    $ jupyter notebook
```
2. Run the notebook cells sequentially to:
```sh
        Load the dataset
        Preprocess the data
        Train the KNN model
        Evaluate model performance
        Predict heart disease risk based on user input
```
## Model Implementation

Data Preprocessing: Standardization using StandardScaler.
Classification Model: K-Nearest Neighbors (KNN) with n_neighbors=6.
User Input Prediction: The user is prompted to enter medical details, and the model predicts the risk.

## Results

The model achieves good accuracy in predicting heart disease risk based on the provided medical dataset. More evaluation metrics such as confusion matrix, precision-recall, and ROC curve can be added for deeper insights.





