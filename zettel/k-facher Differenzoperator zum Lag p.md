Sei $(X_t)_{t \in \mathbb{Z}}$ ein [[zettel/Additives Zerlegungsmodell mit saisonaler Komponente|Additives Zerlegungsmodell mit saisonaler Komponente]] mit Periodenlänge $p$.

Der *$k$-fache Differenzoperator zum Lag $p$* ist definiert als

$$
	\forall k \in \mathbb{N}, t \in \mathbb{Z} : \nabla_p^k X_t := \nabla_p(\nabla_p^{k-1} X_t) = X_t + \sum_{i=1}^k (-1)^i \cdot \binom{k}{i} \cdot B^{i \cdot p}(X_t)
$$