Sei $X : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathscr{B})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathscr{B}^d)$ ein [[zettel/Zufallsvariable|Zufallsvektor]] mit
- $\text{E}[|X|] \lt \infty$

Die *faktorisierung des [[zettel/Bedingter Erwartungswert|bedingten Erwartungswertes]]* $g$ von $X$ unter $Y$ ist definiert als

$$
	\forall y \in \mathbb{R}^d : g(y) := \text{E}[X \mid Y=y]
$$

Es gilt
- $g(Y) = g \circ Y := \text{E}[X \mid Y]$
- $g$ ist $P^Y$-f. s. eindeutig bestimmt