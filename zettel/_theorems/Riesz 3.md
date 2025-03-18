Sei $((X, \oplus, \odot), \| \cdot \|)$ ein [[zettel/Normierter Raum|normierter Raum]], $A : X \to X$ ein [[zettel/Normierter Raum/Operator/Kompaktheit|kompakter]] [[zettel/Metrischer Raum/Operator|Operator]] in $X$, $L := I - A$.

Es gilt
- $\exists! r \in \mathbb{N}_0$ mit

$$
	\underbrace{N(L^0)}_{\{ 0 \}} \subset N(L) \subset N(L^2) \subset \ldots \subset N(L^r) = N(L^{r+1})
$$

und

$$
	R(L^{r+1}) = R(L^r) \subset \ldots \subset R(L^2) \subset R(L) \subset \underbrace{R(L^0)}_X
$$

Schreibe
- $r$ heißt *Riesz-Zahl*