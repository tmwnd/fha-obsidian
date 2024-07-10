Sei $f : \mathbb{R} \to \mathbb{R} \in C^1$, $X : \mathbb{R}_+ \to \mathbb{R}$ mit
- $\dot{X} := \frac{\partial}{\partial t} X(t)$

Es gilt

$$
	\forall t \in \mathbb{R}_+ : f(X(t)) - f(X(0)) = \int_0^t f'(X_s) dX_s := \int_0^t f'(X(s)) \dot{X}(s) ds
$$