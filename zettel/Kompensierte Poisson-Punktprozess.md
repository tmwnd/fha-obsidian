Sei $(N_t)_{t \in \mathbb{N}}$ ein [[zettel/Poisson-Punktprozess|Poisson-Punktprozess]] mit Intensität $\lambda$.

Der *kompensierte Poisson-Punktprozess* $(M_t)_{t \in \mathbb{N}}$ ist definiert als

$$
	\forall t \in \mathbb{N} : M_t = N_t - \lambda t
$$

Es gilt
- $\forall t \in \mathbb{N} : M_t$ ist ein [[zettel/Martingal|Martingal]]
- $\forall t \in \mathbb{N} : \text{E}[N_t] = \lambda t$