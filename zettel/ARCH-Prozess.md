Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{IID}(0, 1)$, $(a_i)_{i \in \{ 1, \dots, p \}} \in \mathbb{R}_0^+$ mit
- $a_p \gt 0$.

Eine [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Autoregressiver Bedingter Heteroskedastischer Prozess (ARCH-Prozess) der Ordnung $p$*, falls

$$
	\forall t \in \mathbb{Z} : X_t = \underbrace{\sqrt{a_0 + \sum_{i=1}^p a_i B^i(X_t^2)}}_{\sigma_t} \cdot \varepsilon_t
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{ARCH}(p)
$$

Es gilt
- $\forall t \in \mathbb{Z} : \text{Var}[X_t \mid (B^i(X_t))_{i \in \{ 1, \dots, p \}}] = \sigma_t^2$

und
- $\forall t \in \mathbb{Z} : \text{Var}[X_t] = a_0 + a_1 \text{Var}[B(X_t)]$, falls $(X_t)_{t \in \mathbb{Z}} \sim \text{ARCH}(1)$
- $\forall t \in \mathbb{Z} : \text{Var}[X_t] = \frac{a_0}{1 - a_1}$, falls $(X_t)_{t \in \mathbb{Z}}$ [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]

und
- $(X_t)_{t \in \mathbb{Z}} \sim \text{GARCH}(p, 0)$