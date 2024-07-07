Sei $(X_i)_{i \in \{ 1, \dots, d \}} \sim \mathcal{N}(0, \Sigma)$, $X = \sum_{i=1}^d X_i \sim \mathcal{N}(0, \sigma^2)$, $\gamma \in \mathbb{R}$.

Es gilt

$$
	\text{VaR}_\gamma(X) = \sigma\Phi^{-1}(\gamma) = \sqrt{\sum_{i=1}^d \text{VaR}_\gamma(X_i)^2 + \sum_{i \ne j} \rho_{i, j} \text{VaR}_\gamma(X_i) \text{VaR}_\gamma(X_j)}
$$