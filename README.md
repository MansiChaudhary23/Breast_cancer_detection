# Breast Cancer Detection using Neural Network (TensorFlow/Keras)

## Overview
A binary classification system that predicts whether a breast tumor is Malignant (0) or Benign (1) using a feedforward neural network trained on the sklearn Breast Cancer dataset.

## Dataset
Source: sklearn.datasets.load_breast_cancer()
569 samples, 30 numerical features
Target: 212 Malignant, 357 Benign
No missing values

# Tech Stack
Python, NumPy, Pandas, Scikit-learn, TensorFlow, Keras, Matplotlib

# Model Architecture
Input Layer: 30 features (Flatten)
Hidden Layer: 20 neurons, ReLU activation
Output Layer: 2 neurons, Sigmoid activation
Optimizer: Adam | Loss: Sparse Categorical Crossentropy

# Results
Accuracy = 93.86%
Epochs = 10
Val Accuracy= 97.83%
