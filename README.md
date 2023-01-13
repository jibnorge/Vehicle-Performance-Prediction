# Linear_Regression_SGD
Vehicle Performance prediction using Linear regression SGD method

## Problem Statement
Analyse the different factors affecting the mileage of a vehicle and train a model using these features.

## SGD
Stochastic gradient descent (SGD) is an optimization algorithm that can be used to find the best-fitting line for linear regression. The algorithm starts with an initial set of parameters for the line (such as the slope and y-intercept) and then iteratively updates them based on the negative gradient of the loss function with respect to the parameters. The loss function measures the difference between the predicted values (based on the current parameter values) and the actual values.

In each iteration of SGD, the algorithm uses a small subset of the data (called a "batch") to estimate the gradient and update the parameters. This process is repeated until the parameters converge to a set of values that minimize the loss function.

So, in short, SGD Linear Regression is a method to find the best fit line to the data which minimizes the difference between predicted and actual values by iteratively updating parameters through the use of a subset of data, which is known as batches.
