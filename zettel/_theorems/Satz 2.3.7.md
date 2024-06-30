Sei $(\Omega, \mathcal{A}, \mu)$ ein [[zettel/Maßraum|Maßraum]], $(A_n)_{n \in \mathbb{N}} \subseteq \mathcal{A}$.

Es gelten folgende [[zettel/Konvergenz|Konvergenzaussagen]]
- Falls $A_n \uparrow A$ gilt die *$\sigma$-Stetigkeit von unten*

$$
	\lim_{n \to \infty} \mu(A_n) = \mu(A) = \mu\left( \bigcup_{n \in \mathbb{N}} A_n \right)
$$

- Falls $A_n \downarrow A$ und $\inf_{n \in \mathbb{N}} \mu(A_n) \lt \infty$ gilt die *$\sigma$-stetigkeit von oben*

$$
	\lim_{n \to \infty} \mu(A_n) = \mu(A) = \mu\left( \bigcap_{n \in \mathbb{N}} A_n \right)
$$