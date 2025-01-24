Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{IID}(0, 1)$, $(a_i)_{i \in \{ 1, \dots, p \}}, (b_i)_{i \in \{ 1, \dots, q \}} \in \mathbb{R}_0^+$ mit
- $a_p \gt 0$.
- $b_q \gt 0$.

Eine [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Verallgemeinerter Autoregressiver Bedingter Heteroskedastischer Prozess (GARCH-Prozess) der Ordnungen $p$ und $q$*, falls

$$
	\forall t \in \mathbb{Z} : X_t = \underbrace{\sqrt{a_0 + \sum_{i=1}^p a_i X_{t-i}^2 + \sum_{i=1}^q b_i\sigma_{t-i}^2}}_{\sigma_t} \cdot \varepsilon_t
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{GARCH}(p, q)
$$

Es gilt
- $\forall t \in \mathbb{Z} : \mu_t = 0$
- $\forall t \in \mathbb{Z} : \text{Var}[X_t \mid (X_{t-i})_{i \in \{ 1, \dots, p \}}] = \sigma_t^2$

und
- $(X_t)_{t \in \mathbb{Z}}$ ist unter bestimmten Bedingungen [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]] $\implies$ $(X_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$

und
- $\exists k \in \overline{\mathbb{N}} : (X_t)_{t \in \mathbb{Z}} \sim \text{ARCH}(k)$