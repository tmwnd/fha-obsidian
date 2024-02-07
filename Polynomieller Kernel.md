Sei $Q, \gamma, \zeta \in \mathbb{R}$.

$K_\text{poly}$ heißt *polynominieller Kernel* und ist definiert als

$$
	K_\text{poly}(x_i, x_j) = (\zeta + \gamma x_i^Tx_j)^Q
$$

Es gilt $K_\text{poly}$ mit
- $Q = 1$, $\gamma = 1$, $\zeta = 0$ $\implies$ $K_\text{linear}(x_i, x_j) = x_i^Tx_j$, $\Phi(x) = x$
- $Q = 2$ $\implies$ $\Phi(x) = (\zeta, \sqrt{2\gamma\zeta} \cdot x_1, \sqrt{2\gamma\zeta} \cdot x_2, \dots, \sqrt{2\gamma\zeta} \cdot x_d, \gamma\cdot x_1^2, \gamma\cdot x_1x_2, \dots, \gamma\cdot x_d^2)$