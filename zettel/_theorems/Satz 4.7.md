Sei $n \in \mathbb{N}$, $(X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\forall i \in \{ 1, \dots, n \} : X_i \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \text{E}[X_i] \lt \infty$

Es gilt

$$
	E\left[ \prod_{i=1}^n X_i \right] = \prod_{i=1}^n \text{E}[X_i]
$$

---

Sei $n \in \mathbb{N}$, $(X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\forall i \in \{ 1, \dots, n \} : \text{E}[X_i^2] \lt \infty$

Es gilt

$$
	\text{Var}\left( \sum_{i=1}^n X_i \right) = \sum_{i=1}^n \text{Var}[X_i]
$$