Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{AR}(p)$ zu $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{IID}(0, \sigma^2)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]], $\hat{\sigma^2}, \hat{\phi}$ die [[zettel/Yule-Walker-Schätzer|Yule-Walker-Schätzer]] von $\phi, \sigma^2$.

Es gilt

$$
	\sqrt{n}(\hat{\phi} - \phi) \overset{V}{\longrightarrow} \mathcal{N}(0, \sigma^2\Gamma_p^{-1})
$$

und

$$
	\hat{\sigma}^2 \overset{P}{\longrightarrow} \sigma^2
$$