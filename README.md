# Logistic-Regression-From-Scratch
A Logistic Regression model for multiple independent variable based predictions using Python (Google Colab)
# Logistic Regression Implementation
This repository contains a Python implementation of logistic regression using a custom class LOR. Logistic regression is a fundamental machine learning algorithm used for binary classification tasks.
# Class Methods
__init__(self, learning_rate, epoch)
# Parameters:
learning_rate: The learning rate for gradient descent.
epoch: The number of iterations for training.
train(self, X, y)
# Train the logistic regression model.
# Parameters:
X: Input features.
y: Target labels.
predict(self, X)
# Predict labels for new data. Parameters:
X: Input features.
# Returns:
Predicted labels.
plot(self, X_test, y_pred)
# Plot a scatter plot of the predicted classes.
Parameters:
X_test: Features for plotting.
y_pred: Predicted labels.
# Loss Function
The logistic regression model uses binary cross-entropy loss as its loss function. This function is implemented in the method loss_function.
