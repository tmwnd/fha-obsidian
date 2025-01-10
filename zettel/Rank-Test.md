Sei $(X_t)_{t \in \{ 1, \dots, n \}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $\text{H} : (X_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2), \text{K} : (X_t)_{t \in \mathbb{Z}} \not\sim \text{WN}(0, \sigma^2)$ mit

$$
	P := \sum_{i, j \in \mathbb{Z}, i \lt j} \mathbb{1}(X_i \lt X_j)
$$

Es gilt
- $\text{E}[P] = \frac{1}{4}n(n-1)$
- $\text{Var}[P] = \frac{1}{72}n(n-1)(2n+5)$
- $n$ genügend groß $\implies$ $P \overset{V}{\approx} \mathcal{N}(\text{E}[P], \text{Var}[P])$

und
- $P(X_i \lt X_j) = \frac{1}{2}$, falls $\text{H}$ gültig ist

Verwerfe $\text{H}$, falls

$$
	\frac{|P - \text{E}[P]|}{\sqrt{\text{Var}[P]}} \gt \Psi_{1-\frac{\alpha}{2}}
$$