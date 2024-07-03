Sei $(\Omega, \mathcal{P}(\Omega), P)$ ein diskreter [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $S \ne \emptyset$, $X : \Omega \to \mathbb{R}$, $Y : \Omega \to S$ diskrete [[zettel/Zufallsvariable|Zufallsvariablen]].

Die *Faktorisierung des [[zettel/Bedingter Erwartungswert (diskret)|diskreten bedingten Erwartungswertes]]* $e : S \to \mathbb{R}$ ist definiert als

$$
	\forall y \in S_{P^Y} : e(y) := \text{E}[X \mid Y=y]
$$

Es gilt
- $e(Y) = e \circ Y := \text{E}[X \mid Y]$

und

$$
	\text{E}[X] = \sum_{y \in S_{P^Y}}\left( \sum_{x \in \mathbb{R}} xP(X=x \mid Y=y) \right) P(Y=y) = \sum_{y \in S_{P^Y}} e(y) P(Y=y) = \text{E}[e(Y)] = \text{E}[\text{E}[X \mid Y]]
$$