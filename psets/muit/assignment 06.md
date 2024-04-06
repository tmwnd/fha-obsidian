---
type: assignment
---

1. Eine Abbildung $\varphi : \mathbb{R}^n \to \mathbb{R}^n$ heißt *Bewegung des Raumes*, wenn
	
	$$
		\langle \varphi(x), \varphi(y) \rangle = \langle x, y \rangle \quad \forall x, y \in \mathbb{R}^n
	$$
	
	gilt.
	Es steht $\langle \cdot, \cdot \rangle$ für das euklidische Skalarprodukt.
	
	1. Physikalisch entspricht eine solche Abbildung einer Starrkörperbewegung.
		Um diese Anschauung zu rechtfertigen, zeigen Sie: Bewegungen des Raumes erhalten Winkel und (euklidische) Abstände.
	2. Zeigen Sie: Eine Bewegung $\varphi$ des Raumes ist linear, und die Abbildungsmatrix ist orthogonal.
		
		*Hinweis*: Zeigen Sie die Additivität von $\varphi$ durch den Nachweis von $\| \varphi(x+y) - \varphi(x) - \varphi(y) \|^2 = 0 \forall x, y$ und die Homogenität analog.
	3. Zeigen Sie: Das Lebesgue-Maß ist invariant unter Bewegung des Raumes.

^1

2. Eine Abbildung $f : \mathbb{R}^n \to \mathbb{R}^n$ heißt *Isometrie*, wenn
	
	$$
		\| f(x) - f(y) \| = \| x - y \| \quad \forall x, y \in \mathbb{R}^n
	$$
	
	gilt mit der euklidischen Norm $\| \cdot \|$.
	Zeigen Sie:
	1. Eine Isometrie $f$ mit $f(0) = 0$ ist eine Bewegung des Raumes.
		
		*Anleitung*: Betrachten Sie die Gleichung $\| f(x) - f(y) \|^2 = \| x - y \|^2$
	2. Für eine Isometrie $f$ gilt $f = T \circ \varphi$, wobei $T$ eine Translation ist und $\varphi$ eine Bewegung des Raumes.
	Deuten Sie damit eine Isometrie physikalisch.
	3. Das Lebesgue-Maß auf $\mathbb{R}^n$ ist translationsinvariant.
	4. Das Lebesgue-Maß ist invariant gegenüber Isometrien.

^2

3. Sei $H \subseteq \mathbb{R}^n$ eine Hyperebene.
	Zeigen Sie, dass $H$ eine $\lambda^n$-Nullmenge ist.

^3

4. Wir kehren noch einmal zum Satz von Tonelli zurück..
	Die Voraussetzung der $\sigma$-Endlichkeit an Maßräume ist nowendig.
	Um das einzusehen, betrachten wir die Maßräume $([0, 1], \mathcal{B}^*([0, 1]), \lambda)$ und $([0, 1], \mathcal{P}([0, 1]), \#)$, wobei $\#$ für das Zählmaß steht.
	Die $\sigma$-Algebra $\mathcal{B}^*([0, 1])$ geht durch die Restriktion aus der Borelschen $\sigma$-Algebra $\mathcal{B}^*$ hervor.
	Es sei $D := \{ (x, x) \mid x \in [0, 1] \}$.
	Zeigen Sie:
	1. $D \in \mathcal{A} := \mathcal{B}^*([0, 1]) \otimes \mathcal{P}([0, 1])$
	2. 
	
	$$
		\int_{[0, 1]}\int_{[0, 1]} I_D(x, y) \lambda(dx)\#(dy) = 0
	$$
	
	3. 
	
	$$
		\int_{[0, 1]}\int_{[0, 1]} I_D(x, y) \#(dy)\lambda(dx) = 1
	$$
	
	4. Folgern Sie, dass  für die Eindeutigkeit des Produktmaßes die $\sigma$-Endlichkeit der Ausgangsmaße notwendig ist.

^4