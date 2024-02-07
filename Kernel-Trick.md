Sei $\Phi$ eine [[Nichtlineare Transformation]], $g$ eine [[Hypothese]] einer [[Support Vector Machines, SVMs|SVM]].

Ersetze die [[Hypothese]] $g$ durch

$$
	g(x) = \text{sign}\left( \sum_{n=1}^N \alpha_ny_n\underbrace{\Phi(x_n)^T\Phi(x)}_{K(x_n, x)} + b \right)
$$

mit der *Kernel-Funktion*

$$
	K(x_i, x_j) = \Phi(x_i)^T\Phi(x_j)
$$

![[Polynomieller Kernel]]

![[Gaußscher RBF Kernel]]