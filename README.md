# regression_fetch_california_housing_FUNCTIONAL-_API
# Functional API in Keras

This repository demonstrates the use of the Functional API in Keras for building neural networks.  The Functional API offers more flexibility than the Sequential API, allowing for the creation of more complex architectures, including models with multiple inputs, multiple outputs, shared layers, and residual connections.

## What is the Functional API?

The Keras Functional API is a way to define models where layers are treated as functions.  Instead of sequentially adding layers to a model like in the Sequential API, you explicitly connect layers by passing the output of one layer as the input to the next. This approach allows you to define complex computational graphs, making it suitable for building a wide range of architectures.

Key features of the Functional API:

* **Flexibility:** Enables building complex architectures beyond simple sequential models.
* **Layer as Functions:** Treats layers as functions that take tensors as input and return tensors as output.
* **Explicit Connections:**  Requires explicitly defining the connections between layers, providing more control over the model's structure.
* **Multiple Inputs/Outputs:** Supports models with multiple inputs and/or outputs.
* **Shared Layers:** Allows sharing layers across different parts of the model.

## Code Description

The provided code defines a simple neural network using the Functional API.
