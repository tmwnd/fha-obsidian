Sei $X : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $\Theta$ eine Parametermenge, $\delta : \Theta \to \mathbb{R}^n$, $\delta(\Theta) \in \mathscr{B}^d$, $\delta(\vartheta)$ der Parameter der Verteilung von $X$, $\eta \in \delta(\Theta)$, $\Theta_0(\eta) := \{ \vartheta \in \Theta \mid \delta(\vartheta) = \eta \}$, $\emptyset \ne \Theta_1(\eta) \subseteq \Theta \setminus \Theta_0(\eta)$, $\varphi_\eta(x) = I_{A(\eta)}(x)$ eine [[zettel/Testfunktion|Testfunktion]] zu dem vorgegebenen Testniveau $\alpha$, $B$ ein [[zettel/Konfidenzbereich|Konfidenzbereich]] für $\delta(\vartheta)$ zum Konfidenzniveau $1-\alpha$, $\text{H} : \vartheta \in \Theta_0(\eta), \text{K} : \vartheta \in \Theta_1(\eta)$ ein [[zettel/Statistisches Testproblem|statistisches Testproblem]] nach dem [[zettel/Korrespondenzprinzip|Korrespondenzprinzip]].

Es gilt

$$
	\{ (x, \eta) \in R \times \delta(\Theta) \mid x \in A(\eta) \} \in \mathscr{S} \otimes \mathscr{B}^d
$$

Das Volumen von $B(X)$ ist definiert als

$$
	\lambda(B(X)) := \int_{\delta(\Theta)} I(\eta \in B(X)) d\eta = \int_{\delta(\Theta)} I(X \in A(\eta)) d\eta
$$

Die [[zettel/Funktion|Funktion]] $f : R \times \delta(\Theta) \to \{ 0, 1 \}$ sei definiert als

$$
	f(x, \eta) := I(x \in \mathcal{A}(\eta))
$$

Es gilt
- $f^{-1}(\{ 1 \}) = \{ (x, \eta) \in R \times \delta(\Theta) \mid x \in A(\eta) \} \in \mathscr{S} \otimes \mathscr{B}^d$
- $f$ ist $(\mathscr{S} \otimes \mathscr{B}^d, \mathcal{P}(\{ 0, 1 \}))$-[[zettel/Funktion/A-S-Messbarkeit|messbar]]

Sei $\emptyset \ne \tau$ die Familie Familien von Testfunktionen $(\vartheta_\eta(X))_{\eta \in \delta(\Theta)}$ zum exakt eingehaltenen Testniveau $\alpha$, $\mathcal{B}$ die Menge der [[zettel/Korrespondenzprinzip|korrespondierenden]] [[zettel/Konfidenzbereich|Konfidenzbereiche]].

Es gilt $(\vartheta_\eta^*(X))_{\eta \in \delta(\Theta)} \in \tau$ optimal im Sinne von

$$
	\forall (\vartheta_\eta(X))_{\eta \in \delta(\Theta)} \in \tau, \eta \in \delta(\Theta), \vartheta \in \Theta_1(\eta) : P_\vartheta^X(\vartheta_\eta(X) = 1) \ge P_\vartheta^X(\vartheta_\eta(X) = 1)
$$

Der zu $(\vartheta_\eta(X))_{\eta \in \delta(\Theta)}$ [[zettel/Korrespondenzprinzip|korrespondierende]] [[zettel/Konfidenzbereich|Konfidenzbereich]] $B^* \in \mathcal{B}$

$$
	\forall B \in \mathcal{B}, \vartheta \in \Theta : \text{E}_\vartheta[\lambda(B^*(X))] \le \text{E}_\vartheta[\lambda(B(X))]
$$