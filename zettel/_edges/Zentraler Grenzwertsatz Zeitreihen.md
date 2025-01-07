Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]] mit
- $\tilde{\sigma}^2 \gt 0$
- $\alpha(k) \lt \infty$
- $\forall t \in \mathbb{Z} \ \exists \delta \in \mathbb{R}^+ : \text{E}[X_t^{4+\delta}] \lt \infty$

Falls $\exists C \in \mathbb{R}^+, a \in (0, 1) \ \forall t \in \mathbb{Z} : \alpha(k) \le Ca^k$ gilt

$$
	\sqrt{n} \frac{\frac{1}{n} \sum_{s=1}^n X_s - \mu}{\tilde{\sigma}^2} \overset{V}{\longrightarrow} \mathcal{N}(0, 1)
$$