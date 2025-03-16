Sei $(X, \oplus, \odot)$ ein [[zettel/Linearer Raum|linearer Raum]], $d : X \to X$ eine [[zettel/Metrik|Metrik]].

Es existiert eine [[zettel/Linearer Raum/Norm|Norm]] $\| \cdot \| : X \to \mathbb{R}_0^+$ in $(X, \oplus, \odot)$ genau dann, falls
- $\forall x, y, z \in X : d(x \oplus z, y \oplus z) = d(x, y)$ (Translationsinvarianz)
- $\forall x, y \in X, \lambda \in \mathbb{R} : d(\lambda \odot x, \lambda \odot y) = |\lambda| d(x, y)$ (Skalierungsinvarianz)