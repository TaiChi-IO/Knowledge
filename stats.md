
## Covariance
For two jointly distributed real-valued random variables $X$ and $Y$ with finite second moments, the covariance is defined as the expected value (or mean) of the product of their deviations from their individual expected values:

$$ \begin{aligned}
\operatorname{cov}(X, Y) &=\mathrm{E}[(X-\mathrm{E}[X])(Y-\mathrm{E}[Y])] \\
&=\mathrm{E}[X Y-X \mathrm{E}[Y]-\mathrm{E}[X] Y+\mathrm{E}[X] \mathrm{E}[Y]] \\
&=\mathrm{E}[X Y]-\mathrm{E}[X] \mathrm{E}[Y]-\mathrm{E}[X] \mathrm{E}[Y]+\mathrm{E}[X] \mathrm{E}[Y] \\
&=\mathrm{E}[X Y]-\mathrm{E}[X] \mathrm{E}[Y]
\end{aligned} $$

## Correlation
The most familiar measure of dependence between two quantities is the Pearson product-moment correlation coefficient (PPMCC), or "Pearson's correlation coefficient", commonly called simply "the correlation coefficient":

$$ \begin{aligned}
\rho_{X, Y} &= \operatorname{corr}(X, Y) = \frac{\operatorname{cov}(X, Y)}{\sigma_{X} \sigma_{Y}} \\
&=\frac{\mathrm{E}\left[\left(X-\mu_{X}\right)\left(Y-\mu_{Y}\right)\right]}{\sigma_{X} \sigma_{Y}} \\
&=\frac{\mathrm{E}(X Y)-\mathrm{E}(X) \mathrm{E}(Y)}{\sqrt{\mathrm{E}\left(X^{2}\right)-\mathrm{E}(X)^{2}} \cdot \sqrt{\mathrm{E}\left(Y^{2}\right)-\mathrm{E}(Y)^{2}}} 
\end{aligned} $$

## [Covariance Matrix](https://en.wikipedia.org/wiki/Covariance_matrix)
If the entries in the column vector $X=\left( X_1, X_2, ..., X_n \right)^T$ are random variable, each with finite variance and expected value, then the covariance matrix $\Sigma$ is the matrix whose $(i,j)$ entry is the covariance  

$$ \mathrm{K}_{X_{i} X_{j}}=\operatorname{cov}\left[X_{i}, X_{j}\right]=\mathrm{E}\left[\left(X_{i}-\mathrm{E}\left[X_{i}\right]\right)\left(X_{j}-\mathrm{E}\left[X_{j}\right]\right)\right] $$  

It's equivalent to the matrix equality  

$$\mathrm{K}_{\mathrm{XX}}=\operatorname{cov}[\mathbf{X}, \mathbf{X}]=\mathrm{E}\left[\left(\mathbf{X}-\mu_{\mathbf{X}}\right)\left(\mathbf{X}-\mu_{\mathbf{X}}\right)^{\mathrm{T}}\right]=\mathrm{E}\left[\mathbf{X} \mathbf{X}^{T}\right]-\mu_{\mathbf{X}} \mu \mathbf{x}^{T}$$  

Example (1): $h_\theta(x) = \Large\frac{1}{1 + \mathcal{e}^{(-\theta^\top x)}}$ ;  
example (2): $a^2 + b^2 = c^2$ ;  
example (3): $\sum_{i=1}^m y^{(i)}$  