Sei $X : [0, \overline{T}] \to \mathbb{R}$ stetig und mit stetiger [[zettel/Quadratische Variation|quadratischer Variation]], $F : \mathbb{R} \to \mathbb{R} \in C^2$.

Die *Itô-Formel* ist definiert als

$$
	\forall t \in [0, \overline{T}] : F(X_t) = F(X_0) + \int_0^t F'(X_s) dX_s + \frac{1}{2} \int F''(X_s) d[X]_s
$$

Schreibe
- $dF(X_t) := F'(X_t)dX_t + \frac{1}{2}F''(X_t)d[X]_t$

Es gilt
- Falls $X$ von endlicher [[zettel/Erste Variation|erster Variation]], ist  $\frac{1}{2} \int F''(X_s) d[X]_s = 0$