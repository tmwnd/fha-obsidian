Sei $X : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $\Theta := \{ 0, 1 \}$ eine Parametermenge, $\Theta_0 = \{ 0 \} \subset \Theta$, $\vartheta \in \Theta$ der Paramter der Verteilung von $X$, $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]], $f_\vartheta(x) \mid x \in R$ eine [[zettel/μ-Dichte|μ-Dichte]], $\text{H} : \vartheta = 0, \text{K} : \vartheta = 1$ ein [[zettel/Statistisches Testproblem|satistisches Testproblem]]  mit
- $\forall \vartheta \in \Theta : P_\vartheta^X \ll \mu$

Eine [[zettel/Testfunktion|Testfunktion]] $\varphi : (R, \mathscr{S}) \to (\{ 0, 1 \}, \mathscr{B}_{\{ 0, 1 \}})$ heißt *Likelihood-Quotiententesfunktion* bzw. $\varphi(X)$ heißt *Likelihood-Quotiententest*, falls

$$
	\exists k \in [0, \infty), \forall x \in \{ f_1(x) \ne kf_0(x) \} : \varphi(x) \overset{\mu\text{-f. s.}}{=} \begin{cases}
		1 & f_1(x) \gt kf_0 \\
		0 & f_1(x) \lt kf_0
	\end{cases}
$$