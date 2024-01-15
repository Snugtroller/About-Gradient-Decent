# About-Gradient-Decent
This python program helps to minimize the cost function in this model during the training process. The primary goal is to find the optimal parameters (weights and biases) that minimize the error between the predicted and actual values.
This program helps to understand gradient decent better on how it works.

To make it easier-
- We first import the packages and then import the dataset which is in the form of csv.
- We then seprate the two columns and store it X and y variable corresponding with its axis.
- We then scatter the points in the graph.
- We then use linear regression to find the target intercept and the slope of the line.
- We start with the intercept at 0 (the blue line) and the target intercept is (the red line).
- In other words our starting point is the blue line and we have to move to the red line to make a perfect model with the least errors.
- We use the cost function formula with the gradient decent formula and move the line upwards, hence we form a new line with an intercept more than the previous intercept which was 0.
- We slowly go upwards step by step with the help of learning rate (the new line formed is the green line).
- Now to make it easier we used a for loop and mentioned within how many iteration we will get the targeted line.
- And hence we find the accuracy score to show how accurate our model was.
