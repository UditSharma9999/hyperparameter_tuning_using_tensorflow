# hyperparameter tuning

This code file contains the basic technique of hyperparameter tuning  using tensorflw and Keras Tuner

## Overview
The Keras Tuner is a library that helps you pick the optimal set of hyperparameters for your TensorFlow program. The process of selecting the right set of hyperparameters for your machine learning (ML) application is called hyperparameter tuning or hypertuning.

Hyperparameters are the variables that govern the training process and the topology of an ML model. These variables remain constant over the training process and directly impact the performance of your ML program. Hyperparameters are of two types:

- Model hyperparameters which influence model selection such as the number and width of hidden layers
- Algorithm hyperparameters which influence the speed and quality of the learning algorithm such as the learning rate for Stochastic Gradient Descent (SGD) and the number of nearest neighbors for a k Nearest Neighbors (KNN) classifier.

***

## Setup
```
!pip install -q -U keras-tuner
```
