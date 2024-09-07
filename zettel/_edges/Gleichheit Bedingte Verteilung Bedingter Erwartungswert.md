Seien $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathscr{B}^p)$, $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathscr{B}^d)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $k$ eine [[zettel/Bedingte Verteilung|bedingte Verteilung]] von $X$ unter $Y$.

Es gilt $P$-f. s.

$$
	\forall B \in \mathscr{B}^p : k(Y, B) = \text{E}[I_B(X) \mid Y]
$$

da

$$
	\forall B \in \mathscr{B}^p, C \in \mathscr{B}^d : \text{E}[k(Y, B) \cdot I_C(Y)] = \int_C k(y, B) dP^Y(y) = P(X \in B, Y \in C) = \text{E}[I_B(X) \cdot I_C(Y)]
$$