Sei $X$ eine reelle [[Zufallsvariable]] mit
- $E[|X|^2] \lt \infty$

Die *Varianz* von $X$ ist mit dem [[Erwartungswert]] $E$ definiert als

$$
	\text{Var}(X) = E[(X - E[X])^2] = E[X^2] - E[X]^2
$$

---

Sei $\mathcal{H}$ ein [[Hypothese|Hypothesenset]], $f$ eine [[Target-Function]] mit
- $\overline{g} = \mathbb{E}_\mathcal{D}[g^{(\mathcal{D})}(x)]$ die gemittelte finale Hypothese

Die *Varianz* von $\mathcal{H}$ ist definiert als

$$
	\mathbb{E}_x[\mathbb{E}_\mathcal{D}[(g^{(\mathcal{D})}(x) - \overline{g}(x))^2]]
$$