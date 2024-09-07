Sei $X$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $\emptyset \ne \Theta$ eine Parametermenge, $\emptyset \ne \Theta_0 \subset \Theta$, $\Phi_\alpha := \{ \varphi : (R, \mathscr{S}) \to ([0, 1], \mathscr{B}_{[0, 1]}) \mid \forall \vartheta \in \Theta_0 :  \text{E}_\vartheta[\phi(X)] \le \alpha \}$ die Menge der[[zettel/Testfunktion|Testfunktionen]] zum Testniveau $\alpha$.

$\varphi^* \in \Phi_\alpha$ heißt *gleichmäßig beste Testfunktion* zum Testniveau $\alpha$ bzw. $\varphi^*(X)$ heißt *gleichmäßig bester Test* zum Testniveau $\alpha$, falls

$$
	\forall \vartheta \in \Theta \setminus \Theta_0 : 1 - \text{E}_\vartheta[\varphi^*(X)] = \inf \{ 1 - \text{E}_\vartheta[\varphi(X)] \mid \varphi \in \Phi_\alpha \}
$$