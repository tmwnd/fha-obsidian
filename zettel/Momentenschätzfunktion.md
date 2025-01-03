Seien $X = (X_i)_{i \in \{ 1, \dots, n \}}$ unter jedem $P_\vartheta \in \mathcal{P}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte reelle [[zettel/Zufallsvariable|Zufallsvariablen]], $\Theta \subseteq \mathbb{R}^k$, $\vartheta_0 \in \Theta$ fest mit
- $\forall \vartheta \in \Theta : \text{E}_\vartheta[|X_1|^k] \lt \infty$
- $\forall \vartheta \in \Theta, j \in \{ 1, \dots, k \} : \text{E}_\vartheta[|X_1|^j] \lt \infty$

und

$$
	\forall j \in \{ 1, \dots k \} : \overline{X_n^j} = \frac{1}{n} \sum_{i=1}^k X_i^j
$$

und
- $\forall j \in \{ 1, \dots, k \} : \overline{X_n^j}$ ist ein erwartungstreuer [[zettel/Schätzer|Schätzer]] für $\mu_j(\vartheta) = \text{E}_\vartheta[X_1^j]$

Sei $\mathcal{M} := \{ (\mu_j(\vartheta))_{j \in \{ 1, \dots, k \}} \mid \vartheta \in \Theta \} \subseteq \mathbb{R}^k$ offen, $g : \mathcal{M} \to \mathbb{R}^k$ stetig mit
- $\forall \vartheta \in \Theta : \vartheta = g((\mu_j(\vartheta))_{j \in \{ 1, \dots, k \}})$

Die *Momentenschätzfunktion* $\text{mo} : \mathbb{R}^k \to \mathbb{R}^k$ ist definiert als

$$
	\text{mo}(t) := \begin{cases}
		g(t) & t \in \mathcal{M} \\
		\vartheta_0 & t \notin \mathcal{M}
	\end{cases}
$$