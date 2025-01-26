Sei $(X_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ eine [[zettel/Vektorwertiger Zeitreihe|vektorwertiger Zeitreihe]] mit Werten in $\mathbb{R}^k$, $\Sigma := \text{E}[X_0X_0^T]$ (Varianz-Kovarianzmatrix) mit
- $\forall t \in \mathbb{Z}, l \in \{ 1, \dots, k \} : \text{E}[X_{t, i}] = 0$

$(X_t)_{t \in \mathbb{Z}}$ heißt *Vektorwertiges Weißes Rauschen*, falls
- $\forall t, s \in \mathbb{Z}, t \ne s : \text{E}[X_tX_s^T] = 0$
- $\forall t \in \mathbb{Z} : \text{E}[X_tX_t^T] = \Sigma$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{VWN}(0, \Sigma)
$$