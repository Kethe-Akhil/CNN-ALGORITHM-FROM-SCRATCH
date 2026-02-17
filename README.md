# CNN-ALGORITHM-FROM-SCRATCH
This project is my implementation of a Convolutional Neural Network (CNN) completely from scratch using NumPy.
No TensorFlow. No PyTorch. No high-level deep learning libraries.
#The main goal of implementing :
Understand what is actually happening inside a CNN — forward pass, backward pass, kernel updates, padding, flipping, everything
I used the Digits dataset (handwritten digits 0–9).
For importing of data i used the tensorflow 
NumPy → All mathematical operations (core CNN logic)
Pandas → Data handling and preprocessing
PIL (Python Imaging Library) → Image handling
# Convolution Layer
Multi-channel convolution
Multiple kernels
Manual sliding window logic
Bias handling
# Activation
ReLU (implemented manually)
ReLU derivative for backpropagation
# Backpropagation
Kernel gradient calculation
Input gradient calculation
Padding logic
Kernel flipping for proper gradient flow
Channel-wise gradient accumulation
Dense Layer
Flatten operation
Fully connected layer
Softmax output
Cross-entropy loss
Gradient updates
