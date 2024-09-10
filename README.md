# Neural Network in Lua (LÖVE 2D) - README

## Overview

This project implements a simple neural network in Lua using the LÖVE 2D framework. The network can learn from data through training and provides a visual representation of the network's nodes and connections. It supports a single hidden layer with dynamic nodes, allowing you to modify the network structure easily.

## Features

- **Feedforward Neural Network**: Processes input data through a single hidden layer to generate output.
- **Backpropagation Training**: Learns by adjusting weights and biases based on error.
- **Visualization**: Displays nodes, connections, and weight strengths in real-time.

## Prerequisites

To run this project, you need the following:

- [LÖVE 2D framework](https://love2d.org/) (version 11.3 or later)
- Lua (built-in with LÖVE 2D)

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. **Run the project**:
   Open a terminal in the project directory and type:
   ```bash
   love .
   ```

This will open the LÖVE 2D window, displaying the neural network.

## Customization

- **Modify the Network Structure**: You can change the number of input, hidden, and output nodes by editing the variables in the `love.load()` function.
- **Training the Network**: Use the `train` function to teach the network with data by adjusting weights to reduce error over time.

## How it Works

- **Feedforward Process**: Inputs are passed through the network, multiplied by weights, added to biases, and processed by an activation function.
- **Backpropagation**: The network adjusts its weights based on the error between its prediction and the target output.

## License

This project is open-source and available under the MIT License.

---

Feel free to explore the code, experiment with different node structures, and tweak the training parameters!
