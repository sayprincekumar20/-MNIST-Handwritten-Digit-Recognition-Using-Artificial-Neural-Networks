# MNIST Handwritten Digit Recognition Using Artificial Neural Networks

## Project Overview

This project involves developing an Artificial Neural Network (ANN) to classify handwritten digits using the MNIST dataset. The MNIST dataset comprises 70,000 grayscale images of handwritten digits (0-9), each sized at 28x28 pixels. The dataset is divided into 60,000 training images and 10,000 testing images. The primary objective is to build a neural network model that can accurately predict the digit represented in each image.

## Key Features

- **Data Preprocessing**: Normalized pixel values to the range [0, 1] to enhance model performance.

- **Model Architecture**:
  - **Input Layer**: Flattened the 28x28 pixel images into a 784-element vector.
  - **Hidden Layers**:
    - First Hidden Layer: 128 neurons with ReLU activation.
    - Second Hidden Layer: 32 neurons with ReLU activation.
  - **Output Layer**: 10 neurons with softmax activation for multi-class classification.

- **Compilation**: Used `sparse_categorical_crossentropy` as the loss function and the `Adam` optimizer.

- **Training**: Trained the model over 25 epochs with a validation split of 20% to monitor performance on unseen data.

- **Evaluation**: Achieved an accuracy of approximately 97% on the test dataset.

## Visualizations

The project includes plots to visualize the training and validation loss, as well as accuracy metrics over the epochs, providing insights into the model's learning process.

## Code Implementation

The project is implemented in Python using TensorFlow and Keras libraries. The complete code is available in the repository.

## Conclusion

This project demonstrates the effectiveness of Artificial Neural Networks in image classification tasks, specifically in recognizing handwritten digits. The achieved accuracy underscores the model's proficiency in generalizing to new, unseen data.


