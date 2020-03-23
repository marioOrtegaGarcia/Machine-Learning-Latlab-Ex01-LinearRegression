# Linear Regression & Gradient Descent Algorithm
Linear Regression and Gradient Descent Algorithms are implemented for single and multiple variables. Using linear regression to approximate the profit a food truck will make based on the city's population.

## Cost Function
The cost function allows us to test the accuracy of our hypothesis by taking calculating the mean squared error or our hypothesis.  
Our main goal in Linear Regression is to minimize the value of our cost function.  
<img src = "https://latex.codecogs.com/gif.latex?\inline&space;J(\theta)=&space;\frac{1}{2m}&space;\sum_{i=1}^{m}(h_{\theta}(x^{(i)}-y^{(i)}))^{2}" name="Cost Function"/>

### Hypothesis
Our hypothesis is our predicted function that will approximate our data.  
<img src = "https://latex.codecogs.com/gif.latex?\inline&space;h_{\theta}(x)&space;=&space;\Theta^{T}x&space;=&space;\theta_0&space;&plus;&space;\theta_1x_1" name="Hypothesis"/>

## Batch Gradient Descent
Gradient descent allows us to estimate the parameters in our hypothesis function. This is done by taking the derivative of the cost function (gives us tangent line) which returns a direction to move down the cost function.   
<img src = "https://latex.codecogs.com/gif.latex?\inline&space;\theta_{0}:=\theta_0-\alpha\frac{1}{m}\sum_{i=1}^{m}(h_{\theta}(x^{(i)}-y^{(i)}))\\&space;\theta_{j}:=\theta_{j}-\alpha\frac{1}{m}\sum_{i=1}^{m}(h_{\theta}(x^{(i)}-y^{(i)}))x_{j}^{(i)}" name="Batch Gradient Descent"/>

<!-- Pass through LaTeX code as an image from codecogs -->
<!-- <img src = ""/> -->
