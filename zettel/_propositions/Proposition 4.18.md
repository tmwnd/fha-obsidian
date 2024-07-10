Sei $X : [0, \overline{T}]$ stetig und von endlicher [[zettel/Erste Variation|erster Variation]], $f : \mathbb{R} \to \mathbb{R} \in C^1$, $(\tau_n)_{n \in \mathbb{N}}$ eine Folge von [[zettel/Partition|Partitionen]] von $[0, \overline{T}]$ mit
- $\lim_{n \to \infty} |\tau_n| = 0$

Es existiert

$$
	\int_0^t f'(X_s) dX_s := \lim_{n \to \infty} \sum_{t_i \in \tau_n, t_i \le t} f'(X_{t_{i-1}})(X_{t_i} - X_{t_{i-1}})
$$

Es gilt die Kettenregel

$$
	f(X_t) = f(X_0) + \int_0^t f'(X_s) dX_s
$$