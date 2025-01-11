Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$, $(z_i)_{i \in \{ 1, \dots q \}}$ die Nullstellen der AR-Polynoms $\phi$.

$(X_t)_{t \in \mathbb{Z}}$ heißt *kausal von $(\varepsilon_t)_{t \in \mathbb{Z}}$ abhängig*, falls
- $\forall i \in \{ 1, \dots, q \} : |z_i| \gt 1$

Es gilt
- $\exists (\psi_i)_{i \in \mathbb{N}_0}, \forall t \in \mathbb{Z} : X_t = \varepsilon_t + \sum_{i \in \mathbb{N}} \psi_i\varepsilon_{t-i}$