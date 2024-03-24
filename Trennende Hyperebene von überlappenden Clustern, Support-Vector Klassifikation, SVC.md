Seien $(x_i, y_i)_{i \in \{ 1, \dots, n \}}$ Daten-Paare, $w \in \mathbb{R}^{m+1}$, $H(w)$ eine [[Hyperebene]], $g(x, w)$ die Funktion aus $H(w)$, $M \in \mathbb{R}$ der  Mindestabstand aller Punkte $x_i$ zu $H(w)$, $\xi$ der erlaubte relative Fehler, $C \ge 0$ die Gewichtung von $\xi$ mit
- $\forall i \in \{ 1, \dots, n \} : x_i \in \mathbb{R}^n$
- $\forall i \in \{ 1, \dots, n \} : y_i \in \{ -1, 1 \}$
- $\forall i \in \{ 1, \dots, n \} : y_ig(x_i, w) \ge M \gt 0$
- $\forall i \in \{ 1, \dots, n \} : \xi_i \ge 0$

Es gilt
- $\not\exists H(w) : \forall i \in \{ 1, \dots, n \} : y_i = \text{sign}(g(x_i, w))$ bzw. es lässt sich keine [[Optimal trennende Hyperebene von nicht-überlappenden Clustern, Support-Vector Klassifikation, SVC|optimal trennende Hyperebenene]] finden

Bestimme
- $M$ maximal

mit

$$
	M = \max_{\| v \|_2 = 1} M(w), \quad \forall i \in \{ 1, \dots, n \} : y_ig(x_i, w) \ge M(1 - \xi_i) \gt 0
$$

Es gilt
- $\forall i \in \{ 1, \dots, n \} : \xi_i = 0 \implies d(M(w), y_ix_i) \ge M$
- $\forall i \in \{ 1, \dots, n \} : \xi_i \in (0, 1) \implies 0 \lt d(M(w), y_ix_i) \le M$
- $\forall i \in \{ 1, \dots, n \} : \xi_i \gt 1 \implies d(M(w), y_ix_i) \lt 0$

Die Anzahl der Missklassifikationen lässt sich über $K \in \mathbb{N}$ beschränken mit

$$
	\sum_{i=1}^n \xi_i \le K
$$

Bestimme $v \in \mathbb{R}^m$, $v_0 \in \mathbb{R}$ mit
- $w = (v, v_0)$
- $\| v \|_2 = 1$
- $M$ maximal
- $\forall i \in \{ 1, \dots, n \} : y_ig(x_i, w) \ge M(1 - \xi_i) \gt 0$

mit

$$
	w = (v, v_0) = \min_{v \ne 0, v_0, \xi} \frac{1}{2} \| v \|_2^2 + C \sum_{i=1}^n \xi_i, \quad \forall i \in \{ 1, \dots, n \} : y_i(v^Tx_i + v_0) \ge 1 - \xi_i
$$

und
- $C \to 0$ Fehler dürfen beliebig groß werden
- $C \to \infty$ Summe der Fehler muss verschwinden, Problem eventuell nicht mehr lösbar

Das optimale $\hat{w}$ kann durch die Lösung des [[restringiertes Optimierungsproblem|restringiertes Optimierungsproblems]] $L(v, v_0, \alpha)$ über [[Karush-Kuhn-Tucker-Bedingungen, KKT|KKT]] bestimmt werden.

$$
	L(v, v_0, \xi, \alpha, \beta) = \left( \frac{1}{2} \| v \|_2^2 + C \sum_{i=1}^n \xi_i \right) - \sum_{i=1}^n \alpha_i\left(\left( y_i \sum_{j=1}^m v_jx_{ij} + v_0 \right) - 1 + \xi_i \right)
$$

mit
- $\forall i \in \{ 1, \dots, n \} : \alpha_i \in \mathbb{R}$
- $\forall i \in \{ 1, \dots, n \} : \beta_i \in \mathbb{R}$

Es gilt
- $\partial_{v_0} L(v, v_0, \alpha) = - \sum_{i=1}^n \alpha_iy_i$
- $\forall k \in \{ 1, \dots, m \} : \partial_{v_k} L(v, v_0, \alpha) = v_k - \sum_{i=1}^n \alpha_iy_ix_{ik}$
- $\forall l \in \{ 1, \dots, n \} : \partial_{\xi_k} L(v, v_0, \alpha) = C - \alpha_i - \beta_i$

Für optimale Parameter $\hat{v}$, $\hat{v}_0$, $\hat{\xi}$ muss also gelten
- $0 = \sum_{i=1}^n \hat{\alpha}_iy_i$
- $\hat{v} = \sum_{i=1}^n \hat{\alpha}_iy_ix_i$
- $\forall l \in \{ 1, \dots, n \} : \hat{\alpha}_l = C - \hat{\beta}_l$
- $\forall i \in \{ 1, \dots, n \} : \hat{\alpha}_i \ge 0$
- $\forall i \in \{ 1, \dots, n \} : y_i(\hat{v}^Tx_i + \hat{v}_0) - 1 + \hat{\xi}_i \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \hat{\alpha}(y_i(\hat{v}^Tx_i + \hat{v}_0) - 1 + \hat{\xi}_i) - 1) = 0$
- $\forall i \in \{ 1, \dots, n \} : \hat{\beta}_i \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \hat{\xi}_i \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \hat{\beta}_i\hat{\xi}_i = 0$

und
- $\forall i \in \{ 1, \dots, n \} : y_i(\hat{v}^Tx_i + \hat{v}_0) - 1 + \hat{\xi}_i \ne 0$ $\implies$ $x_i$, $y_i$ hat keinen Einfluss auf $\hat{v}$
- $\forall i \in \{ 1, \dots, n \} : y_i(\hat{v}^Tx_i + \hat{v}_0) - 1 + \hat{\xi}_i = 0$ $\implies$ $x_i$, $y_i$ heißt *Stützpunkt* bzw. *Support-Punkt* von $H(\hat{v})$