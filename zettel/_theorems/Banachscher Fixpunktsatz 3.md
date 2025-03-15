Sei $(X, d)$ ein [[zettel/Metrischer Raum/Vollständigkeit|vollständer]] [[zettel/Metrischer Raum|metrischer Raum]], $A : X \to X$ eine [[zettel/Metrischer Raum/Operator/Kontraktion|Kontraktion]] mit Kontraktionszahl $q$, $x$ der [[zettel/Metrischer Raum/Operator/Fixpunkt|Fixpunkt]] von $A$, $(x_n)_{n \in \mathbb{N}} \in X$ eine Folge mit
- $\forall n \in \mathbb{N}, n \ge 2 : x_n := Ax_{n-1}$

Es gelten die Fehlerabschätzungen
- a-priori

$$
	\forall n \in \mathbb{N} : d(x_n, x) \le \frac{q^n}{1-q} \ d(1, 0)
$$

- a-posteriori

$$
	\forall n \in \mathbb{N} : d(x_n, x) \le \frac{q}{1-q} \ d(x_n, x_{n-1})
$$