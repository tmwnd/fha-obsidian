Sei $n \in \mathbb{N}$ bekannt, $p \in (0, 1)$ mit
- $\vartheta := \log\left( \frac{1}{1-p} \right) \in \mathbb{R}$

Die $\mu := \sum_{k=0}^n \delta_k$-Dichte von $\mathcal{B}(n, p)$ kann geschrieben werden als

$$
	f(x, \vartheta) = \underbrace{(1-p)^n}_{c(\vartheta)} \cdot \underbrace{e^{\log\left( \frac{1}{1-p} \right) \cdot x}}_{e^{\vartheta \cdot T(x)}} \cdot \underbrace{\binom{n}{x}}_{h(x)} \quad x \in \{ 0, \dots, n \}
$$

mit
- $c(\vartheta) := (1-p)^n \quad \vartheta \in \Theta$
- $T(x) := e^{\log\left( \frac{1}{1-p} \right) \cdot x} \quad x \in \{ 0, \dots, n \}$
- $h(x) := \binom{n}{x} \quad x \in \{ 0, \dots, n \}$