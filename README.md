# House Price Prediction with PyTorch

This repository contains a Python project using PyTorch to build and train a machine learning model that predicts house prices based on various features such as location, size, number of rooms, and other housing attributes.

## Project Overview

The objective of this project is to create a neural network model to predict house prices, making use of PyTorch as the deep learning framework. This project demonstrates the full pipeline from data preprocessing, model building, training, and evaluation.

## Key Features

- Uses PyTorch to build a regression model for predicting house prices.
- Implements a feedforward neural network for regression.
- Preprocessing of the dataset to handle missing values, normalization, and feature selection.
- Tracks model performance using loss metrics and visualizes the loss curve over time.
- Provides insights into model evaluation through Mean Squared Error (MSE) and other regression metrics.

## Dataset

The dataset used in this project includes various features related to houses, such as:

- **Square footage** of the house
- **Number of bedrooms and bathrooms**
- **Location** of the house
- **Age of the house**
- And other relevant housing features

## Installation

To run this project, ensure you have the following installed:

- Python 3.x
- PyTorch
- Matplotlib
- Pandas
- Scikit-learn

You can install the dependencies using the following command:

```bash
pip install torch matplotlib pandas scikit-learn
