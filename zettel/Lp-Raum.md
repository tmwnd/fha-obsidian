Sei $1 \le p \in \mathbb{R}$, $(\Omega, \mathcal{A}, \mu)$ ein [[zettel/Maßraum|Maßraum]].

Der *$\mathcal{L}^p$-Raum* ist definiert als

$$
	\mathcal{L}^p := \mathcal{L}^p(\Omega, \mathcal{A}, \mu) = \left\{ f : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L}), \int |f|^p d\mu \lt \infty \right\}
$$

---

Sei $L^p \subseteq \mathcal{L}^p$ ein normierter Vektorraum mit
- $\forall f \in \mathcal{L}^p : [f]$ äquivalente [[zettel/Funktion|Funktionen]] nach $f \sim_{L_p} g \iff f = g$ $\mu$-[[zettel/μ-Nullmenge|f. ü.]]
- $\forall f \in \mathcal{L}^p : \exists! [g] \in L^p : f = g$ $\mu$-[[zettel/μ-Nullmenge|f. ü.]]

---

Ein $\mathcal{L}^p$-Raum besteht aus allen $p$-fach integrierbaren [[zettel/Funktion|messbaren]] [[zettel/Funktion|Funktionen]].

---

$L^p$ ist ein [[zettel/Banachraum|Banachraum]].

---

Sei $L^2$ ein $L^p$-Raum, $f, g \in L^2$, $\langle f, g \rangle$ ein Skalarprodukt mit
- $\langle f, g \rangle = \int f \cdot g d\mu$

$L^2$ ist ein reeller Hilbertraum.