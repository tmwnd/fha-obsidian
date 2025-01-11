Sei $(X_t)_{t \in \mathbb{N}}$ ein [[zettel/Random Walk|Random Walk]] von $(\varepsilon_t)_{t \in \mathbb{N}} \sim \text{IID}(0, \sigma ^2)$.

Die [[zettel/ACVF|ACVF]] ist gegeben durch

$$
	\forall t, h \in \mathbb{N} : \gamma(t+h, t) = \text{Cov}\left[ \sum_{i=1}^{t+h} \varepsilon_i, \sum_{i=1}^t \varepsilon_i \right] = \sum_{i_1=1}^{t+h} \sum_{i_2=1}^t \text{Cov}[\varepsilon_{t_1}, \varepsilon_{t_2}] = \sum_{i=1}^t \text{Cov}[\varepsilon_i, \varepsilon_i] = t \cdot \sigma^2
$$