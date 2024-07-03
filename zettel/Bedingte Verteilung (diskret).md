Sei $(\Omega, \mathcal{P}(\Omega), P)$ ein diskreter [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $R, S \ne \emptyset$, $B \subseteq R$, $X : \Omega \to R$, $Y : \Omega \to S$ diskrete [[zettel/Zufallsvariable|Zufallsvariablen]], $y \in S_{P^Y}$.

Die *bedingte [[zettel/Verteilungsfunktion|Verteilungsfunktion]]* $P^{X \mid Y=y}$ von $X$ unter $Y=y$ ist definiert als

$$
	P^{X \mid Y=y}(B) := P(X \in B \mid Y=y) = \frac{P(X \in B, Y=y)}{P(Y=y)}
$$

$P^{X \mid Y=y}$ ist festgelegt durch die [[zettel/Wahrscheinlichkeitsmassefunktion|Wahrscheinlichkeitsmassefunktion]]

$$
	p(x) := P^{X \mid Y=y}(\{ x \}) = P(X=x \mid Y=y) = \frac{P(X=x, Y=y)}{P(Y=y)}
$$