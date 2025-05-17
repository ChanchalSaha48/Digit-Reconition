# Digit-Reconition
Simple Convolutional Neural Network (CNN) implemented in TensorFlow/Keras for classifying handwritten digits from the MNIST dataset.


## Project Overview

The model consists of two convolutional layers followed by max pooling, a flattening layer, and two fully connected (dense) layers. It is designed to recognize digits (0-9) from grayscale images of size 28x28 pixels.

---

## Features

- Uses the MNIST dataset of handwritten digits.
- Applies image normalization and one-hot encoding for labels.
- Trains for 10 epochs with a batch size of 64.
- Achieves good accuracy(98.93%)  on test data.

---

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy (usually comes with TensorFlow)
  
You can install TensorFlow using:

```bash
pip install tensorflow
