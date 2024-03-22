Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Daten-Paare, $l$ eine differenzierbare [[Loss-Funktion]].

Die $k$-te Iteration des *Gradientenverfahrens* ist definiert als

$$
	w^{(k+1)} = w^{(k)} - l''\left( w^{(k)} \right)^{-1}l'\left( w^{(k)} \right)
$$