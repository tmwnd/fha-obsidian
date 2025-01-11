Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{AR}(p)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]].

Der *Yule-Walker-Schätzer* ist über die [[zettel/Yule-Walker-Gleichungen|Yule-Walker-Gleichungen]] definiert als

$$
	\hat{\sigma}^2 := \hat{\gamma}(0) - \sum_{i=1}^p \phi_i \hat{\gamma}(i)
$$

und

$$
	\hat{\phi} := \hat{\Gamma}_p^{-1}\hat{\gamma}(p )
$$