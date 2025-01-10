Sei $(X_t)_{t \in \{ 1, \dots, n \}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $k^* \in \{ 1, \dots, n \}$, $\mu_1, \mu_2 \in \mathbb{R}$ mit

$$
	\forall t \in \{ 1, \dots, n \} : X_t := \mu_1 \cdot \mathbb{1}(t \le k^*) + \mu_2 \cdot \mathbb{1}(1 \gt k^*)
$$

und
- $\text{H} : \mu_1 = \mu_2, \text{K} : \mu_1 \ne \mu_2$
- $\hat{\sigma}$ ein [[zettel/Schätzer|Schätzer]] für $\tilde{\sigma}$
- $q_\alpha$ das $\alpha$-[[zettel/Quantil|Quantil]] von $\max \{ B(u) - uB(1) \mid u \in [0, 1] \}$

Es gilt

$$
	\max \left\{ \left| \frac{1}{\sqrt{n}} \sum_{t=1}^k (X_t - \text{E}[X_t]) - \frac{k}{n}\frac{1}{\sqrt{n}} \sum_{k=1}^n (X_t - \text{E}[X_t]) \right| \mid k \in \{ 1, \dots, n-1 \} \right\} \overset{V}{\longrightarrow} \max \{ \tilde{\sigma}|B(u) - uB(1)| \mid u \in [0, 1] \}
$$

und
- $\forall k \in \{ 1, \ldots, n \} : \sum_{t=1}^k \text{E}[X_t] - \frac{k}{n} \sum_{i=1}^n \text{E}[X_t] = 0$ bzw. $\sqrt{n}T_n^{(2)} \overset{V}{\longrightarrow} \hat{\sigma}q_{1-\alpha}$, falls $\text{H}$ gültig ist
- $\sum_{t=1}^{k^*} \text{E}[X_t] - \frac{k^*}{n} \sum_{t=1}^n \text{E}[X_t] = \frac{(n-k^*)k^*}{n} (\mu_1 - \mu_2)$ bzw. $\sqrt{n}T_n^{(2)} \overset{V}{\longrightarrow} \infty$, falls $\text{K}$ gültig ist

Verwerfe $\text{H}$, falls

$$
	\sqrt{n}T_n^{(2)} \gt \hat{\sigma}q_{1-\alpha}
$$

Die [[zettel/_examples/CUSUM-Statistik|CUSUM-Statistik]] ist ein [[zettel/Statistischer Test|statistischer Test]] zum Testniveau $\alpha$ mit
- $\lim_{n \to \infty} P(\text{Verwerfe } \text{H} \mid \text{H}) = \alpha$
- $\lim_{n \to \infty} P(\text{Verwerfe } \text{H} \mid \text{K}) = 1$