Sei $X : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $x \in R$ eine Beobachtung von $X$, $\Theta$ eine Parametermenge, $\delta(\vartheta)$ der Parameter der Verteilung von $X$, $1-\alpha$ das vorgegebene Konfidenzniveau.

Eine *Abbildung* $B : R \to \mathcal{P}(\mathbb{R}^d)$ heißt *Konfidenzbereich* für $\delta(\vartheta)$ zum Konfidenzniveau $1-\alpha$, falls
- $\forall \vartheta \in \Theta : \{ x \in R \mid \delta(\vartheta) \in B(x) \} \in \mathscr{S}$
- $\forall \vartheta \in \Theta : P_\vartheta(\delta(\vartheta) \in B(X)) = P_\vartheta^X(\{ x \in R \mid \delta(\vartheta) \in B(x) \}) \ge 1-\alpha$
