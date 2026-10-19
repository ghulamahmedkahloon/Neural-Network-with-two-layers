# Two-Layer Neural Network from Scratch

A foundational machine learning project implementing a two-layer neural network using NumPy. The project explores the mathematical operations behind a neural network, from forward propagation to backpropagation and parameter updates.

**Project type:** Guided machine learning coursework  
**Implementation:** NumPy  
**Language:** Python

## Overview

This project focuses on understanding how a neural network works internally by implementing its core computations rather than relying on a deep learning framework to handle them.

The network uses an input layer, one hidden layer, and an output layer. It learns from labeled data by making predictions, calculating a loss, computing gradients, and updating its parameters during training.

This implementation was completed as part of guided machine learning coursework.

## Objectives

- Understand the architecture of a two-layer neural network.
- Implement forward propagation using matrix operations.
- Calculate the cost function from model predictions.
- Implement backpropagation to calculate gradients.
- Update weights and biases using gradient descent.
- Understand how the network learns from training data.

## Model Architecture

The network consists of two trainable layers:

1. **Hidden layer:** Receives the input features and applies a learned linear transformation followed by an activation function.
2. **Output layer:** Uses the hidden layer's activations to produce the final prediction.

The network's parameters include weight matrices and bias vectors for both layers.

## Methodology

The implementation follows the neural network training process:

1. **Initialize parameters:** Set up the weights and biases for both layers.
2. **Forward propagation:** Calculate activations and generate predictions from the input features.
3. **Cost calculation:** Measure the difference between predictions and the true labels using the task's cost function.
4. **Backpropagation:** Apply the chain rule to calculate gradients for the network's parameters.
5. **Parameter updates:** Use gradient descent to adjust the weights and biases.
6. **Training and evaluation:** Repeat the learning process and examine the model's predictions.

## Technologies Used

- **Python** — programming language
- **NumPy** — numerical computation and matrix operations
- **Jupyter Notebook** — interactive coding and experimentation

## Key Concepts Practiced

- Neural network architecture
- Matrix multiplication and vectorization
- Activation functions
- Forward propagation
- Cost functions
- Backpropagation and the chain rule
- Gradients and gradient descent
- Weights, biases, and parameter optimization

## How to Run

1. Clone or download this repository.
2. Install Python and the required dependencies.
3. Open the notebook in Jupyter.
4. Run the notebook cells in order.

Install the main dependencies:

```bash
pip install numpy matplotlib jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

**Note:** If the notebook relies on course-provided datasets, helper functions, or other supporting files, those resources must also be available for the notebook to run completely.

## Learning Outcome

This project helped me develop a more practical understanding of how neural networks learn through mathematical operations, gradients, and iterative parameter updates. Implementing the core steps with NumPy makes the relationship between linear algebra, calculus, and machine learning more concrete.

## Acknowledgment

This project is based on guided machine learning coursework. The repository is intended to document my learning and practice with neural network fundamentals.

## Author

**Ghulam Ahmad Kahloon**

- Portfolio: [ghulamahmadkahloon.com](https://ghulamahmadkahloon.com/)
- GitHub: [ghulamahmedkahloon](https://github.com/ghulamahmedkahloon)
