# linear-regression
Demonstration of gradient descent algorithm on Linear Regression model containing one feature and one target.

Three techniques for linear regression
We can fit a model to our data:
1. By using sklearn
2. By using Mathematical Formula
3. By using Gradient Descent

All of them give same cost/accuracy

How they work

1. sklearn implements a high level optimization code for optimizing the cost function.
   It's a readymade resource tool and only few lines of code can do the job.
   
2. Mathematical formula gives exact values of its underlying parameters which make up the equation of regression line.
   Equation of regression line y = mx + c (slope-intercept form).
   We can directly find out m and c by using formulaes (m = slope, c = y intercept)
                           m = Σ(x-x̅)(y-y̅) ∕ Σ(x-x̅)²
                                  c = y̅ - mx̅
   
3. By using Gradient Descent: Gradient Descent is an optimizing algorithm. Initially we put random m and c.
    Goal is to minimize the cost function C = (1/m) × Σ(y-y_pred)²
    Requires a learning rate and number of iterations.

   We can construct a line on initial parameters and follow the steps:
   
   a. Compute the cost function.
   
   b. Apply GD and find optimal m and c.
   
   c. Repeat steps a & b until we get a constant minimum value of cost function.
   
Datasets used: www.superdatascience.com/pages/training from Machine Learning AZ course 
