Sei $\delta : \Theta \to \mathbb{R} \in C^1$.

Eine Folge von [[zettel/Schätzer|Schätzern]] heißt *asymptotisch effizient*, falls

$$
	\forall \vartheta \in \Theta : \sqrt{n}(d_n((X_i)_{i \in \{ 1, \dots, n \}}) - \delta(\vartheta)) \overset{V}{\longrightarrow} \mathcal{N}\left( 0, \frac{\delta'^2(\vartheta)}{i_{X_1}(\vartheta)} \right)
$$