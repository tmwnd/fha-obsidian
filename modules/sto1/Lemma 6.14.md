Sei $(\Omega, \mathcal{A}, \mu)$ ein [[Maßraum]], $\omega \in \Omega$, $U \subseteq \mathbb{C}$, $z_0, z \in U$, $f : \Omega \times U \to \mathbb{C}$ mit
- $U$ offen
- $\forall \omega \in \Omega, z \in U : \omega \mapsto f(\omega, z)$ $\mu$-[[mu-Integrierbarkeit einer komplexwertigen Funktion|integrierbar]]
- $\forall \omega \in \Omega, z \in U : z \mapsto f(\omega, z)$ $\mu$-[[mu-Integrierbarkeit einer komplexwertigen Funktion|integrierbar]]
- $\exists k : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L})$ mit
	- $k$ nicht-negativ
	- $k$ $\mu$-[[mu-Integrierbarkeit einer komplexwertigen Funktion|integrierbar]]
	- $k$ [[Funktion messbar|messbar]]
	- $\forall \omega \in \Omega, z \in U : |f(\omega, z) - f(\omega, z_0)| \le |z - z_0|k(\omega)$

Es gilt mit dem $\mu$-[[mu-Integral]]
- $\varphi : U \to \mathbb{C}$ differenzierbar in $z_0$ mit

$$
	\varphi(z) = \int f(\omega, z) d\mu(\omega)
$$

- $\omega \mapsto \frac{d}{dz} f(\omega, z)|_{z = z_0}$ ist [[Funktion komplexwertig|komeplexwertig]], $(\mathcal{A}, \mathcal{L}(\mathbb{C}))$-[[Funktion komplexwertig A-S-messbar|messbar]] und $\mu$-[[mu-Integrierbarkeit einer komplexwertigen Funktion|integrierbar]]

und 

$$
	\varphi'(z_0) = \int \frac{d}{dz} f(\omega, z)|_{z = z_0} d\mu(\omega)
$$