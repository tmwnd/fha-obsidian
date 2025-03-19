Sei $(X_i)_{i \in \{ 1, \dots, t \}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ eine [[zettel/Zeitreihe|Zeitreihe]].

Es gilt
- $\mathcal{L}^2(\Omega, \mathcal{A}, P)$ ist ein [[zettel/Hilbertraum Cauchy-Folge|Hilbertraum Cauchy-Folge]]
- Der $L^2$-Abstand ist definiert als $\forall X, Y \in \mathcal{L}^2(\Omega, \mathcal{A}, P) : d(X, Y) = \sqrt{\text{E}[(X - Y)^2]}$

Gesucht ist eine Funktion $f : \mathbb{R} \to \mathbb{R}$ über

$$
	\underset{\alpha, \beta \in \mathbb{R}}{\arg\min} \ d\left( X_{t+1}, \beta + \sum_{i=1}^t \alpha_iX_i \right)
$$