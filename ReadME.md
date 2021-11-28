# Perceptron Learning ALgorithm (PLA)

## What is the Perceptron learning algorithm?
The Perceptron is a linear machine learning algorithm for binary classification tasks.

Like logistic regression, it can quickly learn a linear separation in feature space for two-class classification tasks, although unlike logistic regression, it learns using the stochastic gradient descent optimization algorithm and does not predict calibrated probabilities.

The Perceptron is one of the simplest ANN architectures, invented in 1957 by Frank Rosenblatt. It is based on a slightly different artificial neuron.
The inputs and output are now numbers (instead of binary on/off values) and each input con‐nection is associated with a weight. The TLU computes a weighted sum of its inputs (z = w_1 x_1 + w_2 x_2 + ⋯ + w_n x_n = x^T w), then applies a step function to that sum and outputs the result: h_w(x) = step(z), where z = x^T w.The picture below is a threshold logic unit (TLU).



## How does the Perceptron works.

The Perceptron receives multiple input signals, and if the sum of the input signals exceeds a certain threshold, it either outputs a signal or does not return an output. In the context of supervised learning and classification, this can then be used to predict the class of a sample.
it is typically represented using a special type of neu‐ron called a bias neuron, which just outputs 1 all the time.
