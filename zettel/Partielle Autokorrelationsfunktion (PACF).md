Sei $(X_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]].

Die *partielle Autokorrelationsfunktion (PACF)* $\tau : \mathbb{Z} \to [0, 1]$ für $(X_t)_{t \in \mathbb{Z}}$ ist definiert als

$$
	\forall h \in \mathbb{Z} : \tau(h) := \text{Corr}[X_{h+1} - P_{\text{span}(1, X_2, \dots, X_h)}(X_{h+1}), X_1 - P_{\text{span}(1, X_2, \dots, X_h)}(X_1)]
$$