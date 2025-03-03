Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{AR}(p)$ von $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{IID}(0, \sigma^2)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]], $\hat{\sigma^2}, \hat{\phi}$ die [[zettel/Yule-Walker-Schätzer|Yule-Walker-Schätzer]] von $\sigma^2, \phi$.

Es gilt

$$
	\hat{\sigma}^2 \overset{P}{\longrightarrow} \sigma^2
$$

und

$$
	\sqrt{n}(\hat{\phi} - \phi) \overset{V}{\longrightarrow} \mathcal{N}(0, \sigma^2\Gamma_p^{-1})
$$