Sei $(X_t)_{t \in \mathbb{R}_0}$ ein rechtsstetiger [[zettel/Stochastischer Prozess|Stochastischer Prozess]], $\tau$ eine [[zettel/Stoppzeit|Stoppzeit]].

Der *gestoppte Prozess* $(X_t^\tau)_{t \in \mathbb{R}_0}$ ist definiert als

$$
	\forall t \in \mathbb{R}_0, \omega \in \Omega : X_t^\tau(\omega) := (X_{t \land \tau(\omega)})(\omega) := \begin{cases}
		X_{\tau(\omega)}(\omega), & \tau(\omega) \le t \\
		X_t(\omega), & \tau(\omega) \gt t
	\end{cases}
$$