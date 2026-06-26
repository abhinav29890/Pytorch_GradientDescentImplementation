# Gradient Descent Implementation in PyTorch

This repository contains a simple PyTorch implementation of batch gradient descent for predicting employee bonuses using a small employee dataset.

## Project Overview

The notebook `gd_implementation.ipynb` uses gradient descent to learn the parameters of a linear regression model for the formula:

bonus = w1 * performance + w2 * years_of_experience + w3 * projects_completed + b

The model is trained on the `bonus_dataset.csv` file using mean squared error (MSE) loss.

## Files

- `gd_implementation.ipynb` - Jupyter notebook with the PyTorch gradient descent implementation
- `bonus_dataset.csv` - Employee bonus dataset used for training
- `data_generation.ipynb` - Additional notebook included in the workspace (not part of the gradient descent implementation)

## Dataset

The dataset contains the following columns:

- `employee_id`
- `performance`
- `years_of_experience`
- `projects_completed`
- `bonus`

## Requirements

- Python 3.8+ recommended
- PyTorch
- pandas
- matplotlib

## How to Run

1. Install dependencies:

```bash
pip install torch pandas matplotlib
```

2. Open `gd_implementation.ipynb` in Jupyter Notebook or JupyterLab.

3. Run the notebook cells in order.

## What the Notebook Does

- Loads `bonus_dataset.csv` with pandas
- Converts feature columns and target values to PyTorch tensors
- Initializes weights and bias randomly
- Uses a training loop for batch gradient descent
- Computes predicted bonus and MSE loss
- Performs backpropagation and updates parameters
- Prints the learned weights and bias after training

## Notes

- The notebook uses a fixed learning rate of `0.006` and `5000` training epochs.
- The final cell demonstrates predicting a bonus value using the learned weights.

## License

This repository is provided for educational purposes.
"# Pytorch_GradientDescentImplementation" 
