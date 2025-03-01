# Artificial Neural Network from Scratch

This repository contains an implementation of an Artificial Neural Network (ANN) built entirely from scratch using Python and NumPy. The project is inspired by and based on the concepts and implementation details presented in the article [*Understand and Implement an Artificial Neural Network from Scratch*](https://tinztwinshub.com/data-science/a-beginners-guide-to-developing-an-artificial-neural-network-from-zero/) by Tinz Twins Hub.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Experiments](#experiments)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Overview

This project demonstrates the key concepts behind artificial neural networks including:
- **Perceptron and Feedforward Propagation**
- **Gradient Descent for Error Minimization**
- **Backpropagation to Update Weights**
- **Implementation of ANN with NumPy**

The code includes examples on how to generate a toy dataset, build and train the neural network, evaluate its performance, and experiment with various parameters such as learning rate, the number of hidden nodes, and iterations.

## Features

- **Simple ANN Architecture:** Single hidden layer neural network.
- **Customizable Parameters:** Easily adjust learning rate, iterations, and hidden layer size.
- **Visualization:** Includes plots for training progress and model evaluation.
- **Hands-On Code:** Well-commented code to help you understand each step of the process.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
# Using conda
conda create -n neural-network python=3.9
conda activate neural-network

# Or using virtualenv
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install required packages
pip install numpy matplotlib scikit-learn pandas plotly
(I used jupyter notebook for this)


Acknowledgments
This project is inspired by the comprehensive tutorial provided by Tinz Twins Hub in their article Understand and Implement an Artificial Neural Network from Scratch. Many thanks to the authors at Tinz Twins Hub for their detailed explanation and code examples that made this project possible.

Additional thanks go to the authors of the referenced literature and open-source communities whose tools and frameworks (like NumPy, scikit-learn, matplotlib, and plotly) have been instrumental in developing this project.


