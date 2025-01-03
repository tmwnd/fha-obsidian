Sei $X : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $x \in R$ eine Beobachtung von $X$, $\emptyset \ne \Theta$ eine Parametermenge, $\emptyset \ne \Theta_0 \subset \Theta$ mit
- $\Theta, \Theta_0$ nicht einelementig

Die *Likelihood-Quotienten-Teststatistik* $\Lambda$ ist definiert als

$$
	\Lambda(x) := \begin{cases}
		\frac{\sup_{\vartheta \in \Theta} f_\vartheta(x)}{\sup_{\vartheta \in \Theta_0} f_\vartheta(x)} \quad & \sup_{\vartheta \in \Theta_0} f_\vartheta(x) \gt 0 \\
		0 \quad & \text{sonst}
	\end{cases}
$$

falls
- $T(x)$ $(\mathscr{S}, \mathscr{B})$-[[zettel/Funktion/A-S-Messbarkeit|messbar]] ist