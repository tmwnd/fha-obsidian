Seien $(X_i)_{i \in \mathbb{N}}$ nicht-[[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]], $\mu := \text{E}[X_1]$, $\sigma^2 := \text{Var}[X_1]$ mit
- $\forall i \in \{ 1, \dots, n \} : \text{E}[X_i] = \mu$
- $\forall i \in \{ 1, \dots, n \} : \text{Var}[X_i] = \sigma^2$

und $(S_n)_{n \in \mathbb{N}}$ definiert als

$$
	\forall n \in \mathbb{N} : S_n := \sum_{i=1}^n X_i
$$

Es gilt
- $\forall n \in \mathbb{N} : \text{E}[S_n] = n\mu$

und

$$
	\forall n \in \mathbb{N} : \text{Var}[S_n] = \sum_{h=-n+1}^{n-1} (n - |h|) \gamma(h)
$$

und

$$
	\frac{1}{n} S_n \to \tilde{\sigma}^2
$$