Sei $(\Omega, \mathcal{A}, P)$ ein [[Maßraum|Wahrscheinlichkeitsraum]], $X$ ein $d$-dimensionaler [[Zufallsvariable|Zufallsvektor]] auf $(\Omega, \mathcal{A}, P)$, $z \in \mathbb{R}^d$.

Die Funktione $\varphi_X : \mathbb{R}^d \to \mathbb{C}$ heißt *Fourier-Transformierte* von $X$ bzw. $P^X$ und ist definiert als

$$
	\varphi_X(z) = E[e^{iz^TX}]
$$

---

Sei $X$ein $d$-dimensionaler [[Zufallsvariable|Zufallsvektor]], $\varphi_X$ die Fourier-Transformierte von $X$

Es gilt
- $\varphi_X(\vec{0}) = 1$
- $\forall z \in \mathbb{R}^d : |\varphi_X(z)| \le 1$
- $\varphi_X$ ist gleichmäßig stetig
- $\varphi_Y(z) = e^{ib^Tz}\varphi_X(A^TX)$ mit
	- $n \in \mathbb{N}$
	- $A \in \mathbb{R}^{n \times d}$
	- $b \in \mathbb{R}^n$
	- $Y = AX + b$ ein $n$-dimensionale [[Zufallsvariable|Zufallsvektor]]
- $\overline{\varphi_X}$ ist die Fourier-Transformierte für $-X$

---

Sei $n \in \mathbb{N}$, $(X_n)_{n \in \{ 1, \dots, n \}}$ [[Unabhängige Zufallsvariablen|unabhängige]] $d$-dimensionale [[Zufallsvariable|Zufallsvektoren]] mit den Fourier-Transformierten $(\varphi_n)_{n \in \{ 1, \dots, n \}}$, $z \in \mathbb{R}^d$ mit
- $X = \sum_{i=1}^n X_i$

Die Fourier-Transformierte $\varphi_x$ ist definiert als

$$
	\varphi_X(z) = \prod_{i=1}^n \varphi_i(z)
$$