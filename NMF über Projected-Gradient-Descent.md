Sei $V \in \mathbb{R}_+^{m \times n}$ [[sparse]].

Finde eine Lösung der [[NMF, Nonnegative-Matrix-Factorisation|NFM]] $V = WH$ über über [[SVD mit Projected Gradient Descent]]  mit
- der [[Loss-Funktion]] $l(W, H)$ definiert als

$$
	l(W, H) = \| V - WH \|_\text{Fro}^2
$$

und der Projektion
- $\forall i, j : \tilde{a}_{ij} = \begin{cases} a_{ij}, & a_{ij} \ge 0 \\ 0, & a_{ij} \lt 0 \end{cases}$
- $\prod(A) = (\tilde{a}_{ij})_{ij}$