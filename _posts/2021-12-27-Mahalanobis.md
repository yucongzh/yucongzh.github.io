## Mahalanobis Distance

> Mahalanobis distance is an effective multivariate distance metric that measures the distance between a point (vector) and a distribution.

$$
D^{2}=(x-m)^{T} \cdot C^{-1} \cdot(x-m)
$$
where, 
- $D^2$ is the square of the Mahalanobis distance
- $x$ is the vector of the observation (row in a dataset)
- $m$ is the vector of mean values of independent variables (mean of each column)
- $C^{-1}$ is the inverse covariance matrix of independent variables