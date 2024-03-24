Sei $X \in \mathbb{R}^{m \times n}$, $v^{(0)} \in \mathbb{R}^n$ mit
- $A = X^TX$
- $\| v^{(0)} \|_2 = 1$

die $i$-te Iteration des *Unterraum-Iteration-Verfahrens* ist definiert als
- $w^{(i+1)} = Av^{(i)} = X^TXv^{(i)}$
- $v^{(i+1)} = \frac{w^{(i+1)}}{\| w^{(i+1)} \|_2}$
- $\lambda^{(i+1)} = \langle v^{(i)}, w^{(i+1)} \rangle_2$

Es gilt
- $\lambda^{(i)} \to \lambda_1$ dem größten [[Eigenwert]] von $X^TX$
- $v^{(i)} \to v_1$ dem zum größten [[Eigenwert]] gehörendem [[Eigenvektor]] von $X^TX$
- $\sqrt{\lambda_i} = \sigma_1$ der größte [[Singulärwert]] von $A$
- Die Lösung von $Xv_1 = U\Sigma V^Tv_1 = \sigma_1u_1$ entspricht dem zum größten [[Singulärwert]] gehörenden [[Eigenvektor]] $u_1$

---

Sei $X \in \mathbb{R}^{m \times n}$, $(v_i^{(0)})_{i \in \{ 1, \dots, k \}} \in \mathbb{R}^n$ mit
- $A = X^TX$
- $V = (v_i^{(0)})_{i \in \{ 1, \dots, k \}}$
- $V$ [[orthogonale Matrizen|orthogonal]]

die $i$-te Iteration des *Unterraum-Iteration-Verfahrens* ist definiert als
- $\tilde{U}^{(i+1)} = XV^{(i)}$
- $W^{(i+1)} = AV^{(i)} = X^T\tilde{U}^{(i+1)}$
- $Q^{(i+1)}R^{(i+1)} = W^{(i+1)}$
- $V^{(i+1)} = Q^{(i+1)}$
- $\Lambda^{(i+1)} = \text{diag}(R^{(i+1)})$

Es gilt
- $\Lambda^{(i)} \to \text{diag}((\lambda_j)_{j \in \{ 1, \dots, k \}})$ die $k$ größten [[Eigenwert|Eigenwerte]] von $X^TX$
- $V^{(i)} \to (v_j)_{j \in \{ 1, \dots, k \}}$ die $k$-größten [[Eigenvektor|Eigenvektoren]] von $X^TX$
- $(\sqrt{\lambda_j})_{j \in \{ 1, \dots, k \}} = (\sigma_i)_{j \in \{ 1, \dots, k \}}$ die $k$-größten [[Singulärwert|Singulärwerte]] von $A$