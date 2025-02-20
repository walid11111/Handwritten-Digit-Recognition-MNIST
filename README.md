# Handwritten-Digit-Recognition-MNIST

MNIST Dataset Classification

This project demonstrates the classification of handwritten digits from the MNIST dataset using TensorFlow and Keras.

Dataset

The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9), with 60,000 images for training and 10,000 for testing. Each image is 28x28 pixels.

Requirements

Ensure the following dependencies are installed before running the notebook:

pip install tensorflow numpy pandas matplotlib seaborn

Project Workflow

Import Libraries: Load essential libraries for data processing and model building.

Load Data: Download and split the MNIST dataset into training and testing sets.

Data Preprocessing: Normalize pixel values to the range [0, 1] to enhance model performance.

Model Development: Construct a Sequential neural network using Flatten and Dense layers.

Model Training: Train the model using categorical cross-entropy loss and an appropriate optimizer.

Model Evaluation: Assess model performance on the test set and perform manual testing on sample predictions.

Usage

Execute the Jupyter Notebook step by step to train the model and validate its predictions.

Results

The trained model is expected to achieve high accuracy in recognizing handwritten digits, demonstrating the effectiveness of deep learning techniques in image classification.

For further improvements, consider experimenting with different neural network architectures, hyperparameter tuning, or data augmentation techniques.

