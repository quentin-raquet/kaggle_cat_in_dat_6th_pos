# Categorical Feature Encoding Challenge II

This repository contains the code for the 6th place solution in the [Categorical Feature Encoding Challenge II](https://www.kaggle.com/c/cat-in-the-dat-ii) Kaggle competition.

## Project Overview

The goal of this competition is to predict the probability of a binary target column.
The data contains binary features, ordinal features, and nominal features which may have string or numeric values.

## Repository Structure

- `deepfm-model.ipynb`: This notebook contains the implementation of the DeepFM model used in the solution.
- `autoencoder.ipynb`: This notebook contains the implementation of the autoencoder used for feature extraction.
- `test_preprocessing_cross_val.ipynb`: This notebook contains the preprocessing and cross-validation steps.

## Results

Our solution achieved the 6th position on the leaderboard under the team name "Patetqueraq".

## Usage

1. Run `test_preprocessing_cross_val.ipynb` for preprocessing and cross-validation.
2. Run `autoencoder.ipynb` to train the autoencoder and extract features.
3. Run `deepfm-model.ipynb` to train the DeepFM model and make predictions.

## Dependencies

- Python 3
- TensorFlow
- Keras
- scikit-learn
- pandas
- numpy
