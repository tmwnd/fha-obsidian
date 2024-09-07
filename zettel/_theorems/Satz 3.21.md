Sei $\emptyset \ne G \subseteq \mathbb{R}^d$ offen und $\Phi : G \to \mathbb{R}^d$ eine geeignete $(\mathscr{B}^d, \mathscr{B}^d)$-[[zettel/Funktion/A-S-Messbarkeit|messbare]] Transformation, $\Delta : \mathbb{R}^d \to \mathbb{R}$ die [[zettel/Funktionaldeterminante|Funktionaldeterminante]] und $f : (\Phi(G), \mathscr{B}_{\Phi(G)}^d) \to (\mathbb{R}, \mathscr{B})$ eine nicht-negative [[zettel/Funktion|Funktion]] mit
- $\Phi$ injektiv
- $\Phi$ stetig differenzierbar
- $\Delta$ verschwindet nirgends

Es gilt für die $\lambda^d$-Dichte

$$
	\int_{\Phi(G)} f(y) dy = \int_G f \circ \Phi(x) \cdot |\Delta(x)| dx
$$