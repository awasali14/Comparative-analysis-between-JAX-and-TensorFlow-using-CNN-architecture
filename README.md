# Comparative-analysis-between-JAX-and-TensorFlow-using-CNN-architecture


## Project Overview

This project undertakes a comparative analysis of neural network performance between JAX and TensorFlow frameworks using the Fashion MNIST dataset. The core objective was to benchmark the training speed and efficiency of identically structured Convolutional Neural Networks (CNNs) implemented in both frameworks, thereby highlighting JAX's capabilities in optimizing computation time without sacrificing accuracy.

## Motivation & Purpose

In the pursuit of more efficient computational frameworks for deep learning, this study provides empirical evidence on the performance gains achievable with JAX over traditional TensorFlow. This project addresses the crucial need for faster training times in machine learning operations, particularly beneficial for environments where rapid model training is critical.

## Neural Network Architecture

Both frameworks utilized an identical CNN architecture to ensure a fair and accurate comparison of performance metrics. The CNN model consisted of the following layers:
- Two convolutional layers with 32 and 64 filters respectively, each followed by a ReLU activation function and a max-pooling layer.
- A flattening layer to reshape the data for the dense layer.
- Two dense layers, the first with 128 neurons and ReLU activation, and the second serving as the output layer with 10 neurons corresponding to the number of classes in the Fashion MNIST dataset.

This uniform architecture across both JAX and TensorFlow implementations ensures that any differences in performance are attributed solely to the frameworks' processing capabilities and not to variations in model design.

## What was learned?

Through rigorous testing, it was observed that JAX significantly outperforms TensorFlow in terms of training speed, achieving a 7x faster performance on the same hardware setup. Both implementations maintained a comparable accuracy rate of approximately 91%, demonstrating that JAX's accelerated computations do not compromise the model's effectiveness.

## Results

- **Training Time Reduction**: JAX model training was 7 times faster compared to TensorFlow.
- **Consistent Accuracy**: Both frameworks achieved around 91% accuracy, confirming model consistency across different platforms.
- **Efficient Processing**: Demonstrated JAX's ability to handle dataset normalization, batching, and model training more efficiently.

### Performance Metrics

- **Number of training examples**: 60,000
- **Number of test examples**: 10,000
- **Epoch Details**: 10 epochs, showing progressive decrease in loss and consistent accuracy.
- **Test Accuracy Achieved**: 91.74% with JAX vs. 91.85% with TensorFlow.

