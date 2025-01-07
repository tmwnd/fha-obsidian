Sei $(X_t)_{t \in \{ 1, \dots, n \}}$ eine [[zettel/Zeitreihe|Zeitreihe]] miit
- $\forall k \in \{ 1, \dots, n-1 \} : \hat{\mu}_1(k) := \frac{1}{k} \sum_{t=1}^k X_t$
- $\forall k \in \{ 1, \dots, n-1 \} : \hat{\mu}_2(k) := \frac{1}{n-k} \sum_{t=k+1}^n X_t$

Die *maximale Differenz* ist definiert als

$$
	T_n^{(1)} := \max \{ |\hat{\mu}_1(k) - \hat{\mu}_2(k)| \mid k \in \{ 1, \dots, n-1 \} \}
$$

Die *CUSUM-Statistik* ist definiert als

$$
	T_n^{(2)} := \max \left\{ \left| \frac{k(n-k)}{n^2} (\hat{\mu}_1(k) - \hat{\mu}_2(k)) \right| \mid k \in \{ 1, \dots, n-1 \} \right\} = \max \left\{ \left| \frac{1}{n} \sum_{t=1}^k X_t - \frac{k}{n^2} \sum_{t=1}^n X_t \right| \mid k \in \{ 1, \dots, n-1 \} \right\}
$$
