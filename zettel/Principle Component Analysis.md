Sei $X = (x_1, \dots, x_n) \in \mathbb{R}^{m \times n}$ mit
- $X$ [[zettel/Zentrierter Datensatz|zentriert]]
- $U\Sigma V^T$ die [[zettel/Singulärwertzerlegung|SVD]] von $X$
- $s \in \mathbb{R}$

Suche
- $u \in \mathbb{R}^m$
- $g(s) = su$ eine Gerade

mit
- der Varianz $V_1(u)$ maximal und definiert als

$$
	V_1(u) = \frac{1}{n-1} \sum_{j=1}^n \langle x_j, u \rangle_2^2 = \frac{1}{n-1} \langle X^Tu, X^Tu \rangle_2 = \frac{1}{n-1} \| X^Tu \|_2^2 = \frac{1}{n-1} \| V\Sigma^T\underbrace{U^Tu}_z \| = \frac{1}{n-1} \| \Sigma^Tz \|_2^2 = \frac{1}{n-1} \sum_{i=1}^r (\sigma_i z_i)^2
$$

Sei
- $f(z) = V_1(z)$ [[zettel/Funktion/Konvexität|konvex]]
- $g(z) = \| z \|_2^2 - 1$ [[zettel/Funktion/Konvexität|konvex]]
- $L(z, \lambda) = f(z) - \lambda g(z)$ die zu lösende [[zettel/Lagrange-Funktion|Lagrange-Funktion]]

Es gilt
- $\partial_z L(z, \lambda) = 2(\Sigma\Sigma^Tz - \lambda z)$
- $\partial_\lambda L(z, \lambda) = \| z \|_2^2 - 1$

Sei $\hat{z}$ eine Maximalstelle.

Es gilt
- $\exists \hat{\lambda} \in \mathbb{R} : \partial_z L(\hat{z}, \hat{\lambda}) = \partial_\lambda L(\hat{z}, \hat{\lambda}) = 0$
- $\| z \|_2 = 1$
- $\Sigma\Sigma^T\hat{z} = \hat{\lambda}\hat{z}$ $\implies$ $\hat{z}$ sind die [[zettel/Eigenvektor|Eigenvektoren]] bzw. $\hat{\lambda}$ sind die [[zettel/Eigenwert|Eigenwerte]] von $\Sigma\Sigma^T$

Da

$$
	\Sigma\Sigma^T = \begin{pmatrix}
		\sigma_1^2 \\
		& \ddots \\
		&& \sigma_r^2 \\
		&&& 0 \\
		&&&& \ddots \\
		&&&&& 0
	\end{pmatrix}
$$

gilt offensichtlich
- $\hat{z} = e_i$ der $i$-te [[zettel/Einheitsvektor|Einheitsvektor]]
- $\hat{\lambda}_i = \begin{cases} \sigma_i^2, & i \in \{ 1, \dots, r \} \\ 0, & i \gt r \end{cases}$
- $f(\hat{z}) = \| \Sigma^T e_i \|_2^2 = \sigma_i^2 \implies \arg\max_i f(\hat{z}_i) = 1$

Für unser Ausgangsproblem erhalten wir
- $\hat{u} = Ue_i = u_i$ den $i$-ten [[zettel/Singulärvektor|Singulärvektor]] von $X$ als Richtung mit der $i$-t größten Varianz
- $V_1(\hat{u}) = V_1(u_i) = \frac{\sigma_i^2}{n-1} = \frac{\lambda_i}{n-1}$

Die $u_j$ heißen *Hauptkomponenten* bzw. *Karhunen-Loeve-Richtungen* zum Datensatz $X$.

Projiziere in $r$ Schritten iterativ $X$ auf $u_i^\perp$ mit
- $\hat{X} = \Sigma_rV:r^T = U_r^TX \in \mathbb{R}^{r \times n}$
- $V(X) = \sum_{i=1}^m V(X_i) = \sum_{i=1}^r V(\tilde{X}_i) = V(\tilde{X})$

Sei $\varepsilon \gt 0$ der maximale Informationsverlust.

Suche
- $k \ll m$

mit

$$
	\sum_{i=1}^k V(\tilde{X}_i) = \frac{\sum_{i=1}^k \sigma_i^2}{n-1} \ge V(X) - \varepsilon
$$

---

Vorteile:
- Produkte über $\tilde{X}$ deutlich günstiger als über $X$