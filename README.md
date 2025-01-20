# Loan-Approval-Prediction
This project aims to predict loan approval for applicants based on various features using machine learning. The model is built using the Keras library with TensorFlow backend.
Introduction
The goal of this project is to predict whether a loan application will be approved based on features such as applicant’s credit history, income, employment status, and other factors. We utilize a neural network model built with Keras, a high-level neural networks API, to make predictions on the loan approval status.

Dataset
The dataset used for this project is a sample loan approval dataset. The dataset includes various features like:
Loan ammount 
time period 
interest rate 
intallment ammount
other features

In this project libraries used are:
tensorflow,
pandas,
numpy,
scikit-learn,
matplotlib,
seaborn.

Model
The model is a simple feedforward neural network with the following layers:

Input Layer: Takes the input features
Hidden Layers: Two hidden layers with ReLU activation
Output Layer: Single neuron with a sigmoid activation function to predict a binary output (0 or 1)
The model is compiled using binary cross-entropy loss and Adam optimizer.

Evaluation
Model performance is evaluated using:

Accuracy
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)
