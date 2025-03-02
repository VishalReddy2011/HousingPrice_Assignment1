# Assignment 1: House Price Prediction using PyTorch

This notebook trains a regression model using PyTorch to predict house prices based on features like square footage, number of bedrooms, and location. It uses the California Housing dataset from sklearn.datasets. The data is preprocessed by normalising the features and splitting it into training and testing sets.

The model is a simple feedforward neural network with linear layers and ReLU activation. It is trained using Mean Squared Error (MSE) loss and the Adam optimiser. After training, the model's performance is evaluated using MSE on the test set. The notebook visualises the results using a scatter plot.
