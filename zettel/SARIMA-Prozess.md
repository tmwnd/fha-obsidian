Seien $d, D, s \in \mathbb{N}_0$, $\phi, \Phi, \vartheta, \Theta$ Polynome des Grades $p, P, q, Q$ und
- die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ definiert über

$$
	\forall t \in \mathbb{Z} : \sum_{i=1}^p \phi_i B\left( \sum_{j=1}^P \Phi_j B^s(X_t) \right) = \sum_{i=1}^q \vartheta_i B\left( \sum_{j=1}^Q \Theta_j B^s(\varepsilon_t) \right)
$$

- die [[zettel/Zeitreihe|Zeitreihe]] $(Y_t)_{t \in \mathbb{Z}}$ definiert über

$$
	\forall t \in \mathbb{Z} : X_t : \nabla^d\nabla_s^D Y_t
$$

mit
- $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]]

$(Y_t)_{t \in \mathbb{Z}}$ heißt *Autoregressiver integrierter Moving Average Prozess der Ordnung $d$ mit saisonaler Komponente und Periodenlänge $s$*.

Schreibe

$$
	(Y_t)_{t \in \mathbb{Z}} \sim \text{SARIMA}(p, d, q) \times (P, D, Q)
$$

Es gilt

$$
	\forall t \in \mathbb{Z} : \sum_{i=1}^p \phi \nabla^d Y_t = \sum_{i=1}^q \vartheta\varepsilon_t
$$