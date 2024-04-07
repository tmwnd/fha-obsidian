---
title: Lemma 4.2.1
type: lemma
---

Seien $((\Omega_i, \mathcal{A}_i))_{i \in \{ 1, 2 \}}$ [[zettel/Messraum|Messräume]] mit
- $\Omega = \Omega_1 \times \Omega_2$
- $\mathcal{A} = \mathcal{A}_1 \otimes \mathcal{A}_2$ die Produkt-$\sigma$-[[zettel/Produkt-σ-Algebra|Algebra]] auf $((\Omega_i, \mathcal{A}_i))_{i \in \{ 1, 2 \}}$
- $A_{\omega_1} = \{ \omega_2 \in \Omega_2 : (\omega_1, \omega_2) \in A \}$ *der $\omega_1$-Schnitt* von $A$ mit $\omega_1 \in \Omega_1$, $A \in \Omega$
- $A_{\omega_2} = \{ \omega_1 \in \Omega_1 : (\omega_1, \omega_2) \in A \}$ *der $\omega_2$-Schnitt* von $A$ mit $\omega_2 \in \Omega_2$, $A \in \Omega$
- $\forall \omega_1 \in \Omega_1 : \{ A \in \mathcal{A} : A_{\omega_1} \in \mathcal{A}_2 \}$ ist eine $\sigma$-[[zettel/σ-Algebra|Algebra]]

Sei $(R, \mathscr{S})$ ein [[zettel/Messraum|Messraum]], $f : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ eine [[zettel/Funktion|messbare]] TODO [[zettel/Funktion|Funktion]], $\omega_1 \in \Omega_1$, $\omega_2 \in \Omega_2$.

Es gilt
- $\forall \omega_1 \in \Omega_1 : f_{\omega_1}(\omega_2) = f(\omega_1, \omega_2)$
- $\forall \omega_2 \in \Omega_2 : f_{\omega_2}(\omega_1) = f(\omega_1, \omega_2)$
- $\forall \omega_1 \in \Omega_1 : f_{\omega_1} : \Omega_2 \to R$ ist eine $(\mathcal{A}_2, \mathscr{S})$-[[zettel/Funktion/A-S-Messbarkeit|messbare]] [[zettel/Funktion|Funktion]]
- $\forall \omega_2 \in \Omega_2 : f_{\omega_2} : \Omega_1 \to R$ ist eine $(\mathcal{A}_1, \mathscr{S})$-[[zettel/Funktion/A-S-Messbarkeit|messbare]] [[zettel/Funktion|Funktion]]

---

Seien $((\Omega_i, \mathcal{A}_i))_{i \in \{ 1, 2 \}}$ [[zettel/Messraum|Messräume]] mit
- $\Omega = \Omega_1 \times \Omega_2$
- $\mathscr{S} = \{ A_1 \times A_2, A_1 \in \mathcal{A}, A_2 \in \mathcal{A} \}$ der [[zettel/Semiring|Semiring]] auf $\Omega$
- $\mathcal{A} = \mathcal{A}_1 \otimes \mathcal{A}_2 = \sigma(\mathscr{S})$ die Produkt-$\sigma$-[[zettel/Produkt-σ-Algebra|Algebra]] auf $((\Omega_i, \mathcal{A}_i))_{i \in \{ 1, 2 \}}$

Sie $\mu_1$ ein [[zettel/Maß|Maß]] auf $\mathcal{A}_1$, $\mu_2$ ein [[zettel/Maß|Maß]] auf $\mathcal{A}_2$, $A_1 \in \mathcal{A}_1$, $A_2 \in \mathcal{A}_2$ mit
- $S = A_1 \times A_2 \in \mathscr{S}$
- $\tilde{\mu}$ dem $\sigma$-[[zettel/Funktion/σ-Additivität|additiven]] [[zettel/Produktmaß|Produktmaß]] von $\mu_1$ und $\mu_2$ auf $\mathscr{S}$

$\tilde{\mu}$ ist definiert als

$$
	\tilde{\mu}(S) = \mu_1(A_1) \times \mu_2(A_2)
$$