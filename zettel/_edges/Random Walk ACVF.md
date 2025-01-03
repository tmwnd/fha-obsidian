Sei $(X_t)_{t \in \mathbb{N}} = \left( \sum_{i=1}^t \epsilon_t \right)_{t \in \mathbb{N}}$ ein [[zettel/Random Walk|Random Walk]].

Die [[zettel/Autokovarianzfunktion (ACVF)|ACVF]] ist gegeben durch

$$
	\forall t, h \in \mathbb{N} : \gamma(t+h, t) = \text{Cov}\left[ \sum_{i=1}^{t+h} \epsilon_i, \sum_{i=1}^t \epsilon_i \right] = \sum_{i_1=1}^{t+h} \sum_{i_2=1}^t \text{Cov}[\epsilon_{t_1}, \epsilon_{t_2}] = \sum_{i=1}^t \text{Cov}[\epsilon_i, \epsilon_i] = t \cdot \sigma^2
$$