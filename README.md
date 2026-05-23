# Automating Neural Network Architecture with Keras Tuner

## Project Overview
This repository contains a Jupyter Notebook designed to demonstrate how to effectively use Keras Tuner for hyperparameter optimization in Deep Learning. The primary goal of this project is learning the core mechanics of automating architecture selection rather than achieving maximum model accuracy. Therefore, standard data preprocessing steps were intentionally omitted to focus strictly on the tuning workflow.

## The Dataset
We utilize the Diabetes dataset for a binary classification task. The objective is to predict the onset of diabetes based on raw medical diagnostic measurements.

## Key Concepts Covered
* Implementing Keras Tuner within a standard TensorFlow workflow.
* Defining a dynamic search space using hyperparameter objects.
* Automating the selection of hidden layers, neuron counts, and activation functions.
* Understanding the fundamental differences between search trials and training epochs.
* Extracting and interpreting the final best model architecture.

## Setup Instructions
Follow these steps to run the notebook locally:
1. Clone this repository to your local machine.
2. Ensure you have Python installed.
3. Install the required libraries via your terminal or command prompt: `pandas`, `numpy`, `scikit_learn`, `tensorflow`, and `keras_tuner`.
4. Open the Jupyter Notebook and execute the cells sequentially.

## Future Improvements
To achieve significantly higher accuracy on this dataset, you can fork this project and implement the following:
* Data standardization using Scikit Learn preprocessing tools.
* Advanced search algorithms like Hyperband or Bayesian Optimization.
* Expanded search spaces allowing for more layers and longer training epochs.

## Author
Developed and maintained by Paxton.