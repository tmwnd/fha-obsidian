Sei $(X_n)_{n \in \mathbb{N}_0}$ eine [[zettel/Markov-Kette|Markov-Kette]], $h : \left( (\mathbb{R}^p)^{\mathbb{N}_0}, (\mathcal{L}^p)^{\mathbb{N}_0} \right) \to (\mathbb{R}, \mathcal{L})$ beschränkt mit
- $\forall n \in \mathbb{N} : \mathcal{F}_n := \sigma(X_0, \dots, X_n)$
- $\tau : \Omega \to \overline{\mathbb{N}}_0$ eine [[zettel/Stoppzeit|Stoppzeit]] bezüglich $(\mathcal{F}_n)_{n \in \mathbb{N}}$
- $W := (X_{\tau + k})_{k \in \mathbb{N}_0}$ ein nach-$\tau$-Prozess
- $F_\tau$ eine [[zettel/σ-Algebra|σ-Algebra]] der $\tau$-Vergangenheit

Die *starke Markoveigenschaft* ist erfüllt, falls

$$
	\text{E}[h(W) \mid \mathcal{F}_\tau] = \text{E}_{X_\tau}[h((X_n)_{n \in \mathbb{N}_0})]
$$