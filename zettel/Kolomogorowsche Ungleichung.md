Sei $k, n \in \mathbb{N}$, $k \le n$, $(X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\forall i \in \{ 1, \dots, n \} : \text{E}[X_i] = 0$
- $\forall i \in \{ 1, \dots, n \} : \text{E}[X_i^2] \lt \infty$
- $S_k = \sum_{i = 1}^k X_i$

Es gilt

$$
	\forall \varepsilon \gt 0 : P\left( \max_{1 \le k \le n} |S_k| \gt \varepsilon \right) \le \frac{1}{\varepsilon^2} \sum_{i=1}^n \text{Var}[X_i]
$$