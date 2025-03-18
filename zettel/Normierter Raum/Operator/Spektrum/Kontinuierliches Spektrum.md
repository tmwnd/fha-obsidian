Sei $((X, \oplus, \odot), \| \cdot \|)$ ein [[zettel/Normierter Raum|normierter Raum]], $A : X \to X$ ein [[zettel/Normierter Raum/Operator/Beschränktheit|beschränkter]] [[zettel/Metrischer Raum/Operator|Operator]] in $X$.

Das *kontinuierliche Spektrum* $\sigma_c(A)$ von $A$ ist definiert als

$$
	\sigma_c(A) = \{ \lambda \in \mathbb{C} \mid N(\lambda I - A) = \{ 0 \}, R(\lambda I - A) \ne X, R(\lambda I - A) \text{ dicht in } X \}
$$

Es gilt
- $\lambda \in \sigma_c(A) \implies \lambda I - A$ ist [[zettel/Funktion/Injektivität|injektiv]]
- $\lambda \in \sigma_c(A) \implies (\lambda I - A)^{-1}$ existiert, ist jedoch nicht [[zettel/Normierter Raum/Operator/Beschränktheit|beschränkt]]