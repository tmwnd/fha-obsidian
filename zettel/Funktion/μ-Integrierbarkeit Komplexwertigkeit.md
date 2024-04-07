---
title: μ-Integrierbarkeit einer komplexwertigen Funktion
type: property
---

Sei $(\Omega, \mathcal{A}, \mu)$ ein [[zettel/Maßraum|Maßraum]], $f: (\Omega, \mathcal{A}) \to (\mathbb{C}, \mathcal{L}(\mathbb{C}))$ eine [[zettel/Funktion/Komplexwertigkeit|komplexwertige]], [[zettel/Funktion/Komplexwertigkeit A-S-Messbarkeit|messbare]] [[zettel/Funktion|Funktion]].

$f$ heißt *$\mu$-integrierbar*, falls
- $\text{Re}(f)$ $\mu$-[[zettel/Funktion/μ-Integrierbarkeit|integrierbare]] ist
- $\text{Im}(f)$ $\mu$-[[zettel/Funktion/μ-Integrierbarkeit|integrierbare]] ist

Das $\mu$-[[zettel/μ-Integral|Integral]] von $f$ ist definiert als

$$
	\int d f\mu = \int \text{Re}(f) d\mu + i \int \text{Im}(f) d\mu
$$

---

Sei $(\Omega, \mathcal{A}, \mu)$ ein [[zettel/Maßraum|Maßraum]], $f: (\Omega, \mathcal{A}) \to (\mathbb{C}, \mathcal{L}(\mathbb{C}))$ eine $\mu$-integrierbare [[zettel/Funktion/Komplexwertigkeit|komplexwertige]], [[zettel/Funktion/Komplexwertigkeit A-S-Messbarkeit|messbare]] [[zettel/Funktion|Funktion]].

Es gilt für das $\mu$-[[zettel/μ-Integral|Integral]]
- Die komplex konjugierte Funktion $\overline{f} = \text{Re}(f) - i \text{Im}(f)$ ist ebenfalls $\mu$-Integrierbare
- Das  $\mu$-[[zettel/μ-Integral|μ-Integral]] von $\overline{f}$ ist definiert als

$$
	\int \overline{f} d\mu = \overline{\int f d\mu}
$$

---

Sei $(\Omega, \mathcal{A}, \mu)$ ein [[zettel/Maßraum|Maßraum]], $f: (\Omega, \mathcal{A}) \to (\mathbb{C}, \mathcal{L}(\mathbb{C}))$ eine [[zettel/Funktion/Komplexwertigkeit|komplexwertige]], [[zettel/Funktion/Komplexwertigkeit A-S-Messbarkeit|messbare]] [[zettel/Funktion|Funktion]].

Es gilt
- $f$ $\mu$-integrierbar $\iff$ $|f|$ $\mu$-integrierbar

---

Sei $(\Omega, \mathcal{A}, \mu)$ ein [[zettel/Maßraum|Maßraum]], $f: (\Omega, \mathcal{A}) \to (\mathbb{C}, \mathcal{L}(\mathbb{C}))$ eine $\mu$-integrierbare [[zettel/Funktion/Komplexwertigkeit|komplexwertige]], [[zettel/Funktion/Komplexwertigkeit A-S-Messbarkeit|messbare]] [[zettel/Funktion|Funktion]].

Es gilt für das $\mu$-[[zettel/μ-Integral|Integral]]

$$
	\left| \int f d\mu \right| \le \int |f| d\mu
$$