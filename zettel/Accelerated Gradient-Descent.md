---
title: Accelerated Gradient-Descent
type: definition
aliases:
  - Accelerated Gradient-Descent
  - Nesterov
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Datenpaare, $l$ eine differenzierbare [[zettel/Loss-Funktion|Loss-Funktion]], $w^{(-1)} = w^{(0)} \in \mathbb{R}^n$, $\alpha \in \mathbb{R}$.

Die $k$-te Iteration des *Accelerated Gradient-Descent-Verfahrens* ist definiert als

$$
	v^{(k+1)} = w^{(k)} + \frac{k-1}{k-1}(w^{(k)} - w^{(k-1)})
$$

$$
	w^{(k+1)} = v^{(k+1)} - \alpha^{(k)} l'(v^{(k+1)})
$$

---

Nachteile:
- Accelerated Gradient-Descent ist nicht monoton fallend