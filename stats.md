

## [Covariance Matrix](https://en.wikipedia.org/wiki/Covariance_matrix)
If the entries in the column vector $\bold{X}=\left( X_1, X_2, ..., X_n \right)^T$ are random variable, each with finite variance and expected value, then the covariance matrix $\Sigma$ is the matrix whose $(i,j)$ entry is the covariance 
$$\mathrm{K}_{X_{i} X_{j}}=\operatorname{cov}\left[X_{i}, X_{j}\right]=\mathrm{E}\left[\left(X_{i}-\mathrm{E}\left[X_{i}\right]\right)\left(X_{j}-\mathrm{E}\left[X_{j}\right]\right)\right]$$
It's equivalent to the matrix equality 
$$\mathrm{K}_{\mathrm{XX}}=\operatorname{cov}[\mathbf{X}, \mathbf{X}]=\mathrm{E}\left[\left(\mathbf{X}-\mu_{\mathbf{X}}\right)\left(\mathbf{X}-\mu_{\mathbf{X}}\right)^{\mathrm{T}}\right]=\mathrm{E}\left[\mathbf{X} \mathbf{X}^{T}\right]-\mu_{\mathbf{X}} \mu \mathbf{x}^{T}$$


Example (1): $h_\theta(x) = \Large\frac{1}{1 + \mathcal{e}^{(-\theta^\top x)}}$ ; 
example (2): $a^2 + b^2 = c^2$ ; 
example (3): $\sum_{i=1}^m y^{(i)}$