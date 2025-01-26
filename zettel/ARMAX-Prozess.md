Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]] (Kovariate), $(Y_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ von $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(p, q)$, $\beta \in \mathbb{R}$ mit

$$
	\forall t \in \mathbb{Z} : Y_t = \varepsilon_t + \beta X_t + \sum_{i=1}^p \phi_i B^i(Y_t) + \sum_{i=1}^q \vartheta_i B^i(\varepsilon_t)
$$

$(Y_t)_{t \in \mathbb{Z}}$ heißt *Autoregressiver Moving Average Prozess mit einer Exogenen Variable (ARMAX-Prozess) der Ordnungen $p$ und $q$*.

Es gilt

- $(X_t)_{t \in \mathbb{Z}}$ ist ein Spezialfall eines [[zettel/Transfer-Function-Model|Transfer-Function-Models]]

und

$$
	\forall t \in \mathbb{Z} : Y_t = \varepsilon_t + \beta \sum_{i \in \mathbb{N}} \psi_i B^i(X_t) + \sum_{i \in \mathbb{N}} \psi_i B^i\left( \sum_{j \in \mathbb{N}} \theta_j B^j(\varepsilon_t) \right)
$$

mit
- $\psi$ der Inverse von $\phi$
- $\theta$ der Inverse von $\vartheta$

falls $(X_t)_{t \in \mathbb{Z}}$ [[zettel/ARMA-Prozess/Invertierbarkeit|invertierbar]] ist