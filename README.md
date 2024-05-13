# House Price Prediction with Neural Networks

## Overview
This project aims to predict the price of a house based on the number of bedrooms using a simple neural network model. The relationship between the number of bedrooms and the house price follows a linear pattern, with each additional bedroom adding a fixed amount to the base price.

## Dataset
The dataset consists of pairs of input-output values, where the input represents the number of bedrooms and the output represents the corresponding house price. The dataset covers houses with 1 up to 6 bedrooms.

## Neural Network Model
The neural network model is designed with one input neuron and one output neuron. It utilizes a dense layer with linear activation to learn the relationship between the number of bedrooms and the house price. Two different optimizers were experimented with during training:

1. Adam Optimizer:
   - Prediction for a 7-bedroom house: 4.8 (scaled down)
   
2. Stochastic Gradient Descent (SGD) Optimizer:
   - Prediction for a 7-bedroom house: 4.0 (scaled down)

## Training
The model was trained for 1000 epochs using the input-output pairs from the dataset. The Mean Squared Error loss function was used to evaluate the model's performance during training.

## Usage
To use the trained model for house price prediction:
1. Clone this repository to your local machine.
2. Run the provided Python script to train the model and make predictions.
3. Experiment with different optimizers and hyperparameters to optimize the model's performance further.
