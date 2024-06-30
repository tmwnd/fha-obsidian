Sei $\Omega \ne \emptyset$, $\mathcal{A}, \mathcal{B} \subseteq \mathcal{P}(\Omega)$ mit
- $\mathcal{A} = (A_i)_{i \in I}$
- $\mathcal{B} = (B_j)_{j \in J}$

Es gilt
- *Komplementbildung*
	- $(A^\complement)^\complement = A$
	- $\Omega^\complement = \emptyset$
	- $\emptyset^\complement = \Omega$
	- $A \subseteq B \iff B^\complement \subseteq A^\complement$
- *De Morgansche Gesetze*

$$
	\left( \bigcup_{i \in I} A_i \right)^\complement = \bigcap_{i \in I} A_i^\complement
$$

$$
	\left( \bigcap_{i \in I} A_i \right)^\complement = \bigcup_{i \in I} A_i^\complement
$$

- *Distributivgesetz*

$$
	\left( \bigcup_{i \in I} A_i \right) \bigcap \left( \bigcup_{j \in J} A_j \right) = \bigcup_{i \in I} \bigcup_{j \in J} (A_i \cap B_j)
$$

$$
	\left( \bigcap_{i \in I} A_i \right) \bigcup \left( \bigcap_{j \in J} A_j \right) = \bigcap_{i \in I} \bigcap_{j \in J} (A_i \cap B_j)
$$