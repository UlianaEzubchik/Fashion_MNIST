# Fashion MNIST Neural Network Classifier
This project trains a neural network to classify images of clothing items from the Fashion MNIST dataset using TensorFlow and Keras.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Dataset](#dataset)
- [Contact](#contact)
  
## Description

The project consists of the following steps:

1. **Data Loading**: Load the Fashion MNIST dataset using TensorFlow's built-in dataset module.

2. **Data Preprocessing**: Normalize pixel values of images to a range of [0, 1].

3. **Model Building**: Define a neural network architecture using Keras Sequential API with layers of dense neurons.

4. **Model Compilation**: Compile the model with appropriate loss function, optimizer, and metrics for training.

5. **Model Training**: Train the model on the training data for a specified number of epochs.

6. **Model Evaluation**: Evaluate the trained model's performance on the test data to measure accuracy and loss.

7. **Prediction**: Make predictions on new data samples using the trained model.

## Requirements

To run this project, you'll need the following dependencies:

- [Python 3.x](https://www.python.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
  
You can install the required Python packages using pip:
```
pip install tensorflow numpy matplotlib
```
## Dataset
[Fashion MNIST dataset](https://keras.io/api/datasets/fashion_mnist/)

This is a dataset of 60,000 28x28 grayscale images of 10 fashion categories, along with a test set of 10,000 images. This dataset can be used as a drop-in replacement for MNIST.

The classes are:
| Label | Description    |
|-------|----------------|
| 0     | T-shirt/top    |
| 1     | Trouser        |
| 2     | Pullover       |
| 3     | Dress          |
| 4     | Coat           |
| 5     | Sandal         |
| 6     | Shirt          |
| 7     | Sneaker        |
| 8     | Bag            |
| 9     | Ankle boot     |


## Contact
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ulyana-yezubchyk/)](https://www.linkedin.com/in/ulyana-yezubchyk/)
[![Email](https://img.shields.io/badge/Email-ulyaa.071@gmail.com-green.svg)](mailto:your_email@example.com)

[![Back to Top](https://img.shields.io/badge/-Back_to_Top-blue?style=flat-square)](#Fashion-MNIST-Neural-Network-Classifier)
