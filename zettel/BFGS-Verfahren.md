Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Datenpaare, $w^{(0)} \in \mathbb{R}^n$, $B^{(0)} \in \mathbb{R}^{n \times n}$, $l$ eine zweifach differenzierbare [[zettel/Loss-Funktion|Loss-Funktion]], $\gamma^{(k)} \ge 0$ die durch Liniensuche bestimmte Schrittlänge, $p^{(k)}$ die Suchrichtung mit
- $l''$ [[zettel/Matrix/Singularität|singulär]]

Die $k$-te Iteration von *BFGS* ist definiert als
- $B^{(k)}p^{(k)} = -l'(w^{(k)})$
- $w^{(k+1)} = w^{(k)} + \gamma^{(k)}p^{(k)}$
- $y^{(k)} = l'(w^{(k+1)}) - l'(w^{(k)})$
- $h^{(k)} = w^{(k+1)} - w^{(k)}$
- $u^{(k)} = B^{(k)}h^{(k)}$
- $B^{(k+1)} = B^{(k)} + \frac{y^{(k)}y^{(k)^T}}{h^{(k)^T}y^{(k)}} - \frac{u^{(k)}u^{(k)^T}}{h^{(k)^T}u^{k}}$

---

BFGS ist ein Quasi-[[zettel/Newton-Verfahren|Newton-Verfahren]]