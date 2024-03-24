Sei $A \in \mathbb{R}^{m \times n}$ mit
- $U\Sigma V^T$ die [[Singulärwertzerlegung, SVD|SVD]] von $A$

Die $k$-te Iteration der *Krylov Raum Verfahrens* ist definiert als
- $v_k = \sigma_k = \Sigma_{kk}$ der $k$-te [[Singulärwerte|Singulärwert]]
- $V_k = \text{span}(v_1, \dots, v_k) \in \mathbb{R}^{n \times k}$ der $k$-te Krylov-Raum