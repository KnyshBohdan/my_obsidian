Activation Functions serve as the gatekeepers of the Artificial Neural Networks, deciding the output of a node given a set of inputs. They introduce the necessary non-linear properties to the system, allowing the network to learn from the error and make adjustments.

## Definition

An Activation Function is a mathematical function that takes an input and produces an output based on a certain criterion. It introduces non-linearity into the system, enabling the network to learn complex mappings from the input data.

f(x)=Activation Function applied to weighted sum of inputsf(x)=Activation Function applied to weighted sum of inputs

## Types of Activation Functions

1. **Linear Function**: $f(x) = x$
    
    - **Range**: $-\infty$ to $+\infty$
    - **Uses**: Output layer in regression problems.
2. **Sigmoid Function**: $f(x) = \frac{1}{1 + e^{-x}}$
    
    - **Range**: 0 to 1
    - **Uses**: Output layer in binary classification.
3. **Tanh Function**: $f(x) = \tanh(x)$
    
    - **Range**: -1 to +1
    - **Uses**: Hidden layers.
4. **ReLU (Rectified Linear Unit)**: $f(x) = \max(0, x)$
    
    - **Range**: $[0, \infty)$
    - **Uses**: Hidden layers, commonly used in CNNs.

### Key Concepts

- **Non-linearity**: Enables the network to learn from the error backpropagated.
- **Vanishing & Exploding Gradient**: Issues that arise with certain activation functions during backpropagation.

## Applications

- **Classification**: Sigmoid and Softmax functions are commonly used.
- **Regression**: Linear functions can be used in the output layer.
- **Deep Learning**: ReLU and its variants are often used in CNNs.

## Challenges

- **Computational Complexity**: Some functions like Sigmoid and Tanh are computationally expensive.
- **Vanishing Gradient**: Sigmoid and Tanh suffer from this problem, making the network hard to train for several layers.

## Connection to Other Topics

- **[[Neural Networks]]**: Activation functions are a fundamental component.
- **[[Backpropagation]]**: The choice of activation function affects how backpropagation is computed.
- **[[Convolution Neural Networks]]**: ReLU is commonly used here.