Seien $X = (X_\nu)_{\nu \in \{ 1, \dots, n \}}$ unter jedem $P_\vartheta \in \mathcal{P}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] und identisch verteilte reelle [[zettel/Zufallsvariable|Zufallsvariablen]], $\Theta \subseteq \mathbb{R}^k$, $\Sigma_\vartheta := \text{Cov}\left[ (X_1^j)_{j \in \{ 1, \dots, k \}}^T \right]$ mit
- $\forall \vartheta \in \Theta : \text{E}_\vartheta[|X_1|^k] \lt \infty$
- $\forall \vartheta \in \Theta, j \in \{ 1, \dots, k \} : \text{E}_\vartheta[|X_1|^j] \lt \infty$

Es gilt

$$
	\sqrt{n}\left( (\overline{X_n^j})_{j \in \{ 1, \dots, k \}} - (\mu_j(\vartheta))_{j \in \{ 1, \dots, k \}} \right) \overset{V}{\longrightarrow} \mathcal{N}_k(0, \Sigma_\vartheta)
$$

und

$$
	\sqrt{n}(\text{Mo}_n - \vartheta) \overset{V}{\longrightarrow} \mathcal{N}_k(0, J_\vartheta\Sigma_\vartheta J_\vartheta^\top)
$$