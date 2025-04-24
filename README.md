# Rui Classifier

A deep learning project for binary image classification that detects whether an image contains Rui or not. Built from scratch using NumPy and trained on a custom dataset (rui_dataset).

## Features
- Implements a 4-layer fully connected neural network: (Linear -> RELU)*3 -> Linear -> Sigmoid
- Takes input of images of shape (256, 256, 3) and flattens into a vector of size 196608
- Predicts binary labels (1: Rui, 0: Not Rui)
- Trained using gradient descent and backpropagation
- Uses a custom HDF5 dataset (rui_dataset.h5) for training/testing

## How to Use
- Upload your image to the `images/` folder
- Run the notebook to predict if the image is Rui or not

## Acknowledgements
This project is inspired by the Deep Learning Specialization on Coursera, taught by Andrew Ng and the team at deeplearning.ai. Parts of the architecture and implementation are adapted from course assignments for educational purposes.
