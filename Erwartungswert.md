Sei $(\Omega, \mathcal{A}, P)$ ein [[Maßraum|Wahrscheinlichkeitsraum]], $\overline{\mathcal{L}}$ die Borelsche $\sigma$-[[Borelsche sigma-Algebra|Algebra]] , $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine [[Zufallsvariable]] mit
- $\int X^+ dP \lt \infty$ oder
- $\int x^- dP \lt \infty$

Der *Erwartungswert* von $X$ bzw. $P^X$ ist mit dem $P$-[[P-Integral|Integral]] definiert als

$$
	E[X] = \int X dP = \int X^+ dP - \int X^- dP
$$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Maßraum|Wahrscheinlichkeitsraum]], $\mathcal{L}$ die Borelsche $\sigma$-[[Borelsche sigma-Algebra|Algebra]] , $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine [[Zufallsvariable]] mit der $\lambda$-[[lambda-Dichte|Dichte]] $f : (\mathbb{R}, \mathcal{L}) \to (\mathbb{R}, \mathcal{L})$, $g : (\mathbb{R}, \mathcal{L}) \to (\mathbb{R}, \mathcal{L})$ eine nicht-negative [[Funktion]].

Es gilt mit dem $P$-[[P-Integral|Integral]] 

$$
	E[g \circ X] = \int g \circ X dP = \int_{-\infty}^{+\infty} g(x)f(x) dx
$$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Maßraum|Wahrscheinlichkeitsraum]], $\mathcal{L}$ die Borelsche $\sigma$-[[Borelsche sigma-Algebra|Algebra]] , $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine diskret verteilte [[Zufallsvariable]], $\delta_a$ das [[Dirac-Maß]], $g : (R, \mathscr{S}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}})$ eine nicht-negative [[Funktion]] und $(R, \mathscr{S})$ ein [[Messraum]] mit
- $\forall x \in R : \{ x \} \in \mathscr{S}$
- $\exists S \in \mathscr{S} : P^X(S) = P(X \in S) = 1$

Es gilt mit dem $P^X$-[[PX-Integral|Integral]]

$$
	E[g \circ X] = \int g dP^X = \sum_{a \in S} g(y)P(X = a) = \sum_{a \in R} g(a) P(X = a)
$$

---

Sie $X$ ein $d$-dimensionaler [[Zufallsvariable|Zufallsvektor]] mit
- $\forall i \in \{ 1, \dots, d \} : E[X_i] \lt \infty$ bzw. $E[|X_i|] \lt \infty$

Der *Erwartungswertvekotor* von $X$ ist definiert als

$$
	E[X] = (E[X_1], \dots, E[X_d])
$$

Es gilt
- $\forall A \in \mathbb{R}^{n \times d}, b \in \mathbb{R}^n : E[AX + b] = AE[X] + b$
- $E[X^2] \lt \infty$