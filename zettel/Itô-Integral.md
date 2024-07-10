Sei $X : [0, \overline{T}] \to \mathbb{R}$ stetig und mit stetiger [[zettel/Quadratische Variation|quadratischer Variation]], $F : \mathbb{R} \to \mathbb{R} \in C^2$.

Das *Itô-Integral* ist definiert als

$$
	\forall t \in [0, \overline{T}] : I_t := \int_0^t F'(X_s) dX_s := \lim_{n \to \infty} \sum_{t_i \in \tau_n, t_i \le t} F'(X_{t_{i-1}})(X_{t_i} - X_{t_{i-1}})
$$

Es gilt
- Das Itô-Integral ist stetig an der Obergrenze $t$