Sei $(\Omega, \mathcal{A}, \mu)$ ein [[zettel/Maßraum|Maßraum]], $\omega \in \Omega$, $U \subseteq \mathbb{C}$, $z_0, z \in U$, $f : \Omega \times U \to \mathbb{C}$ mit
- $U$ offen
- $\forall \omega \in \Omega, z \in U : \omega \mapsto f(\omega, z)$ $\mu$-[[zettel/Funktion/μ-Integrierbarkeit Komplexwertigkeit|integrierbar]]
- $\forall \omega \in \Omega, z \in U : z \mapsto f(\omega, z)$ $\mu$-[[zettel/Funktion/μ-Integrierbarkeit Komplexwertigkeit|integrierbar]]
- $\exists k : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L})$ mit
	- $k$ nicht-negativ
	- $k$ $\mu$-[[zettel/Funktion/μ-Integrierbarkeit Komplexwertigkeit|integrierbar]]
	- $k$ [[zettel/Funktion/Messbarkeit|messbar]]
	- $\forall \omega \in \Omega, z \in U : |f(\omega, z) - f(\omega, z_0)| \le |z - z_0|k(\omega)$

Es gilt
- $\varphi : U \to \mathbb{C}$ differenzierbar in $z_0$ mit

$$
	\varphi(z) = \int f(\omega, z) d\mu(\omega)
$$

- $\omega \mapsto \frac{d}{dz} f(\omega, z)|_{z = z_0}$ ist [[zettel/Funktion/Komplexwertigkeit|komeplexwertig]], $(\mathcal{A}, \mathcal{L}(\mathbb{C}))$-[[zettel/Funktion/Komplexwertigkeit A-S-Messbarkeit|messbar]] und $\mu$-[[zettel/Funktion/μ-Integrierbarkeit Komplexwertigkeit|integrierbar]]

und 

$$
	\varphi'(z_0) = \int \frac{d}{dz} f(\omega, z)|_{z = z_0} d\mu(\omega)
$$