<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Math Equations</title>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>
<body>
  
  <!-- Your LaTeX math equations here -->
  <div>
    \(\hat{m}_n(x) = \frac{\sum_{i=1}^{n} K\left(\frac{X_i - x}{h}\right)Y_i}{\sum_{i=1}^{n} K\left(\frac{X_i - x}{h}\right)}\)
  </div>

</body>
</html>

# [Project Name]
We are going to construct and
plot the Nadaraya-Watson estimator using the bandwidths h=0.5, 2.5, 5, 10. The analysis has been done in R programming languge. 

# Nadaraya-Watson Regression Estimation

In the context of estimating the regression function \(E(Y_i | X_i = x) = m(x)\) for a set of IID pairs of random variables \((X_1, Y_1), \ldots, (X_n, Y_n)\), Nadaraya-Watson regression is employed. The estimator for \(m(x)\), denoted as \(\hat{m}_n(x)\), is given by:

\[
\hat{m}_n(x) = \frac{\sum_{i=1}^{n} K\left(\frac{X_i - x}{h}\right)Y_i}{\sum_{i=1}^{n} K\left(\frac{X_i - x}{h}\right)}
\]

Here, \(K\) is the kernel function, and \(h\) is the bandwidth.



## Usage

[//]: # (Provide examples or instructions on how to use your project. This could include code snippets, screenshots, or even a link to a live demo.)

