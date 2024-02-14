# Target
We are going to construct and
plot the Nadaraya-Watson estimator using the bandwidths h=0.5, 2.5, 5, 10. The analysis has been done in R programming languge. 

# Nadaraya-Watson Regression Estimation

In the context of estimating the regression function $E(Y_i | X_i = x) = m(x)$ for a set of iid pairs of random variables $(X_1, Y_1), \ldots, (X_n, Y_n)$, Nadaraya-Watson regression is employed. The estimator for $m(x)$, denoted as $\hat{m}_n(x)$, is given by:


$\hat{f}(x) = \frac{\displaystyle\sum_{i=1}^{n} K\left(\frac{x - X_i}{h}\right)Y_i}{\displaystyle\sum_{i=1}^{n} K\left(\frac{x - X_i}{h}\right)}$


Here, $K$ is the kernel function, and $h$ is the bandwidth.



## Usage

[//]: # (Provide examples or instructions on how to use your project. This could include code snippets, screenshots, or even a link to a live demo.)

