Sei $l : V \to W$ eine [[zettel/Lineare Abbildung|Lineare Abbildung]] mit der zugehörigen [[zettel/Matrix/Symmetrie|symmetrischen]] Matrix $A \in \mathbb{R}^{n \times n}$.

Es gilt
- Es gibt $n$ reelle Eigenwerte $(\lambda_i)_{i \in \{ 1, \dots, n \}}$
- Es gibt $n$ paarweise orthonormale Eigenvektoren $(v_i)_{i \in \{ 1, \dots, n \}}$

und

$$
	\forall x \in \mathbb{R}^n \ \exists a \in \mathbb{R}^n : x = \sum_{i=1}^n a_iv_i
$$

bzw.

$$
	\forall x \in \mathbb{R}^n \ \exists a \in \mathbb{R}^n : Ax = \sum_{i=1}^n a_iAv_i = \sum_{i=1}^n a_i \lambda_i v_i
$$

Somit eignet sich als [[zettel/Basis|Basis]]

$$
	A \to \tilde{A} := \begin{pmatrix}
		\lambda_1 && \\
		& \ddots & \\
		&& \lambda_3
	\end{pmatrix}
$$