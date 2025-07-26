# Concrete-Strength-Regression

A machine learning project using neural networks (Keras with TensorFlow backend) to predict the compressive strength of concrete based on its ingredients.

## Dataset
- *Features:*
  - Cement
  - Blast Furnace Slag
  - Fly Ash
  - Water
  - Superplasticizer
  - Coarse Aggregate
  - Fine Aggregate
  - Age
- *Target:*
  - Concrete Compressive Strength

## Model
- 3 hidden layers with ReLU activation
- Output layer with 1 neuron for regression
- Optimizer: Adam
- Loss: Mean Squared Error

## Results
- MSE on test set: ~33.37
- Loss curve shows good convergence

## Files
- concrete_data.csv: dataset used
- concrete-strength-regression.ipynb: all code and training process
