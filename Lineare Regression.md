Sei $(x_1, \dots, x_N) = X$, $y$ ein [[Datensatz]] mit

$$
	X = \begin{pmatrix}
		1 & \textemdash \ x_1^T \ \textemdash \\
		& \vdots \\
		1 & \textemdash \ x_N^T \ \textemdash
	\end{pmatrix}
$$

$$
	X^\textdagger = (X^TX)^{-1}X^T
$$

$$
	w_\text{min}=X^\textdagger y
$$

---

```py
def lin_reg(X, y):
	X = np.concatenate([np.ones((X.shape[0], 1)), X], axis=1)
	X_inv = np.linalg.pinv(X)

	return X_inv @ y

w_lin = lin_reg(X, y)
```