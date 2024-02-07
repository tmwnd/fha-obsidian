Sei $f$, eine [[Target-Function]], $X$ eine Datenmatrix, $y$ ein Vektor mit
- $\forall i \in \{ 1, \dots, |X| \} : f(X_i) = y_i$

Ein *Datensatz* $\mathcal{D}$ ist definiert als

$$
	\mathcal{D} = (X_i, y_i)_{i \in \{ 1, \dots, |X| \}}
$$

---

Sei $X$ ein Datensatz.

```py
X.shape
```