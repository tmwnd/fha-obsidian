Seien $(X_t)_{t \in \mathbb{Z}}, (Y_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ [[zettel/Zeitreihe|Zeitreihen]].

Die *Kreuzkorrelationsfunktion (CCF)* $\rho_{X, Y} : \mathbb{Z}^2 \to \mathbb{R}$ für $(X_t)_{t \in \mathbb{Z}}$ und $(Y_t)_{t \in \mathbb{Z}}$ ist definiert als

$$
	\forall t, s \in \mathbb{Z} : \rho_{X, Y}(t, s) := \frac{\gamma_{X, Y}(t, s)}{\sqrt{\gamma_{X, X}(t, t) \cdot \gamma_{Y, Y}(s, s)}}
$$