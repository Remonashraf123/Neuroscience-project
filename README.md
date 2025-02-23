# Neural Network with Tanh Activation

## Overview
This project implements a simple **neural network** with one hidden layer using **Tanh activation function**. The network consists of:
- **Input Layer**: 2 neurons
- **Hidden Layer**: 2 neurons
- **Output Layer**: 1 neuron

It initializes random weights, performs forward propagation, computes the final output, and calculates the error between the predicted and target values.

## Features
- Uses **Tanh Activation Function**.
- Random **weight initialization**.
- Computes **Mean Squared Error (MSE)**.
- Visualizes the **Tanh function** using `matplotlib`.

## Dependencies
Make sure you have Python and the following libraries installed:
```bash
pip install numpy matplotlib
```

## How It Works
1. Initializes weights randomly within the range (-0.5, 0.5).
2. Computes activations for the hidden and output layers using **tanh**.
3. Computes error using **Mean Squared Error (MSE)** formula.
4. Plots the Tanh activation function for visualization.

## Code Structure
- **tanh_activation(x)**: Computes the Tanh activation.
- **initialize_weights(shape)**: Initializes random weights.
- **compute_error(target, output)**: Computes the error.
- Forward pass:
  - Computes hidden layer activations.
  - Computes final output.
- Prints results and plots the **Tanh Activation Function**.

## Usage
Run the script using:
```bash
python filename.py
```
Replace `filename.py` with your actual file name.

## Example Output
```
Hidden Layer Input: [ 0.2 -0.1]
Hidden Layer Output: [ 0.197 -0.099]
Output Layer Input: [0.45]
Final Output: [0.42]
Error: [0.0035]
```

## Visualization
The script generates a plot of the **Tanh Activation Function** to illustrate its shape and properties.

## License
This project is open-source. Feel free to modify and use it for educational purposes.

