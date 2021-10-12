
# Cost Function

We can measure the accuracy of our hypothesis function by using a cost function. This takes an average difference (actually a fancier version of an average) of all the results of the hypothesis with inputs from x's and the actual output y's.

<!-- $
J(\theta_0, \theta_1) = \dfrac {1}{2m} \displaystyle \sum _{i=1}^m \left ( \hat{y}_{i}- y_{i} \right)^2 = \dfrac {1}{2m} \displaystyle \sum _{i=1}^m \left (h_\theta (x_{i}) - y_{i} \right)^2 
$ --> <img style="transform: translateY(0.1em); background: white;" src="https://render.githubusercontent.com/render/math?math=J(%5Ctheta_0%2C%20%5Ctheta_1)%20%3D%20%5Cdfrac%20%7B1%7D%7B2m%7D%20%5Cdisplaystyle%20%5Csum%20_%7Bi%3D1%7D%5Em%20%5Cleft%20(%20%5Chat%7By%7D_%7Bi%7D-%20y_%7Bi%7D%20%5Cright)%5E2%20%3D%20%5Cdfrac%20%7B1%7D%7B2m%7D%20%5Cdisplaystyle%20%5Csum%20_%7Bi%3D1%7D%5Em%20%5Cleft%20(h_%5Ctheta%20(x_%7Bi%7D)%20-%20y_%7Bi%7D%20%5Cright)%5E2">

This function is otherwise called the "`Squared error function`", or "`Mean squared error`". The mean is halved 1/2 as a convenience for the computation of the gradient descent, as the derivative term of the square function will cancel out the 1/2 term. The following image summarizes what the cost function does:

![cost function](./img/cost%20function.png)
