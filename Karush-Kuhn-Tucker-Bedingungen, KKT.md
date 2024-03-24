$\hat{v}, \hat{v}_0$ sind optimale Lösungen eines [[restringiertes Optimierungsproblem|restringiertes Optimierungsproblems]], falls $(\hat{\alpha}_i)_{i \in \{ 1, \dots, n \}} \ge 0$ existiert mit
- $\forall k \in \{ 1, \dots, m \} : \partial_{v_k} L(\hat{v}, \hat{v}_0, \hat{a}) = 0$
- $\forall i \in \{ 1, \dots, n \} : y_i(\hat{v}^Tx_i + \hat{v}_0) - 1 \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \hat{\alpha}_i(y_i(\hat{v}^Tx_i + \hat{v}_0) - 1) = 0$ (Komplementaritätsbedingung)