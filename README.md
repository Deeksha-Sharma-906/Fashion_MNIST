# Fashion_MNIST
Fashion MNIST Classification with Neural Networks

# Fashion MNIST Classification Model

This repository contains my first AI/deep learning project using **TensorFlow** and **Keras** to classify images from the **Fashion MNIST dataset**.  
The dataset consists of **70,000 grayscale images** (28×28 pixels) across **10 categories** including T-shirts, trousers, pullovers, coats, sandals, shirts, sneakers, bags, and ankle boots.

## Project Highlights
- **Data preprocessing:** normalization and one-hot encoding of labels
- **Visualization:** class-wise sample images and distribution plots
- **Neural Network Architecture:**
  - Input layer (28×28) → Flatten
  - Two hidden dense layers with ReLU activation
  - Output layer with Softmax activation for 10 classes
- **Model training:** experimented with varying hyperparameters (epochs, batch size, learning rate)
- **Evaluation:** training/validation accuracy & loss plots, confusion matrix
