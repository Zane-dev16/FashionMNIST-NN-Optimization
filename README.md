# FashionMNIST-NN-Optimization

## Overview

This repository focuses on optimizing the classification of the Fashion MNIST dataset using neural networks. The project involves:

- Creating neural networks using the Keras API in three different ways.
- Tuning hyperparameters with Keras Tuner.
- Analyzing results using TensorBoard.

# Repository Structure
```bash
FashionMNIST-NN-Optimization/
├── notebooks/
│ ├── buiding_NNs.ipynb # Building a NN 3 different ways for customization using Keras Sequential API
│ ├── NN_tuning.ipynb # Hyperparameter tuning with Keras Tuner
├── data/
│ ├── fashion_mnist_data.zip # Dataset
├── models/ # Trained models
├── README.md
├── .gitignore
└── requirements.txt # Required packages and dependencies
```

# Running the Notebooks
1. **Clone the repository**:
  ```bash
  git clone https://github.com/yourusername/FashionMNIST-NN-Optimization.git
  cd FashionMNIST-NN-Optimization
  ```

2. **Open and run the notebooks**:
  Navigate to the notebooks directory and open the desired notebook to run.

## Bibliography

- Aurélien Géron. Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems. 3rd Edition. O'Reilly Media, 2022.
