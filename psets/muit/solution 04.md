---
type: solution
---

![[psets/muit/assignment 04#^1|assignment 04#^1]]

Sei $\lambda$ das $\sigma$-[[zettel/Maß|endliche]] TODO [[zettel/Lebesgue-Borelsches Maß|Lebesgue-Borelsches Maß]], $\epsilon_x$ das [[zettel/Dirac-Maß|Einpunktmaß]], $\mathcal{N}_\lambda$ das [[zettel/μ-Nullmenge|System der Nullmengen]] auf $\lambda$, $\mathcal{N}_{\epsilon_x}$ das [[zettel/μ-Nullmenge|System der Nullmengen]] auf $\epsilon_x$.

$\epsilon_x$ hat eine $\lambda$-[[zettel/μ-Dichte|Dichte]], falls
- $\epsilon_x$ $\lambda$-[[zettel/μ-Stetigkeit|stetig]] ist

$\epsilon_x$ ist $\lambda$-stetig, falls
- $\forall N \in \mathcal{N}_\lambda : N \in \mathcal{N}_{\epsilon_x}$

$\unicode{x21af}$: $\{ x \} \in \mathcal{N}_\lambda \land \{ x \} \notin \mathcal{N}_{\epsilon_x}$

---

![[psets/muit/assignment 04#^2|assignment 04#^2]]

1. $\sim$ ist eine Äquivalenzrelation, falls
	1. $\mu = \mu \implies \mu \sim \mu$ (Reflexivität)
	2. $\mu \sim \nu \implies \nu \sim \mu$ (Symmetrie)
	3. $\mu \sim \pi \land \pi \sim \nu \implies \mu \sim \nu$ (Transitivität)
	
	Alle Voraussetzungen sind erfüllt, da
	1. $\mu$ offensichtlich $\mu$-[[zettel/μ-Stetigkeit|stetig]]
	2. $\mu \sim \nu \implies \mu \ \nu\text{-stetig} \land \nu \ \mu\text{-stetig} \implies \nu \ \mu\text{-stetig} \land \mu \ \nu\text{-stetig} \land \nu \sim \mu$
	3. $\mu \sim \pi \land \pi \sim \nu \implies \mu \ \pi\text{-stetig} \land \pi \ \mu\text{-stetig} \land \pi \ \nu\text{-stetig} \land \nu \ \pi\text{-stetig} \implies \mathcal{N}_\mu = \mathcal{N}_\pi \land \mathcal{N}_\pi = \mathcal{N}_\nu \implies \mathcal{N}_\mu = \mathcal{N}_\nu \implies \mu \sim \nu$
2. $\mu \sim \nu \implies \mu \ \nu\text{-stetig} \land \nu \ \mu\text{-stetig} \implies \forall N \in (\mathcal{N}_\mu \cup \mathcal{N}_\nu) : N \in \mathcal{N}_\mu \land N \in \mathcal{N}_\nu \implies \mathcal{N}_\mu = \mathcal{N}_\nu$
3. $\mu \sim \nu \implies \exists f \in E_+(X, \mathcal{A}) : \nu = f\mu$

---

![[psets/muit/assignment 04#^3|assignment 04#^3]]

Sei $\lambda$ das [[zettel/Lebesgue-Borelsches Maß|Lebesgue-Borelsches Maß]], $\mathcal{N}_\lambda$ das [[zettel/μ-Nullmenge|System der Nullmengen]] auf $\lambda$, $\mathcal{N}_\nu$ das [[zettel/μ-Nullmenge|System der Nullmengen]] auf $\nu$.

1. $\nu$ ist $\lambda$-[[zettel/μ-Stetigkeit|stetig]], falls
	1. $\forall N \in \mathcal{N}_\lambda : N \in \mathcal{N}_\nu$

	$\nu$ ist $\sigma$-[[zettel/Maß|endlich]] TODO, falls eine Folge $(A_n)_{n \in \mathbb{N}} \subseteq \mathcal{A}$ existiert mit
	1. $\forall n \in \mathbb{N} : \mu(A_n) < \infty$
	2. $X = \bigcup_{n \in \mathbb{N}} A_i$