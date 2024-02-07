Sei $X, y$ ein [[Datensatz]] mit
- $w \in \mathbb{R}^{d+1}$ einem Gewichtsvektor
- $X = \{ 1, x_1, \dots, x_d \}$

Ein *Perzeptron* $h$ ist definiert als

$$
	h(x) = \text{sign}(w^Tx) = y
$$

---

```py
def h(x, w):
	return np.sign(x @ w)
```