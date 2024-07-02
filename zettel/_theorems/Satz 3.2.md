Sei $(\Omega, \mathcal{P}(\Omega), P)$ ein diskreter [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $R, S \ne \emptyset$, $X : \Omega \to R$, $Y : \Omega \to S$ diskrete [[zettel/Zufallsvariable|Zufallsvariablen]], $f : R \times S \to \mathbb{R}$ eine [[zettel/Funktion|Funktion]] mit
- $\text{E}[|f(X, y)|] \lt \infty$

Es gilt

$$
	\forall y \in S_{P^Y} : \text{E}[f(X, y) \mid Y=y] = \sum_{x \in R} f(x, y) P(X=x \mid Y=y)
$$