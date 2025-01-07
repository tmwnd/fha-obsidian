Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $(m_n)_{n \in \mathbb{N}} \in \mathbb{Z}$ proportional zu $(n^\frac{1}{3})_{n \in \mathbb{N}}$.

Der [[zettel/Schätzer|Schätzer]] $(\hat{\sigma}_n^2)_{n \in \mathbb{N}}$ von $\tilde{\sigma}^2$ ist definiert als

$$
	\forall n \in \mathbb{N} : \hat{\sigma}_n^2 = \frac{1}{\lfloor \frac{n}{m_n} \rfloor - 1} \sum_{s=1}^{\lfloor \frac{n}{m_n} \rfloor - 1} \frac{\left( \sum_{t=(s-1)m_n + 1}^{sm_n} X_t - \sum_{t=sm_n+1}^{(s+1)m_n} X_t \right)^2}{2m_n}
$$

Unter bestimmten Bedingungen gilt

$$
	\hat{\sigma}^2 \to \tilde{\sigma}^2
$$