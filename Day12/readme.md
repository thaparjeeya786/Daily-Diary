# Artificial Intelligence & Machine Learning Training Report - Day 12
**Name:** Jeeya Thapar  
**URN:** 2303002  
**Date:** 8 July 2025  

## Overview
In today’s session, I learned about the working of neural networks, which are the backbone of many AI systems. The focus was on understanding the structure of neural networks, how data passes through layers during forward propagation, and how learning happens using backward propagation (backpropagation). The session explained how models adjust their weights and biases based on errors to improve accuracy over time.

## Learning Objectives
- Understand the basic structure of a neural network.  
- Learn how forward propagation processes input through layers.  
- Understand how backpropagation adjusts weights to improve learning.  
- Explore the roles of loss functions and gradients in model optimization.  

## Neural Networks
A **neural network** is made of layers of nodes (neurons) that mimic the human brain.  
- **Input Layer** → Where data enters.  
- **Hidden Layers** → Process and transform data.  
- **Output Layer** → Produces the final prediction.  

Each connection has a weight, and each neuron applies an activation function to decide what to pass forward.

## Forward Propagation
- Definition: The process of passing input data through the network to make a prediction.  
- **Weights & Biases:**  
  - Weights determine importance of inputs.  
  - *Bias* shifts the activation function to improve learning flexibility.  
- Linear Transformation: \( z = (weights \times inputs) + bias \)  
- Layers: Input → Hidden → Output  

## Backward Propagation
Backward Propagation (Backpropagation) is used to train neural networks by reducing prediction errors.  

- Computes gradients of the loss function using the chain rule.  
- Updates weights and biases to minimize errors.  
- Scales well for deep networks with multiple hidden layers.  
- Automates the learning process by continuously optimizing the model.  

## Conclusion
Today, it gave me a clear understanding of how neural networks learn and improve.  
- **Forward propagation** showed how inputs move through layers to make predictions.  
- **Backward propagation** explained how models correct their errors by adjusting weights.  
