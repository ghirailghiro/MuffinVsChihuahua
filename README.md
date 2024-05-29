# MuffinVsChihuahua

submitted by Michele Ghirardelli

Department of Computer Science "Giovanni Degli Antoni" - University of Milan

## Introduction to the Project
The project aim to classify a dataset composed of photos of muffins and chihuahuas using Convolutional Neural Network.

## Objective of the project
- Experiment with different network architectures (at least 3) and training hyperparameters.
- Use 5-fold cross validation to compute your risk estimates.
- Documenting the influence of the choice of the network architecture and the tuning of the hyperparameters on the final cross-validated risk estimate.

## Project Constraints
Images must be transformed from JPG to RGB (or grayscale) pixel values and scaled down. While the training loss can be chosen freely, the reported cross-validated estimates must be computed according to the zero-one loss.

## Configuration and code
All the experiments will be run on Google Colab and the code can be found
in the file called ”Experiments.ipynb”.
To start the project upload to drive (using this path: /content/drive/MyDrive/Statistical Method/) the dataset downloaded from [kaggle](https://www.kaggle.com/datasets/samuelcortinhas/muffin-vs-chihuahua-image-classification) zipped with the name archive.zip. In the last section of the notebook, inside the section ”Plotting Train Loss”, plots use .json files as data sources, to replicate the plots the results need to be saved as a .json file for each architecture.
