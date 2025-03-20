Seien $(b_i)_{i \in \{ 1, \dots, n \}}$, $(\tilde{b}_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Basis|Basen]] für den Vektorraum $V$ mit der [[zettel/Basistransformation|Basistransformation]] $s : V \to V$ bzw. der [[zettel/Basistransformation|Basistransformationmatrix]] $S$ und analog $(c_i)_{i \in \{ 1, \dots, m \}}$, $(\tilde{c}_i)_{i \in \{ 1, \dots, m \}}$ [[zettel/Basis|Basen]] für den Vektorraum $W$ mit der [[zettel/Basistransformation|Basistransformation]] $t : W \to W$ bzw. der [[zettel/Basistransformation|Basistransformationmatrix]] $T$, $l : V \to W$ eine [[zettel/Lineare Abbildung|Lineare Abbildung]] mit der Matrix $A$ mit
- $\forall i \in \{ 1, \dots, n \} : b_i = s(\tilde{b}_i)$
- $\forall i \in \{ 1, \dots, m \} : c_i = t(\tilde{c}_i)$

Es gilt

$$
	\forall v, \tilde{v} \in V, w, \tilde{w} \in W, w = l(v) : \tilde{w} = Tw = TAv = TAS\tilde{v} = \tilde{A}\tilde{v}
$$

bzw.

$$
	\tilde{A} := TAS
$$