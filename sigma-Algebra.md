$\mathcal{A} \subseteq \mathcal{P}(\Omega)$ heißt *$\sigma$-Algebra* auf $\Omega$, falls
- $\Omega \in \mathcal{A}$
- $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
- $\forall (A_n)_{n \in \mathbb{N}} \in \mathcal{A}: \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$

---

Für eine beliebige Teilmenge $\mathcal{E} \subseteq \mathcal{P}(\Omega)$ ist

$$
	\sigma(\mathcal{E}) = \bigcap_{\mathcal{A} \ \sigma\text{-Algebra auf } \Omega, \ \mathcal{E} \subseteq \mathcal{A}} \mathcal{A}
$$

die von $\mathcal{E}$ erzeugte $\sigma$-Algebra.