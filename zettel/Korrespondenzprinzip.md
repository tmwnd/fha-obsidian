Sei $X : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $\Theta$ eine Parametermenge, $\vartheta \in \Theta$, $\delta : \Theta \to \mathbb{R}^n$, $\delta(\vartheta)$ der Parameter der Verteilung von $X$, $\eta \in \delta(\Theta)$, $\Theta_0(\eta) := \{ \vartheta \in \Theta \mid \delta(\vartheta) = \eta \}$, $\emptyset \ne \Theta_1(\eta) \subseteq \Theta \setminus \Theta_0(\eta)$, $\{ P_\vartheta^X \mid \vartheta \in \Theta_0(\eta) \cup \Theta_1(\eta) \}$ die Familie der möglichen Verteilungen von $X$, $\text{TP}(\eta) := \text{H} : \vartheta \in \Theta_0(\eta), \text{K} : \vartheta \in \Theta_1(\eta)$ ein [[zettel/Statistisches Testproblem|statistisches Testproblem]].

Der [[zettel/Konfidenzbereich|Konfidenzbereich]] $B$ ist definiert als

$$
	B(x) := \{ \eta \in \delta(\Theta) \mid x \in A(\eta) \} \mid x \in R
$$

mit
- $A(\eta) \in \mathscr{S}$

falls
- $\vartheta_\eta(x) := I_{A(\eta)^\complement}(x) \mid x \in R$ [[zettel/Testfunktion|Testfunktion]] zum Testniveau $\alpha$ für $\text{TP}(\eta)$

Es gilt
- $B(X)$ ist ein [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] für $\delta(\vartheta)$ zum Konfidenzniveau $1-\alpha$

---

Die [[zettel/Testfunktion|Testfunktion]] $\vartheta_\eta$ ist definiert als

$$
	\vartheta_\eta(x) = I_{A(\eta)^\complement}(x)
$$

falls
- $A(\eta) := \{ x \in R \mid \eta \in B(x) \}$
- $B(X)$ ist ein [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] für $\delta(\vartheta)$ zum Konfidenzniveau $1-\alpha$

Es gilt
- $\vartheta_\eta$ ist eine [[zettel/Testfunktion|Testfunktion]] zum Testniveau $\alpha$