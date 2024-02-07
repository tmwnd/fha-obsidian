Sei $(x_1, \dots, x_N) = X$ ein [[Datensatz]].

Die *nichtlineare Transformation* $Z$ ist definiert als
- $Z = (z_i, \dots, z_N)$

mit
- $x \in X$
- $z \in Z$
- $d, m \in \mathbb{N}$
- $\Phi : \mathbb{R}^d \to \mathbb{R}^q$ z. B.
	- $z = \Phi_Q(x) = ((x^i)_{i \in \{ 0, \dots, Q \}})$ mit $d=1$
	- $z = \Phi_Q(x) = (1, x_1^Q, \dots, x_d^Q)$
	- $z = \Phi_Q(x) = (1, x_1, x_2, x_1^2, x_1x_2, x_2^2, \dots)$
	- $z = \Phi(x) = (1, L_1(x), \dots, L_q(x))$ mit $L$ die ersten $q$ [[Legendre-Polynome]]

---

```py
# \Phi_Q(x) = ((x^i)_{i \in \{ 0, \dots, Q \}})
def phi(X, Q=5):
	return np.concatenate([(X**i).reshape(-1, 1) for i in range(Q)], axis=1)
```

```py
# \Phi_Q(x) = (1, x_1^Q, \dots, x_d^Q)
def phi(X, Q=2):
	return np.concatenate([np.ones((X.shape[1], 1)), *[(X[:, i]**2).reshape(-1, 1) for i in range(X.shape[0])]], axis=1)
```

```py
# \Phi_Q(x) = (1, x_1, x_2, x_1^2, x_1x_2, x_2^2, \dots)
def phi(X, Q=3):
	idx = []
	pot = []
	
	for n in range(Q+1):
		idx.extend([[0]] + [[0, 1]]*(n-1) + [[1]]*(n >= 1))
		pot.extend([[n]] + [[n-k, k] for k in range(1, n)] + [[n]]*(n >= 1))

	return np.concatenate([(X[:, i]**p).reshape(-1, len(i)).prod(axis=1).reshape(-1, 1) for i, p, in zip(idx, pot)], axis=1)

phi(X)
```
