# Machine Learning Algorithms Implementation

This repository contains implementations of various machine learning algorithms. Each algorithm is implemented in Python and includes a description, code, and analysis.

## Perceptron Learning Algorithm

### Description
The perceptron learning algorithm is implemented for classifying a linearly separable dataset in 2D.

### Implementation
The implementation includes dataset creation, the perceptron learning algorithm, and analysis.

#### Dataset Creation
A linearly separable dataset with at least 1000 data points is created.

#### Perceptron Learning Algorithm
The algorithm is implemented to classify the dataset.

#### Analysis
Observations are discussed with respect to the number of iterations required for perfect classification by varying the level of separability in the dataset.

### Usage
To run the perceptron learning algorithm, execute the `perceptron.py` script.

## Gradient Descent for Training a Linear Classifier

### Description
Gradient descent is used for training a linear classifier on a linearly separable 2D dataset.

### Implementation
The implementation includes loss formulation, gradient computation, and the update equation.

#### Loss Formulation
A loss function based on classroom discussions is formulated.

#### Gradient Computation
The gradient of the loss function is computed analytically.

#### Update Equation
The basic version of the gradient descent update equation is implemented.

### Usage
To train the linear classifier using gradient descent, execute the `gradient_descent.py` script.

## MLP with a Single Hidden Layer

### Description
A Multi-layer Perceptron (MLP) with a single hidden layer is trained for binary classification on a non-linearly separable dataset in 2D.

### Implementation
The implementation includes dataset creation, MLP definition, backpropagation algorithm, and elegance/recursion considerations.

#### Dataset Creation
A binary classification dataset that is not linearly separable in 2D is created (e.g., data lying on the circumference of two concentric circles).

#### MLP Definition
The architecture of the MLP with a single hidden layer is defined.

#### Backpropagation Algorithm
The gradient descent algorithm (backpropagation) is implemented for training the MLP.

#### Elegance/Recursion
Considerations for elegance and recursion in the implementation are discussed.

### Usage
To train the MLP with a single hidden layer, execute the `mlp.py` script.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
