Sei $(\Omega, \mathcal{P}(\Omega), P)$ ein diskreter [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $S \ne \emptyset$, $X : \Omega \to \mathbb{R}$, $Y : \Omega \to S$ diskrete [[zettel/Zufallsvariable|Zufallsvariablen]], $y \in S_{P^Y}$ mit
- $\text{E}[|X|] \lt \infty$

Der *bedingte [[zettel/Erwartungswert|Erwartungswert]]* von $P^{X \mid Y=y}$ bzw. $X$ unter $Y=y$ ist definiert als

$$
	\text{E}[X \mid Y=y] := \sum_{x \in \mathbb{R}} x P(X=y \mid Y=y)
$$

Es gilt

$$
	\sum_{x \in \mathbb{R}} |x| P(X=x) = \sum_{y \in S_{P^Y}} \left( \sum_{x \in \mathbb{R}} |x| P(X=x \mid Y=y) \right) \lt \infty
$$

und

$$
	\forall y \in S_{P^Y} : \sum_{x \in \mathbb{R}} |x| P(X=x, Y=y) \lt \infty
$$