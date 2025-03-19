Sei $(X, \| \cdot \|)$ ein [[zettel/Normierter Raum|normierter Raum]], $A : X \to X$ ein [[zettel/Linearer Raum/Operator/Linearität|linearer]] [[zettel/Normierter Raum/Operator/Beschränktheit|beschränkter]] [[zettel/Metrischer Raum/Operator|Operator]] in $X$.

Das *Residualspektrum* $\sigma_r(A)$ von $A$ ist definiert als

$$
	\sigma_r(A) := \{ \lambda \in \mathbb{C} \mid N(\lambda I - A) = \{ 0 \}, R(\lambda I - A) \text{ nicht dicht in } X \}
$$

Es gilt
- $\lambda \in \sigma_r(A) \implies \lambda I - A$ ist [[zettel/Funktion/Injektivität|injektiv]]
- $\lambda \in \sigma_r(A) \implies (\lambda I - A)^{-1}$ existiert nicht