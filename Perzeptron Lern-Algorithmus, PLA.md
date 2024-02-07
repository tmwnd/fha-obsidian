Sei $X, y$ ein [[Datensatz]], $w_\text{final}$ der [[Perzeptron]]-Gewichtsvektor.

```py
def h(x, w):
	return np.sign(x @ w)
```

```py
def pla(X, y, w=None, t=0):
	if t == 0:
		X = np.concatenate([np.ones((X.shape[0], 1)), X], axis=1)
	
	if w is None:
		w = np.zeros(X.shape[1])
	
	y_pred = h(X, w)

	if all(y_pred == y):
		return w

	idx = (y_pred != y).argmax()
	return pla(X, y, w + y[idx]*X[idx], t+1)

w_final = pla(X, y)
```

---

Visualisierung im $\mathbb{R}^2$

```py
def g(x, w_final):
	return - (w_final[0] + x*w_final[1]) / w_final[2]
```

```py
plt.scatter(*X.T, c=y)

plt.plot((X[:, 0].min(), X[:, 0].max()), (g(X[:, 0].min(), w_final), g(X[:, 0].max(), w_final)))

plt.show()
```