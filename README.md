# Email Spam Classification

## Overview

This repository contains code for a machine learning model that classifies emails as spam or non-spam (ham). The model uses a Support Vector Machine (SVM) algorithm with a text classification approach.

## Table of Contents

- [Background](#background)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Data](#data)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Tuning](#tuning)
- [Results](#results)

## Background

This project aims to build a machine learning model for classifying emails as spam or non-spam. The SVM algorithm is chosen for its effectiveness in text classification tasks.

## Features

- Text classification using Support Vector Machine (SVM)
- Model training, evaluation, and tuning scripts

## Requirements

- Python 3.6+

## Usage
- To use the Email Spam Classification code, follow these steps:

1. Prepare Your Data:

   Ensure your email data is in a suitable format for the model. For example, a CSV file with columns for email text and labels.

2. Train the Model:

   Use the train_model.py script to train the SVM model on your training data.

3. Make Predictions:

   After training, you can use the model to make predictions on new email data.

## Data
- The dataset used for this project can be found at Dataset Source.

## Model Training
- To train the SVM model on your data, use the train_model.py script. Ensure your data is properly formatted and split into training and testing sets.

## Evaluation
- Evaluate the model's performance using the evaluate_model.py script. This will provide insights into accuracy and other relevant metrics.

## Tuning
- Experiment with hyperparameter tuning to improve model performance. Adjust parameters in the tuned_param dictionary within the train_model.py script.

tuned_param = {'kernel': ['linear', 'rbf'], 'gamma': [1e-3, 1e-4], 'C': [1, 10, 100, 1000, 10000]}

## Results
- Share the results of your model, including accuracy, precision, recall, and F1 score. Discuss any interesting observations or challenges encountered during the project.
