Sei $w$ ein Gewichtsvektor, $X$ ein [[Datensatz]], $x \in X$

Ein *Lineares Modell* hat die Form

$$
	\theta(w^Tx)
$$

mit

- Klassifikation
	- $\theta : \mathbb{R} \to \{ 0, 1 \}$
	- $\theta(\cdot) = \text{sign}(\cdot)$
	- z. B. [[Perzeptron Lern-Algorithmus, PLA|PLA]], [[Pocket Algorithmus]]
- Regression
	- $\theta : \mathbb{R} \to \mathbb{R}$
	- $\theta(\cdot) = \text{id}(\cdot) = \cdot$
	- z. B. [[Lineare Regression]]
- Logistische Regression
	- $\theta : \mathbb{R} \to [0, 1]$
	- $\theta(\cdot) = \frac{e^\cdot}{1+e^\cdot}$