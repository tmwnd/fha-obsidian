Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $\overline{\mathcal{L}}$ die Borelsche $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] , $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine [[zettel/Zufallsvariable|Zufallsvariable]] mit
- $\int X^+ dP \lt \infty$ oder
- $\int X^- dP \lt \infty$

Der *Erwartungswert* von $X$ bzw. $P^X$ ist definiert als

$$
	\text{E}[X] := \int X dP = \int X^+ dP - \int X^- dP
$$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $\mathcal{L}$ die Borelsche $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] , $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine [[zettel/Zufallsvariable|Zufallsvariable]] mit der $\lambda$-[[zettel/λ-Dichte|Dichte]] $f : (\mathbb{R}, \mathcal{L}) \to (\mathbb{R}, \mathcal{L})$, $g : (\mathbb{R}, \mathcal{L}) \to (\mathbb{R}, \mathcal{L})$ eine nicht-negative [[zettel/Funktion|Funktion]].

Es gilt

$$
	\text{E}[g \circ X] = \int g \circ X dP = \int_{-\infty}^{+\infty} g(x)f(x) dx
$$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $\mathcal{L}$ die Borelsche $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] , $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine diskret verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $\delta_a$ das [[zettel/Dirac-Maß|Dirac-Maß]], $g : (R, \mathscr{S}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}})$ eine nicht-negative [[zettel/Funktion|Funktion]] und $(R, \mathscr{S})$ ein [[zettel/Messraum|Messraum]] mit
- $\forall x \in R : \{ x \} \in \mathscr{S}$
- $\exists S \in \mathscr{S} : P^X(S) = P(X \in S) = 1$

Es gilt mit dem $P^X$-[[zettel/PX-Integral|Integral]]

$$
	\text{E}[g \circ X] = \int g dP^X = \sum_{a \in S} g(y)P(X = a) = \sum_{a \in R} g(a) P(X = a)
$$

---

Sie $X$ ein $d$-dimensionaler [[zettel/Zufallsvariable|Zufallsvektor]] mit
- $\forall i \in \{ 1, \dots, d \} : \text{E}[X_i] \lt \infty$ bzw. $\text{E}[|X_i|] \lt \infty$

Der *Erwartungswertvekotor* von $X$ ist definiert als

$$
	\text{E}[X] = (\text{E}[X_1], \dots, \text{E}[X_d])
$$

Es gilt
- $\forall A \in \mathbb{R}^{n \times d}, b \in \mathbb{R}^n : \text{E}[AX + b] = AE[X] + b$
- $\text{E}[X^2] \lt \infty$