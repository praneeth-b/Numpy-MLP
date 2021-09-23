# Numpy-MLP

A complete Numpy based implementation of the Multi Layered Perceptron. 

- Dense layers implemented in numpy and are configurable by the user.
- ReLU, sigmoid and softmax activation functions implemented.
- MSE and cross-entropy loss functions.
- Stochastic Gradient descent optimizer 
- Configurable parameters such as batch-size and Learning rate

**Gradients are computed using Algorithmic Differentiation**

**Experiment:**

This framework is tested on the MNIST digits dataset by passing the flattened images as inputs to the MLP.
Data augmentation is performed on the images before training.(optional parameter).
Augmentation is performed by generating 4 images for every training image where each image is displaced by 2 pixels in all four directions.

**Results**
- A test accuracy of over 98% for experiments without data augmentation.
- Accuracy increases to over 99% for experiments with data augmentation.


The mnist_evaluation.ipynb can be used to load pretrained weights onto the MLP model and evaluate the performance on a test set.
