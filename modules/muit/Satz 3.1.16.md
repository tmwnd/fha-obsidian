Sei $(R_i)_{i \in I}$, $(\mathcal{R}_i)_{i \in I}$ ein System von $\sigma$-[[σ-Algebra|Algebren]], $(f_i)_{i \in I}$ eine Menge von [[Funktion|Funktionen]] mit
- $\forall i \in I : f_i : \Omega \to (R_i, \mathcal{R}_i)$

Es existiert das System $(\mathcal{A}_i)_{i \in I}$ mit
- $\forall i \in I : A_i = f_i^{-1}(\mathcal{R}_i)$

und die $\sigma$-[[σ-Algebra|Algebra]] $\mathcal{A}$ auf $\Omega$ ist definiert als

$$
	\mathcal{A} = \sigma\left( \bigcup_{i \in I} \mathcal{A}_i \right)
$$

Sei weiterhin $g : (S, \mathscr{S}) \to (\Omega, \mathcal{A})$ eine [[Funktion]].

Folgende Aussagen sind äquivalent
- $g$ ist $\mathscr{S}$-$\mathcal{A}$-[[Funktion A-S-messbar|messbar]]
- $\forall i \in I : (f_i \circ g)$ ist $\mathscr{S}$-$\mathcal{R}_i$-[[Funktion A-S-messbar|messbar]]