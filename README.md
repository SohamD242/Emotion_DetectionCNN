# Emotion Detection with CNN, Data Augmentation, VGG16, and ResNet

This Jupyter Notebook explores emotion detection using various Convolutional Neural Network (CNN) techniques, focusing on improving accuracy through custom CNNs, data augmentation, and transfer learning.

## Approach
- **Custom CNN**: The initial model was built using normalization, max-pooling, and ReLU activation functions, achieving 56% accuracy due to imbalanced data.
- **Data Augmentation**: To address the data imbalance, I applied techniques like rotation, flip, and zoom, leading to more diverse training data.
- **Transfer Learning with VGG16**: Implemented transfer learning by fine-tuning a VGG16-based model, resulting in significant performance improvements.
- **ResNet for Optimal Accuracy**: Ultimately, I used the ResNet architecture, achieving a remarkable 92% accuracy for emotion detection.

## What's Inside
- Code for building and training a custom CNN, with detailed explanations of layers and functions used.
- Implementation of data augmentation strategies to boost model robustness.
- Steps to fine-tune a VGG16, ResNet model and evaluate its performance.
- Instructions for using the ResNet model to achieve high accuracy.

## How to Use
1. Clone or download the repository.
2. Install the necessary dependencies.
3. Follow the step-by-step instructions in the Jupyter Notebook to build, train, and evaluate the models.
4. Observe the differences in accuracy across the custom CNN, VGG16, and ResNet models.

## Requirements
- Python 3.10
- Jupyter Notebook
- Deep learning libraries like TensorFlow, Keras
- Data visualization libraries such as Matplotlib, Computer Vision

## Screenshots

![Example-1](path/to/custom_cnn_training_screenshot.png)


![Example-2](path/to/resnet_model_performance_screenshot.png)


