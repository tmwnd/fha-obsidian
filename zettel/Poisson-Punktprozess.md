Seien $(T_n)_{n \in \mathbb{N}} \sim \text{Exp}(\lambda)$ [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\forall n \in \mathbb{N} : \tau_n = \sum_{j=1}^n T_j$

Der zugehörige *Poisson-Punktprozess* $(N_t)_{t \in \mathbb{N}}$ mit Intensität $\lambda$ ist definiert als

$$
	\forall t \in \mathbb{N} : N_t := \sup \{ n \mid \tau_n \le t \}
$$

Es gilt
- $\forall t \in \mathbb{N}, k \in \{ 0, \dots, t \} : P(N_t = k) = e^{-\lambda t}\frac{(\lambda t)^k}{k!}$
- $\forall t, s, u \in \mathbb{N}, s \le t : N_{t + u} \sim \mathcal{P}(\lambda)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]] $N_s$