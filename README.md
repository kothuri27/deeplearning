# Machine Learning Tasks Overview

# Task 1: Fundamentals of Machine Learning
## Perceptron Learning Algorithm
### Description:
- Implementation of perceptron learning algorithm for classifying a linearly separable dataset in 2D.
- Includes dataset creation, training, and analysis.

### Files:
- perceptron_learning_algorithm.py

## Gradient Descent for Training a Linear Classifier
### Description:
- Solving the classification problem using gradient descent algorithm.
- Includes loss formulation, gradient computation, and update equation implementation.

### Files:
- gradient_descent.py

## MLP with a Single Hidden Layer
### Description:
- Training a Multi-layer Perceptron (MLP) with a single hidden layer for binary classification on a non-linearly separable dataset in 2D.

### Files:
- mlp_single_hidden_layer.py

# Task 2: Visualization Techniques for CNNs and SGD Update Rules
## Variants of Backprop for Visualizing CNNs
### Description:
- Implementing and visualizing different backpropagation variants for Convolutional Neural Networks (CNNs) using a pre-trained ResNet-50 model.

### Files:
- cnn_visualization.py

## SGD Update Rule Variations
### Description:
- Implementing various update rules for Stochastic Gradient Descent (SGD) to find the minimum for a given function.
- Includes visualization of convergence paths.

### Files:
- sgd_update_rules.py

# Task 3: Recurrent Neural Networks (RNNs) for Sequence Summation
## The Adding Problem
### Description:
- Training different RNN models (Elmon network, LSTM, and GRU) to solve the sequence summation problem.
- Comparison against a baseline model.
- Includes dataset creation, training, and performance analysis.

### Files:
- rnn_sequence_summation.py

# Task 4: Autoencoders, Variational Autoencoder (VAE), and Self-Attention in CNN
## Autoencoders
### Description:
- Training autoencoder models on the MNIST dataset with hidden dimensions of 32 and 64.
- Reporting reconstruction errors and performing reconstructions in the hidden space.

### Files:
- autoencoders.py

## Variational Autoencoder (VAE)
### Description:
- Training a VAE on the MNIST dataset to generate MNIST-like digits.
- Generating and displaying images.

### Files:
- vae.py

## Self-Attention in CNN
### Description:
- Implementing a CNN with one or more self-attention layer(s) for object recognition over the CIFAR-10 dataset.

### Files:
- cnn_self_attention.py

# License
This project is licensed under the MIT License - see the LICENSE file for details.
