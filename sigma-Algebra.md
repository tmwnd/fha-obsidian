$\mathcal{A} \subseteq \mathcal{P}(\Omega)$ heißt *$\sigma$-Algebra* auf $\Omega$, falls
- $\Omega \in \mathcal{A}$
- $A \in \mathcal{A} \implies A^C \in \mathcal{A}$
- $(A_n)_{n \in \mathbb{N}} \in \mathcal{A}: \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$

---

Für eine beliebige Teilmenge $\mathcal{C} \subseteq \mathcal{P}(\Omega)$ ist

$$
	\sigma(\mathcal{C}) = \bigcap_{\mathcal{A} \ \sigma\text{-Algebra auf } \Omega, \ \mathcal{C} \subseteq \mathcal{A}} \mathcal{A}
$$

die von $\mathcal{C}$ erzeugte $\sigma$-Algebra.