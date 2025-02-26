Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$, $(z_i)_{i \in \{ 1, \dots q \}}$ die Nullstellen der MA-Polynoms $\vartheta$.

$(X_t)_{t \in \mathbb{Z}}$ heißt *invertierbar bzgl. $(\varepsilon_t)_{t \in \mathbb{Z}}$*, falls
- $\forall i \in \{ 1, \dots, q \} : |z_i| \gt 1$

Es gilt
- $\forall t \in \mathbb{Z} : \varepsilon_t = \sum_{i \in \mathbb{Z}} \theta B^i\left( \sum_{j \in \mathbb{Z}} \phi_j B^j(X_t) \right)$
  
  mit
  - $\theta$ der Inverse $\vartheta$
- $\exists (\lambda_i)_{i \in \mathbb{N}_0}, \forall t \in \mathbb{Z} : \varepsilon = \sum_{i \in \mathbb{N}_0} \lambda_i B^i(X_t)$