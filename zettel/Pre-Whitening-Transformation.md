Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ von $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]] und [[zettel/ARMA-Prozess/Invertierbarkeit|invertierbar]], $(Y_t)_{t \in \mathbb{Z}}$ ein [[zettel/Transfer-Function-Model|Transfer-Function-Model]] von $(X_t)_{t \in \mathbb{Z}}$.

Die *Pre-Whitening-Transformation* $(X_t^*)_{t \in \mathbb{Z}}$ bzw. $(Y_t^*)_{t \in \mathbb{Z}}$ von $(X_t)_{t \in \mathbb{Z}}$ bzw. $(Y_t)_{t \in \mathbb{Z}}$ ist definiert als

$$
	\forall t \in \mathbb{Z} : X_t^* := \sum_{i \in \mathbb{N}} \theta_i B^i\left( \sum_{j=1}^p \phi_j B^j(X_t) \right) = \varepsilon_t
$$

bzw.

$$
	\forall t \in \mathbb{Z} : X_t^* := \sum_{i \in \mathbb{N}} \theta_i B^i\left( \sum_{j=1}^p \phi_j B^j(Y_t) \right)
$$

mit
- $\theta$ der Inverse von $\vartheta$