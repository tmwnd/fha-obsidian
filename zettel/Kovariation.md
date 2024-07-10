Sei $(\tau_n)_{n \in \mathbb{N}}$ eine Folge von [[zettel/Partition|Partitionen]] von $[0, \overline{T}]$, $X$, $Y$ stetig mit
- $\forall t \in [0, \overline{T}] : \lim_{n \to \infty} \sum_{t_i \in \tau_n, t_i \le t} (X_{t_i} - X_{t_{i-1}})(Y_{t_i} - Y_{t_{i-1}})$ existiert

Die *Kovariation* $[X, Y]_t$ ist definiert als

$$
	[X, Y]_t := \lim_{n \to \infty} \sum_{t_i \in \tau_n, t_i \le t} (X_{t_i} - X_{t_{i-1}})(Y_{t_i} - Y_{t_{i-1}})
$$