Seien $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathscr{B}^p)$, $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathscr{B}^d)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $k$ ein [[zettel/Übergangskern|Übergangskern]] von $(\mathbb{R}^d, \mathscr{B}^d)$ nach $(\mathbb{R}^p, \mathscr{B}^p)$.

$k$ heißt *bedingte Verteilung* von $X$ unter $Y$, falls

$$
	\forall B \in \mathscr{B}^p, C \in \mathscr{B}^d : P(X \in B, Y \in C) = \int_C k(y, B) dP^Y(y)
$$

---

Seien $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathscr{B}^p)$, $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathscr{B}^d)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $y \in \mathbb{R}^d$, $k$ eine [[zettel/Bedingte Verteilung|bedingte Verteilung]] von $X$ unter $Y$.

Das [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaß]] $\forall B \in \mathscr{B}^p : B \mapsto k(y, B)$ heißt *bedingte Verteilung* von $X$ unter $Y=y$.

Schreibe
- $P^{X \mid Y=y}$