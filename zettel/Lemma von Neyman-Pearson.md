Sei $X : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $\Theta := \{ 0, 1 \}$ eine Parametermenge, $\Theta_0 = \{ 0 \} \subset \Theta$, $\vartheta \in \Theta$ der Paramter der Verteilung von $X$, $\mu$ eine [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]], $f_\vartheta(x) \mid x \in R$ eine [[zettel/μ-Dichte|μ-Dichte]], $\text{H} : \vartheta = 0, \text{K} : \vartheta = 1$ ein [[zettel/Likelihood-Quotiententestproblem|Likelihood-Quotiententestproblem]], $\alpha \in (0, 1)$ das vorgegebene Testniveau mit
- $\forall \vartheta \in \Theta : P_\vartheta^X \ll \mu$

Es gilt
- $\exists k^* \in [0, \infty), \gamma^* \in [0, 1] : \text{E}_0[\varphi^*(X)] = \alpha$ mit
	- der [[zettel/Likelihood-Quotiententestproblem|Likelihood-Quotiententestfunktion]] $\varphi^*(x) := I(f_1(x) \gt k^*f_0(x)) + \gamma^*I(f_1(x) = k^*f_0(x) \mid x \in R$
- $\text{E}_0[\varphi(X)] = \alpha$ $\implies$ $\varphi(X)$ [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig bester]] [[zettel/Statistischer Test|statistischer Test]] zum Testniveau $\alpha$
- $\varphi(X)$ [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig bester]] [[zettel/Statistischer Test|statistischer Test]] zum Testniveau $\alpha$ $\implies$ $\varphi(X)$ ist [[zettel/Likelihood-Quotiententestproblem|Likelihood-Quotiententestproblem]]