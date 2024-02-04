Sei $(\Omega, \mathcal{A}, \mu)$ ein [[Maßraum]], $f: (\Omega, \mathcal{A}) \to (\mathbb{C}, \mathcal{L}(\mathbb{C}))$ eine [[Komplexwertige Funktion|komplexwertige]], [[A-S-Messbarkeit einer komplexwertigen Funktion|messbare]] [[Funktion]].

$f$ heißt *$\mu$-integrierbar*, falls
- $\text{Re}(f)$ $\mu$-[[mu-Integrierbarkeit|integrierbare]] ist
- $\text{Im}(f)$ $\mu$-[[mu-Integrierbarkeit|integrierbare]] ist

Das $\mu$-[[mu-Integral|Integral]] von $f$ ist definiert als

$$
	\int d f\mu = \int \text{Re}(f) d\mu + i \int \text{Im}(f) d\mu
$$

---

Sei $(\Omega, \mathcal{A}, \mu)$ ein [[Maßraum]], $f: (\Omega, \mathcal{A}) \to (\mathbb{C}, \mathcal{L}(\mathbb{C}))$ eine $\mu$-integrierbare [[Komplexwertige Funktion|komplexwertige]], [[A-S-Messbarkeit einer komplexwertigen Funktion|messbare]] [[Funktion]].

Es gilt für das $\mu$-[[mu-Integral|Integral]]
- Die komplex konjugierte Funktion $\overline{f} = \text{Re}(f) - i \text{Im}(f)$ ist ebenfalls $\mu$-Integrierbare
- Das  $\mu$-[[mu-Integral]] von $\overline{f}$ ist definiert als

$$
	\int \overline{f} d\mu = \overline{\int f d\mu}
$$

---

Sei $(\Omega, \mathcal{A}, \mu)$ ein [[Maßraum]], $f: (\Omega, \mathcal{A}) \to (\mathbb{C}, \mathcal{L}(\mathbb{C}))$ eine [[Komplexwertige Funktion|komplexwertige]], [[A-S-Messbarkeit einer komplexwertigen Funktion|messbare]] [[Funktion]].

Es gilt
- $f$ $\mu$-integrierbar $\iff$ $|f|$ $\mu$-integrierbar

---

Sei $(\Omega, \mathcal{A}, \mu)$ ein [[Maßraum]], $f: (\Omega, \mathcal{A}) \to (\mathbb{C}, \mathcal{L}(\mathbb{C}))$ eine $\mu$-integrierbare [[Komplexwertige Funktion|komplexwertige]], [[A-S-Messbarkeit einer komplexwertigen Funktion|messbare]] [[Funktion]].

Es gilt für das $\mu$-[[mu-Integral|Integral]]

$$
	\left| \int f d\mu \right| \le \int |f| d\mu
$$