# Gradient-Decsent
Gradient Descent for Adaline - Linear Regression
Using gradient descent, as well as using library functions (scikit-learn library) to solve a simple linear regression problem: y=ax+b.

The aim is to get acquainted with the Scikit-Learn library and Python and also get familiar with the behavior of gradient descent solutions.

You will observe that the first two methods provide the same solution (intercept & coefficient), up to rounding errors. Indeed, the solution is unique, except when there are more features than data points, in which case there will be more than one solution. With the closed form solution, there are no free-parameter to tune, which is a big advantage.

Gradient descent, on the other hand, has many applications, so even though it may not be the preferred method for linear regression, it is very much of interest in general. However, gradient descent method heavily depends on finding a good range for the learning rate; otherwise it may diverge (nan due to over/underflow). Also finding a good learning rate for weights in different scale can be a bit difficult. Software libraries have normalization to adjust for scale differences between different input/weight scales.
