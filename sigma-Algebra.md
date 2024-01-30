$\mathcal{A} \subseteq \Omega$ heißt *$\sigma$-Algebra* auf $\Omega$, falls
- $\Omega \in \mathcal{A}$
- $A \in \mathcal{A} \implies A^C \in \mathcal{A}$
- $A_n \in A, n \in \mathbb{N}: \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$

---

Für eine beliebige Teilmenge $\mathcal{C} \subseteq \mathcal{P}(\Omega)$ ist

$$
	\sigma(\mathcal{C}) = \bigcap_{\mathcal{A} \ \sigma\text{-Algebra auf } \Omega, \ \mathcal{C} \subseteq \mathcal{A}} \mathcal{A}
$$

die von $\mathcal{C}$ erzeugte $\sigma$-Algebra.