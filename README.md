# CNN Demo

This repository provides a simple demonstration of a Convolutional Neural Network (CNN) applied to the MNIST dataset.

## Contents

- **Notebook Demo**  
A Jupyter Notebook demonstrating the CNN implementation and its performance on the MNIST dataset.  
[Open in Google Colab](https://colab.research.google.com/drive/1oYbRdkrgTVKkwxGL3Lxye31pO0UfBh-9)  
*Source file: `Pytorch MNIST.ipynb`*


- **Pre-trained Model**  
  `cnn.pth` — This file contains the saved parameters of a pre-trained CNN model.

- **Linear Regression Example**  
  A notebook that walks through a synthetic example of linear regression using polynomial features. It demonstrates model selection, training using Ordinary Least Squares (OLS), and performance visualization.  
  *Source file: `Notebook_Reg.ipynb`*

- **Simple Neural Network Example**  
  A basic feedforward neural network implementation using PyTorch. This notebook illustrates how a neural network can approximate a nonlinear function, showing the difference between linear models and deep learning methods.  
  *Source file: `Notebook_DL.ipynb`*

## Notes

- The MNIST dataset is used for handwritten digit classification.
- The pre-trained model (`cnn.pth`) can be loaded to skip training and directly evaluate performance.
- If MNIST data is not available in your Google Colab environment, please run the **second code block** in the notebook to download the dataset before proceeding.
