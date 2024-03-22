Sei $\mathcal{R}$ ein [[Ring]] auf $\Omega$ und $\mu : \mathcal{R} \to \overline{\mathbb{R}}_+$ ein [[Maß|endlich-additives]] [[Maß]], dann gilt
- Isotonie:
	- $A, B \in \mathcal{R}, A \subseteq B \implies \mu(A) \le \mu(B)$
- Subtraktivität:
	- $A, B \in \mathcal{R}, A \subseteq B, \mu(A) \lt \infty \implies \mu(B \cap A^\complement) = \mu(B) - \mu(A)$
- Siebformel:
	- $A_1, \dots, A_n \in \mathcal{R}$ mit $\mu(\bigcup_{k=1}^n) A_k \lt \infty, n \in \mathbb{N} \implies$

$$
	\mu\left( \bigcup_{k=1}^n A_k \right) = \sum_{k=1}^n \left( (-1)^{k-1} \cdot \sum_{I \subseteq \{ 1, \dots, n \}, |I| = k} \mu\left( \bigcap_{i \in I} A_i \right) \right)
$$

$$
	\mu\left( \bigcap_{k=1}^n A_k \right) = \sum_{k=1}^n \left( (-1)^{k-1} \cdot \sum_{I \subseteq \{ 1, \dots, n \}, |I| = k} \mu\left( \bigcup_{i \in I} A_i \right) \right)
$$

- Subadditivität
	- $A_1, \dots, A_n \in \mathcal{R} \implies$

$$
	\mu\left( \bigcup_{i=1}^n A_i \right) \le \sum_{i=1}^n \mu(A_i)
$$

- Sub-$\sigma$-Additivität:
	- $\mu$ $\sigma$-additiv, $(A_n)_{n \in \mathbb{N}} \in \mathcal{R}$ mit $\bigcup_{n \in \mathbb{N}} A_n \in \mathcal{R} \implies$

$$
	\mu\left( \bigcup_{n \in \mathbb{N}} A_n \right) \le \sum_{n=1}^\infty \mu(A_i)
$$

- p. d. $(A_n)_{n \in \mathbb{N}} \in \mathcal{R}$ mit $\bigcup_{n \in \mathbb{N}} A_n \in \mathcal{R} \implies$

$$
	\mu\left( \bigcup_{n \in \mathbb{N}} A_n \right) = \sum_{n=1}^\infty \mu(A_n)
$$