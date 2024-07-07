Seien $(\mathcal{F}_t)_{t \in T}$ [[zettel/Filtration|Filtrationen]], $d \in \mathbb{N}$, $\left( S_t^{(0)} \right)_{t \in T}$ risikolose Assets, $\left( S_t^{(i)} \right)_{t \in T, s \in \{1, \dots d \}}$ risikobehaftete Assets auf $\Omega$, $(Q_t)_{t \in T}$ Martingalmaße auf $(\Omega, \mathcal{F}_t)_{t \in T}$ mit
- $\forall t \in T, s \in \{ 1, \dots, d \} : S_t^{(i)}$ [[zettel/_edges/Adaption Stochastischer Prozess Filtration|adaptiert]] $\mathcal{F}_t$

und den Martingalen unter $Q$

$$
	\forall t \in T, i \in \{ 1, \dots, d \} : \tilde{S}_t^{(i)} = \frac{S_t^{(i)}}{S_t^{(0)}}
$$

Es gilt die *risikoneutrale Bewertungsformel*

$$
	\forall s, t \in T, s \le t, i \in \{ 1, \dots, d \} : \tilde{S}_s^{(i)} = \text{E}_Q\left[ \tilde{S}_t^{(i)} \mid \mathcal{F}_s \right]
$$