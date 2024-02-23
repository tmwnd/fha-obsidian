$\mathcal{R} \subseteq \mathcal{P}(\Omega)$ heißt *Ring* auf $\Omega$, falls
- $\emptyset \in \mathcal{R}$
- $A, B \in \mathcal{R} \implies A \cap B^C \in \mathcal{R}$
- $A, B \in \mathcal{R} \implies A \cup B \in \mathcal{R}$

---

Für eine beliebige Teilmenge $\mathcal{E} \subseteq \mathcal{P}(\Omega)$ ist

$$
	R(\mathcal{E}) = \bigcap_{\mathcal{R} \text{ Ring auf } \Omega, \ \mathcal{E} \subseteq \mathcal{R}} \mathcal{R}
$$

der von $\mathcal{E}$ erzeugte Ring.