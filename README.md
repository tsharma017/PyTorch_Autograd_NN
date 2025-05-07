# Autograd in Python: Automatic Differentiation Made Easy

Autograd is a Python library for automatic differentiation (autodiff), which efficiently computes gradients (derivatives) of functions. It is widely used in machine learning, optimization, and scientific computing, especially in libraries like PyTorch and JAX (which evolved from Autograd).

Key Features of Autograd
Automatic Differentiation

Computes gradients of any Python or NumPy function.

Supports forward-mode and reverse-mode (backpropagation) differentiation.

NumPy-Compatible

Works seamlessly with NumPy arrays (ndarray).

Just replace import numpy as np with import autograd.numpy as np.

Supports Higher-Order Gradients

Can compute second derivatives (Hessians) and beyond.

Used in Deep Learning

PyTorch’s autograd and TensorFlow’s GradientTape are inspired by Autograd.

How Autograd Works
Tracks Operations

When you perform computations, Autograd builds a computational graph.

It records how variables depend on each other.

Computes Gradients via Backpropagation

When you call .grad(), it traverses the graph backward to compute derivatives.
