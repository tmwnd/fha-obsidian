Sei $(W_t)_{t \in \mathbb{R}_0}$ eine [[zettel/Wiener Prozess|Wiener Prozess]], $\mu \in \mathbb{R}$, $\sigma, S_0 \in \mathbb{R}_+$ mit
- $\forall t \in \mathbb{R}_0 : X_t := \sigma W_t$
- $\forall t \in \mathbb{R}_0 : Y_t := (\mu - \frac{1}{2}\sigma^2)t$
- $[X]_t = [\sigma W]_t = \sigma^2[W]_t = \sigma^2t$
- $[Y]_t = \left[ \left( \mu - \frac{1}{2}\sigma^2 \right) \right]_t = 0$
- $[X, Y]_t = \frac{1}{2}([X + Y]_t - [X]_t - [Y]_t) = \frac{1}{2}([X_t] - [X]_t - 0) = 0$
- $\forall x, y \in \mathbb{R} : F(x, y) := S:0e^{x+y}$
- $F_X = F_Y = F_{XX} = F$

Es gilt

$$
	S_t = S_0 + \int_0^t F(X_s, Y_s) \underbrace{dX_s}_{\sigma dW_s} + \int_0^t F(X_s, Y_s) \underbrace{dY_s}_{(\mu - \frac{1}{2}\sigma^2)ds} + \frac{1}{2} \int_0^t F(X_s, Y_s) \underbrace{d[X]_s}_{\sigma^2ds} = S_0 + \int_0^t \sigma S_s dWs + \int_0^t \mu S_s ds
$$

Schreibe
- $dS_t = \mu S_t dt + \sigma S_t dW_t$