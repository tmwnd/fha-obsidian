Sei $X, y$ ein [[Datensatz]], $w_\text{final}$ der [[Perzeptron]]-Gewichtsvektor.

```py
def h(x, w):
	return np.sign(x @ w)
```

```py
def pocket(X, y, T=1000, w=None):
	X = np.concatenate([np.ones((X.shape[0], 1)), X], axis=1)

	if w is None:
		w = np.zeros(X.shape[1])

	def pla(X, y, w):
		y_pred = h(X, w)

		if all(y_pred == y):
			return w
	
		idx = (y_pred != y).argmax()
		return w + y[idx]*X[idx]

	E_in = 1
	w_t = 
	w_final = w

	for t in range(T):
		w_t = pla(X, y, w_t)

		E_in_t = (y == h(X, w_t)).mean()

		if E_in_t < E_in:
			E_in = E_in_t
			w_final = w_t

	return w_final

w_final = pocket(X, y)
```