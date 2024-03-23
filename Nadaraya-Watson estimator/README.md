# Target
We are going to construct and
plot the Nadaraya-Watson estimator using the bandwidths $h=0.5, 2.5, 5, 10$. The analysis has been done in R programming languge. 
We have also explored the shape of density functions based on LOESS method.


# Nadaraya-Watson Regression Estimation

In the context of estimating the regression function $E(Y_i | X_i = x) = m(x)$ for a set of iid pairs of random variables $(X_1, Y_1), \ldots, (X_n, Y_n)$, Nadaraya-Watson regression is employed. The estimator for $m(x)$, denoted as $\hat{m}_n(x)$, is given by:


$\hat{f}(x) = \frac{\displaystyle\sum_{i=1}^{n} K\left(\frac{x - X_i}{h}\right)Y_i}{\displaystyle\sum_{i=1}^{n} K\left(\frac{x - X_i}{h}\right)}$


Here, $K$ is the kernel function, and $h$ is the bandwidth.



## Usage

# LOESS (Smoothing data using local regression)
https://towardsdatascience.com/loess-373d43b03564





# Congress Demographics 

This directory contains various demographic data about the United States Senate and House of Representatives over time. It’s been used in the following FiveThirtyEight articles: 

- [Congress Today Is Older Than It’s Ever Been](https://fivethirtyeight.com/features/aging-congress-boomers/), by Geoffrey Skelley (April 3, 2023)

`was the first Congress in which all senators had been directly elected, rather than elected by state legislatures, following the [ratification of the 17th Amendment in 1913](https://constitutioncenter.org/the-constitution/amendments/amendment-xvii). 

| Header | Description | Source(s) | 
| ----- | ------------ | ------ |
| `congress` | The number of the Congress that this member’s row refers to. For example, `118` indicates the member served in the 118th Congress (2023-2025). | [Biographical Directory of the United States Congress](https://bioguide.congress.gov/); [VoteView.com](https://voteview.com/) | 
| `start_date` | First day of a Congress. For the 66th Congress to the 73rd Congress, this was March 4. With the [ratification of the 20th Amendment](https://constitutioncenter.org/the-constitution/amendments/amendment-xx), Congress’s start date shifted to Jan. 3 for the 74th Congress to present. | U.S. House of Representatives | 
| `chamber` | The chamber a member of Congress sat in: `Senate` or `House`. Any member who served in both chambers in the same Congress — e.g., a sitting representative who was later appointed to the Senate — was assigned to the chamber in which they cast more votes. | [Biographical Directory of the United States Congress](https://bioguide.congress.gov/); [VoteView.com](https://voteview.com/) | 
