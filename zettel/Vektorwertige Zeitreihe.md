Das Tupel der [[zettel/Zeitreihe|Zeitreihen]] $(X_t)_{t \in \mathbb{Z}}$ und $(Y_t)_{t \in \mathbb{Z}}$ heißt *Vektorwertige Zeitreihe*, falls
- $\exists f : \mathcal{L}(\Omega, \mathcal{A}, P)^p \to \mathcal{L}(\Omega, \mathcal{A}, P) \ \forall t \in \mathbb{Z} : X_t = f((Y_{t-s})_{s \in \{ 1, \dots, p \}})$
- $\exists g : \mathcal{L}(\Omega, \mathcal{A}, P)^q \to \mathcal{A}(\Omega, \mathcal{A}, P) \ \forall t \in \mathbb{Z} : Y_t = g((X_{t-s})_{s \in \{ 1, \dots, p \}})$

Schreibe

$$
	\left\{\begin{pmatrix}
		X_t \\
		Y_t
	\end{pmatrix}\right\}_{t \in \mathbb{Z}}
$$