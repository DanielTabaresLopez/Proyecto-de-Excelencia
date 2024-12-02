# Neural Networks and Perceptron Implementation

This repository contains two Python implementations for machine learning models:

1. A **Multi-Layer Neural Network (MLP)** for multi-class classification on the Iris dataset.
2. A simple **Perceptron** for binary classification on a subset of the Iris dataset.

Both scripts are written in Python and use popular libraries such as `numpy`, `scipy`, and `matplotlib`.


## Dataset Used
The Iris dataset from the sklearn library is used in both scripts. This dataset consists of three classes of 50 samples each, where each class refers to a type of iris plant: Setosa, Versicolor, and Virginica.
- For perceptron.py :
Only two classes (Setosa and Versicolor) are used for binary classification.

- For neural_network.py :
All three classes are used for multi-class classification.


## Results
- perceptron.py :
Shows how the perceptron algorithm learns a linear decision boundary for binary classification.
Plots the learning progress and decision boundary for better understanding.

- neural_network.py :
Demonstrates the accuracy of a multi-layer neural network trained using backpropagation.
Visualizes the cost function to analyze convergence.

