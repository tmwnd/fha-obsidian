Seien $((\Omega_i, \mathcal{A}_i, \mu_i))_{i \in \{ 1, 2 \}}$ [[Maßraum|Maßräume]], $f : (\Omega_1 \times \Omega_2, \mathcal{A}_1 \otimes \mathcal{A_2}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}})$ eine [[Funktion|messbare]] [[Funktion]] mit
- $f \gt 0$

Es gilt
- $\forall \omega_2 \in \Omega_2 : w_2 \mapsto \int f_{\omega_2} d\mu_1$ ist $(\mathcal{A}_2, \overline{\mathcal{L}})$-[[Funktion|messbar]]
- $\forall \omega_1 \in \Omega_1 : w_1 \mapsto \int f_{\omega_1} d\mu_2$ ist $(\mathcal{A}_1, \overline{\mathcal{L}})$-[[Funktion|messbar]]

und 

$$
	\int f d(\mu_1 \otimes \mu_2) = \int\left( \int f_{\omega_2} d\mu_1 \right) d\mu_2(\omega_2) = \int\left( \int f_{\omega_1} d\mu_2 \right) d\mu_1(\omega_1)
$$

---

Seien $((\Omega_i, \mathcal{A}_i, \mu_i))_{i \in \{ 1, 2 \}}$ [[Maßraum|Maßräume]], $f : (\Omega_1 \times \Omega_2, \mathcal{A}_1 \otimes \mathcal{A_2}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}})$ eine [[Funktion|messbare]] [[Funktion]] mit
- $f$ $\mu_1 \otimes \mu_2$-[[mu-Integral|integrierbar]]

Es gilt
- $f_{\omega_1}$ ist für $\mu_1$-[[mu-Nullmengen|fast alle]] $\omega_1 \in \Omega_1$ $\mu_2$-[[mu-Integral|integrierbar]]
- $f_{\omega_2}$ ist für $\mu_2$-[[mu-Nullmengen|fast alle]] $\omega_2 \in \Omega_2$ $\mu_1$-[[mu-Integral|integrierbar]]

Die $\mu_1$-[[Funktion|f. ü. definierte]] [[Funktion]] bzw. $\mu_2$-[[Funktion|f. ü. definierte]] [[Funktion]] ist definiert als
- $\omega_1 \mapsto \int f_{\omega_1} d\mu_2$
- $\omega_2 \mapsto \int f_{\omega_2} d\mu_1$

Es gilt

$$
	\int f d(\mu_1 \otimes \mu_2) = \int\left( \int f_{\omega_2} d\mu_1 \right) d\mu_2(\omega_2) = \int\left( \int f_{\omega_1} d\mu_2 \right) d\mu_1(\omega_1)
$$