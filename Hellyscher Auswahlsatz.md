Sei $(F_n)_{n \in \mathbb{N}}$ eine Folge $d$-dimensionaler [[Verteilungsfunktion|Verteilungsfunktionen]] mit
- $\forall n \in \mathbb{R} : F_n : \mathbb{R}^d \to \mathbb{R}$

Es existiert eine Teilfolge $(f_{n_k})_{k \in \mathbb{N}}$ und eine [[Funktion]] $F: \mathbb{R}^d \to \mathbb{R}$ mit
- $0 \le F \le 1$
- $F$ ist stetig von oben
- $\forall a, b \in \mathbb{R}^d:$
  
  $$
	  \Delta_S F = \sum_{(\varepsilon_1, \dots, \varepsilon_d) \in \{ 0, 1 \}^d} (-1)^{\sum_{i=1}^d \varepsilon_i} F\left( \sum_{i = 1}^d \varepsilon_i a_i + (1 - \varepsilon_i) b_i \right)
  $$
  
  mit $S = \prod_{i \in \{ 1, \dots, d \}} (a_i, b_i]$
- $\forall x \in C(F) = \{ \text{ Stetigkeitsstellen von F } \}$ ist
  
  $$
	  \lim_{k \to \infty} F_{n_k}(x) = F(x)
  $$