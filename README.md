# Logistic Regression with a Neural Network mindset

This is a programming assignment for the "Neural Networks and Deep Learning" course on Coursera. The goal of this assignment is to implement logistic regression with a neural network mindset to recognize cats.
Problem Statement

You are given a dataset of images of _cats and non-cats_. Your task is to build a simple image-recognition algorithm that can correctly classify pictures as cat or non-cat.

## Dataset

The dataset is provided as a h5 file, which contains:

    a training set of m_train images labeled as cat (y=1) or non-cat (y=0)
    a test set of m_test images labeled as cat or non-cat
    each image is of shape (num_px, num_px, 3) where 3 is for the 3 channels (RGB).
    
    
## Program

In this program, we have implemented a logistic regression algorithm with a neural network mindset. The program has the following functions:

    sigmoid: Compute the sigmoid of a scalar or a numpy array of any size.
    initialize_with_zeros: This function creates a vector of zeros of shape (num_px * num_px * 3, 1) for w and initializes b to 0.
    propagate: Implement the cost function and its gradient for the propagation explained above.
    optimize: This function optimizes w and b by running a gradient descent algorithm.
    predict: Predict whether the label is 0 or 1 using learned logistic regression parameters (w, b).
    model: Builds the logistic regression model by calling the functions implemented above. It initializes the parameters, optimizes them using gradient descent, and returns the learned parameters. It also prints the train/test accuracy.

The model function is the main function that calls all the other functions and uses them to implement logistic regression.


## Conclusion

This program is an implementation of logistic regression with a neural network mindset. The program can recognize cats with an accuracy of around 70% on the test set. The accuracy can be improved by using a more complex model like a deep neural network.
