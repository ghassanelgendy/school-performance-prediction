# Learning From Data Project

## Overview

This repository contains the implementation of machine learning models used to predict high school student performance based on various features. The project utilizes **Support Vector Machines (SVM)** and **Neural Networks (NN)** to explore classification performance and evaluate model accuracy, precision, recall, and generalization.

## Models Implemented

### Support Vector Machine (SVM)
The SVM model was trained and evaluated on the dataset to classify student performance. The model's performance was assessed using various metrics such as **accuracy**, **precision**, **recall**, and the **AUC** (Area Under the Curve) of the ROC curve. The SVM showed high accuracy and excellent generalization capabilities.

### Neural Network (NN)
A neural network with two hidden layers was implemented to predict student performance. The network used ReLU activation for hidden layers and sigmoid activation for the output layer, designed for binary classification. The performance of the neural network was also evaluated using similar metrics to compare it with the SVM model.

## Features

- **Data Preprocessing**: Feature engineering, normalization, and encoding.
- **Model Training**: SVM with linear kernel, neural network with 2 hidden layers.
- **Model Evaluation**: Confusion matrix, classification report, ROC curve, AUC.


---

## Results

The models' performance was evaluated using metrics such as:

- **Accuracy**: The percentage of correct predictions.
- **Precision, Recall, F1-Score**: Evaluation for both classes.
- **AUC-ROC**: Performance measurement of classification quality.

## Conclusion

This project highlights the comparative performance of **SVM** and **Neural Networks** for predicting student performance. The SVM model outperformed the neural network in terms of accuracy, generalization, and AUC, making it the preferred model for this classification task.
