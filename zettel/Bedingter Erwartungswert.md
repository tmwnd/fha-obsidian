Sei $X : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $\mathcal{B}$ eine [[zettel/Unter-σ-Algebra|Unter-σ-Algebra]] von $\mathcal{A}$ mit
- $\text{E}[|X|] \lt \infty$

Der *bedingte Erwartungswert* $X_0$ von $X$ unter $\mathcal{B}$ ist definiert als $X_0 : (\Omega, \mathcal{B}) \to (\mathbb{R}, \mathcal{L})$ und es gilt
- $\text{E}[|X_0|] \lt \infty$
- Die [[zettel/Testgleichung|Testgleichung]] gilt
- $X_0$ ist P-f. s. TODO eindeutig bestimmt

Schreibe

$$
	\text{E}[X \mid \mathcal{B}] = X_0
$$

---

Sei $X : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathcal{L}^d)$ ein [[zettel/Zufallsvariable|Zufallsvektor]], $\mathcal{B} := \{ Y^{-1}(B) : B \in \mathcal{L}^d \}$ mit
- $\text{E}[|X|] \lt \infty$

Der *bedingte Erwartungswert* von $X$ unter $Y$ ist definiert als

$$
	\text{E}[X \mid Y] := \text{E}[X \mid \mathcal{B}]
$$