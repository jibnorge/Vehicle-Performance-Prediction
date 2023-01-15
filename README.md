# Linear_Regression_SGD
Vehicle Performance prediction using Linear regression SGD method

## Problem Statement
Analyse the different factors affecting the mileage of a vehicle and train a model using these features.

## SGD
Stochastic gradient descent (SGD) is an optimization algorithm that can be used to find the best-fitting line for linear regression. The algorithm starts with an initial set of parameters for the line (such as the slope and y-intercept) and then iteratively updates them based on the negative gradient of the loss function with respect to the parameters. The vanilla stochastic gradient descent (SGD) updates weights by subtracting the current weight by a factor (i.e. α, the learning rate) of its gradient. The loss function measures the difference between the predicted values (based on the current parameter values) and the actual values.

$$
{w}_{t+1} ={w}_{t} +\alpha \frac{\partial L}{\partial {w}_{t}}
$$

where, <br><p style="margin-left:2.5em">w<sub>t+1</sub> : new weight</p> 
<p style="margin-left:2.5em">w<sub>t</sub> : current weight </p><p style="margin-left:2.5em"><h style = "font-family:Noto Sans Math">L</h> : loss function</p>