Seien $d, D, s \in \mathbb{N}_0$, $\phi, \Phi, \vartheta, \Theta$ Polynome des Grades $p, P, q, Q$ und
- $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]] definiert über

$$
	\forall t \in \mathbb{Z} : X_t = \varepsilon_t + \sum_{i=1}^p \phi_i B\left( \sum_{j=1}^P \Phi_j B^{js}(X_t) \right) + \sum_{i=1}^q \vartheta_i B\left( \sum_{j=1}^Q \Theta_j B^{js}(\varepsilon_t) \right)
$$

- $(Y_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]] definiert über

$$
	\forall t \in \mathbb{Z} : X_t : \nabla^d\nabla_s^D Y_t
$$

mit
- $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]]

$(Y_t)_{t \in \mathbb{Z}}$ heißt *Autoregressiver Integrierter Moving Average Prozess der Ordnung $d$ mit Saisonaler Komponente und Periodenlänge $s$*.

Schreibe

$$
	(Y_t)_{t \in \mathbb{Z}} \sim \text{SARIMA}(p, d, q) \times (P, D, Q)_s
$$

Es gilt

$$
	\forall t \in \mathbb{Z} : \nabla^d \nabla_s^D Y_t = \varepsilon_t + \sum_{i=1}^p \phi_i B^i\left( \sum_{j=1}^P \Phi_j B^{js}(\nabla^d \nabla^D_s Y_t) \right) + \sum_{i=1}^q \vartheta_i B^i\left( \sum_{j=1}^Q \Theta_j B^{js}(\varepsilon_t) \right)
$$