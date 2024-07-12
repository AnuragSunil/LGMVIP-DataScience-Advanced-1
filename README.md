# MNIST Handwritten Digit Classification

## Overview

I have done this project done under Let's Grow More and the aim was to develop a neural network capable of reading handwritten digits using the MNIST Handwritten Digit Classification Challenge. Utilizing TensorFlow and Convolutional Neural Networks (CNN), this project walks through the process of building, training, and evaluating various neural network models. The goal is to compare the performance of different CNN architectures to identify the most effective model for this task.

## Problem Statement

1. **Develop A Neural Network That Can Read Handwriting:**
   - Begin the neural network machine learning project with the MNIST Handwritten Digit Classification Challenge.
   - Use TensorFlow and CNN due to their user-friendly interfaces, ideal for beginners.

## Project Structure

1. **Importing Libraries:**

   - Import necessary libraries such as TensorFlow, Keras, NumPy, Matplotlib, and others.

2. **Loading Dataset:**

   - Load the MNIST dataset which includes 60,000 training images and 10,000 test images of handwritten digits.

3. **Preprocessing:**

   - Reshape the images to fit the input shape required by the neural network.
   - Normalize the pixel values to a range of 0 to 1.
   - Encode the labels using one-hot encoding.

4. **Model Creation and Evaluation:**
   - Create and evaluate three different CNN models: a Simple CNN, a LeNet model, and a Deeper CNN model.
   - For each model:
     - **Model Creation:** Define the architecture of the neural network.
     - **Compiling:** Specify the loss function, optimizer, and metrics.
     - **Fitting:** Train the model using the training data.
     - **Evaluating:** Evaluate the model using the test data.
     - **Predicting:** Use the model to predict handwritten digits on new data.

## Models Performance Comparison

| Model            | Accuracy | Loss  |
| ---------------- | -------- | ----- |
| Simple CNN       | 98.85%   | 0.053 |
| LeNet Model      | 98.99%   | 0.043 |
| Deeper CNN Model | 99.03%   | 0.061 |

## Conclusion

Through this project, I have successfully developed and evaluated multiple CNN models to classify handwritten digits from the MNIST dataset. The results indicate that [Model Name] performed the best in terms of accuracy and loss, making it the most suitable model for this task.

## Acknowledgements

This project was completed as part of the internship program at Let's Grow More. Special thanks to the Let's Grow More team for their guidance and support.

## How to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/AnuragSunil/MNIST_LGM_internship.git
   ```
