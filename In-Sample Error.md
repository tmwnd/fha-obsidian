Sei $X, y$ ein [[Datensatz]], $N = |X|$, $h$ eine [[Hypothese]].

Der *In-Sample Error* von $h$ ist definiert als

$$
	E_\text{in}(h) = \frac{1}{N} \sum_{i=1}^N \textlbrackdbl h(x_i) \ne y_i \textrbrackdbl
$$

---

```py
def h(x, w):
	return np.sign(x @ w)
```

```py
(h(np.concatenate([np.ones((X.shape[0], 1)), X], axis=1), w_final) != y).mean()
```

---

Sei $X, y$ ein [[Datensatz]], $N = |\mathcal{D}|$, $h$ eine [[Hypothese]].

Der *In-Sample Error* von $h$ ist definiert als

$$
	E_\text{in}(h) = \frac{1}{N} \sum_{i=1}^N (h(x_i) - y)^2
$$

---

```py
def h(x, w):
	return np.sign(x @ w)
```

```py
(y - h(np.concatenate([np.ones((X.shape[0], 1)), X], axis=1), w_final))**2.mean()
```