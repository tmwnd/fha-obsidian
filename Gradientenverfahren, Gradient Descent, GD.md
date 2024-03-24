Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Daten-Paare, $l$ eine differenzierbare [[Loss-Funktion]], $w^{(0)} \in \mathbb{R}^n$, $\gamma^{(k)} \ge 0$ die Schrittlänge.

Die $k$-te Iteration des *Gradientenverfahrens* ist definiert als

$$
	w^{(k+1)} = w^{(k)} - \gamma^{(k)}l'\left( w^{(k)} \right)
$$