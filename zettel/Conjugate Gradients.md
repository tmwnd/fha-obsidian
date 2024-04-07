---
title: Conjugate Gradients
type: definition
aliases:
  - CG
---

Sei $X \in \mathbb{R}^{m \times n}, y \in \mathbb{R}^m$, $w^{(0)} \in \mathbb{R}^n$ mit
- $\underbrace{X^TX}_Aw = \underbrace{X^Ty}_b$
- $A$ ist [[zettel/Matrix symmetrisch positiv definit|spd]]
- $p^{(0)} = r^{(0)} = b - Aw^{(0)}$

Der $k$-te Schritt von *CG* ist definiert als
- $\gamma^{(k)} = \frac{\langle r^{(k)}, r^{(k)} \rangle_2}{\langle p^{(k)}, Ap^{(k)} \rangle_2}$
- $w^{(k+1)} = w^{(k)} + \gamma^{(k)}p^{(k)}$
- $r^{(k+1)} = r^{(k)} - \gamma^{(k)}Ap^{(k)}$
- $\beta^{(k)} = \frac{\langle r^{(k+1)}, r^{(k+1)} \rangle_2}{\langle r^{(k)}, r^{(k)} \rangle_2}$
- $p^{(k+1)} = r^{(k+1)} + \beta^{(k)}p^{(k)}$

---

Interpretation
- CG als verbessertes [[zettel/Gradient Descent|Gradientenverfahren]]:
	- CG kann nicht langsamer als das [[zettel/Gradient Descent|Gradientenverfahren]] sein
	- CG greift im $k$-ten Schritt zusätzlich zu auf die vorherige Suchrichtung zu
	- CG ist keine stationäre Iteration
- CG als Projektionsverfahren
	- CG ersetzt $Aw = b$ durch eine Folge kleinerer, exakt zu lösender Systeme
	- CG wendet Modellvereinfachung bzw. Dimensionsreduktion an