Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]].

Der *$k$-fache Differenzoperator* $\nabla^k : \mathcal{L}(\Omega, \mathcal{A}, P) \to \mathcal{L}(\Omega, \mathcal{A}, P)$ ist definiert als

$$
	\forall k \in \mathbb{N}, t \in \mathbb{Z} : \nabla^k X_t := \nabla(\nabla^{k-1} X_t) = X_t + \sum_{i=1}^k (-1)^i \cdot \binom{k}{i} \cdot B^i(X_t)
$$