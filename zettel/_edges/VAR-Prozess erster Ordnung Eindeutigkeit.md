Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{VAR}(1)$ von $(\varepsilon_t)_{t \in \mathbb{Z}}$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]] mit Werten in $\mathbb{R}^k$, $(\lambda_i)_{i \in \{ 1, \dots k \}}$ die Eigenwerte von $\Phi$.

$(X_t)_{t \in \mathbb{Z}}$ ist *eindeutig bestimmt*, falls
- $\forall i \in k : |\lambda_i| \lt 1$

Es gilt

$$
	\exists! \Phi \in \mathbb{R}^{k \times k} \ \forall t \in \mathbb{Z} : X_t = \varepsilon_t + \Phi B(X_t)
$$