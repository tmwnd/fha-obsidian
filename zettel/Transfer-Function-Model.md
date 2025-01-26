Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ von $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$ [[zettel/ARMA-Prozess/Invertierbarkeit|invertierbar]], $(R_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(r, s)$ von $(\eta_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \tau^2)$, $(\alpha_i)_{t \in \mathbb{N}_0} \in \mathbb{R}$, $\nu \in \mathbb{N}$ mit
- $(\varepsilon_t)_{t \in \mathbb{Z}}$ und $(\eta_t)_{t \in \mathbb{Z}}$ unkorreliert

Eine [[zettel/Zeitreihe|Zeitreihe]] $(Y_t)_{t \in \mathbb{Z}}$ folgt dem *Transfer-Function-Model (TFM)*, falls

$$
	\forall t \in \mathbb{Z} : Y_t = \sum_{i \in \mathbb{N}_0} \alpha_i B^{i+\nu}\left( 1 - \sum_{j \in \mathbb{N}_0} \gamma_j B^j(X_t) \right) + R_t
$$

mit
- $\gamma$ der Inverse von $\alpha$

Es gilt
- $\forall t \in \mathbb{Z} : Y_t$ ist von $(X_s)_{s \in \mathbb{Z}, s \le t- \nu}$ abhängig

und

$$
	\exists (\beta_i)_{i \in \mathbb{N}_0} \in \mathbb{R} \forall t \in \mathbb{Z} : Y_t = \sum_{i \in \mathbb{N}_0} \beta_i B^i(X_t) + R_t
$$