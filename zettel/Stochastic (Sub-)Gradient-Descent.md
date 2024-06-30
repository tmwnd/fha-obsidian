Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Datenpaare, $l$ eine nicht-differenzierbare [[zettel/Loss-Funktion|Loss-Funktion]], $w^{(0)} \in \mathbb{R}^n$, $\gamma^{(k)} \ge 0$ die Schrittlänge.

Die $k$-te Iteration des *(Sub-)Gradient-Descent-Verfahrens* ist definiert als

$$
	w^{(k+1)} = w^{(k)} - \gamma^{(k)}\partial l\left( w^{(k)} \right)
$$

bzw. mit
- $B \subseteq \{ 1, \dots, m \}$ ein zufällig ausgewählter Batch

$$
	w^{(k+1)} = w^{(k)} - \gamma^{(k)}\frac{1}{m}\sum_{i=1}^m \partial l_i\left( w^{(k)} \right) \approx w^{(k)} - \gamma^{(k)}\frac{1}{|B|}\sum_{i \in B} \partial l_i\left( w^{(k)} \right)
$$

---

Vorteile:
- Eine Abschätzung des [[zettel/Subgradient|Subgradienten]] $\partial f$ ist deutlich günstiger als $\partial f$ zu berechnen

Nachteile:
- Stochastic (Sub-)Gradient-Descent ist nicht monoton fallend