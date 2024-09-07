Sei $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\Omega$, $B \subseteq \Omega$.

Die *Spur-$\sigma$-Algebra* $\mathcal{A}_B$ von $\mathcal{A}$ auf $B$ ist definiert als

$$
	\mathcal{A}_B := \{ A \cap B, A \in \mathcal{A} \}
$$

---

Sei $\mathcal{C} \subseteq \mathcal{P}(\Omega)$, $B \subseteq \Omega$ mit
- $\mathcal{C}_B = \{ C \cap B, C \in \mathcal{C} \}$

$\sigma(\mathcal{C})_B$ ist die von $\mathcal{C}_B$ erzeugte $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $B$.

---

Sei $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\Omega$, $B \subseteq \Omega$, $\mu$ ein [[zettel/Maß|Maß]] auf $\mathcal{A}$.

Das [[zettel/Maß|Maß]] $\mu_B = \mu|_{\mathcal{A}_B}$ ist ein [[zettel/Maß|Maß]] auf $\mathcal{A}_B$, falls
- $B \in \mathcal{A}$

---

Sei $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\Omega$, $B \in \mathcal{A}$, $C \in \mathcal{A}_B$, $\mu$ ein [[zettel/Maß|Maß]] auf $\mathcal{A}$.

Das [[zettel/Maß|Maß]] $\mu_B$ ist ein [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaß]], falls
- $0 \lt \mu(B) \lt \infty$

und ist definiert durch

$$
	\mu_B(C) := \frac{\mu(C)}{\mu(B)}
$$

---

Das [[zettel/Lebesgue-Borelsches Maß|Lebesgue-Borelsches Maß]] $\lambda_{[0, 1]}$ ist ein [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaß]] auf der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathscr{B}_{[0, 1]}$.