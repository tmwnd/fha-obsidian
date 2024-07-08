Sei $X : [0, \overline{T}] \to \mathbb{R}$, $(\tau_n)_{n \in \mathbb{N}}$ [[zettel/Partition|Partitionen]] mit
- $\lim_{n \to \infty} |\tau_n| = 0$

Die *quadratische Variation* von $X$ bzgl. $\tau_n$ ist definiert als

$$
	\forall t \in [0, \overline{T}], n \in \mathbb{N} : V_t^2(X, \tau_n) := \sum_{t_i \in \tau_n, t_i \lt t} (X(t_i) - X(t_{i-1}))^2
$$

und $X$ ist von quadratischer Variation $[X]_t$, falls

$$
	\forall t \in [0, \overline{T}] : [X]_t := \lim_{n \to \infty} V_t^2(X, \tau_n)
$$

Es gilt
- $[X]_t$ ist nicht von $(\tau_n)_{n \in \mathbb{N}}$ abhängig