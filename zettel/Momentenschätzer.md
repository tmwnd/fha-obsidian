Seien $X = (X_i)_{i \in \{ 1, \dots, n \}}$ unter jedem $P_\vartheta \in \mathcal{P}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte reelle [[zettel/Zufallsvariable|Zufallsvariablen]], $\Theta \subseteq \mathbb{R}^k$ mit
- $\forall \vartheta \in \Theta : \text{E}_\vartheta[|X_1|^k] \lt \infty$
- $\forall \vartheta \in \Theta, j \in \{ 1, \dots, k \} : \text{E}_\vartheta[|X_1|^j] \lt \infty$

und

$$
	\forall j \in \{ 1, \dots k \} : \overline{X_n^j} = \frac{1}{n} \sum_{i=1}^k X_i^j
$$

Es gilt
- $\forall j \in \{ 1, \dots, k \} : \overline{X_n^j}$ ist ein erwartungstreuer [[zettel/Schätzer|Schätzer]] für $\mu_j(\vartheta) = \text{E}_\vartheta[X_1^j]$

Sei $\mathcal{M} := \{ (\mu_j(\vartheta))_{j \in \{ 1, \dots, k \}} \mid \vartheta \in \Theta \} \subseteq \mathbb{R}^k$ offen, $g : \mathcal{M} \to \mathbb{R}^k$ stetig mit
- $\forall \vartheta \in \Theta : \vartheta = g((\mu_j(\vartheta))_{j \in \{ 1, \dots, k \}})$

Der *Momentenschätzer* für $\vartheta$ ist definiert als

$$
	g((\overline{X_n^j})_{j \in \{ 1, \dots k \}})
$$

---

Seien $X = (X_i)_{i \in \{ 1, \dots, n \}}$ unter jedem $P_\vartheta \in \mathcal{P}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte reelle [[zettel/Zufallsvariable|Zufallsvariablen]], $\Theta \subseteq \mathbb{R}^k$ mit
- $\forall \vartheta \in \Theta : \text{E}_\vartheta[|X_1|^k] \lt \infty$
- $\forall \vartheta \in \Theta, j \in \{ 1, \dots, k \} : \text{E}_\vartheta[|X_1|^j] \lt \infty$

und

$$
	\forall j \in \{ 1, \dots k \} : \overline{X_n^j} = \frac{1}{n} \sum_{i=1}^k X_i^j
$$

Der *Momentenschätzer* $\text{Mo}_n$ für $\vartheta$ ist definiert als

$$
	\text{Mo}_n := \text{mo}((\overline{X_n^j})_{j \in \{ 1, \dots k \}})
$$

Es gilt
- $\forall \vartheta \in \Theta : P_\vartheta(\lim_{n \to \infty} (\overline{X_n^j})_{j \in \{ 1, \dots, k \}} = (\mu_j(\vartheta))_{j \in \{ 1, \dots k \}}) = 1$
- $\forall \vartheta \in \Theta : P_\vartheta(\lim_{n \to \infty} \text{Mo}_n = \vartheta) = 1$
- $\text{Mo}_n \to \vartheta$ $P_\vartheta$-f. s.
- $\text{Mo}_n \overset{P_\vartheta}{\longrightarrow} \vartheta$

und

$$
	\forall \vartheta \in \Theta : \lim_{n \to \infty} P_\vartheta((\overline{X_n^j})_{j \in \{ 1, \dots k \}} \in \mathcal{M}) = 1
$$