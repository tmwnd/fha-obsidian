Seien $(X_n)_{n \in \mathbb{N}_0} : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathscr{B}^p)$ [[zettel/Zufallsvariable|Zufallsvariablen]], $(P_n)_{n \in \mathbb{N}_0}$ [[zettel/Übergangskern|Übergangskerne]] von $(\mathbb{R}^p, \mathscr{B}^p)$ nach $(\mathbb{R}^p, \mathscr{B}^p)$.

Die *Markov-Eigenschaft* gilt, falls

$$
	\forall n \in \mathbb{N}, B \in \mathscr{B}^p : P(X_n \in B \mid X_0, \dots, X_{n-1}) = P_{n-1}(X_{n-1}, B)
$$