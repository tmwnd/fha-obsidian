Sei $\emptyset \ne \Theta \in \mathscr{B}^d$ eine Parametermenge, $\mathcal{P} := \{ P_\vartheta \mid \vartheta \in \Theta \}$ die durch $\Theta$ indizierte Menge von Wahrscheinlichkeitsmaßen mit
- $\forall \vartheta \in \Theta, B \in \mathscr{B}^n : \vartheta \mapsto P_\vartheta(B)$ [[zettel/Funktion/Messbarkeit|messbar]]
- $\forall \vartheta \in \Theta, B \in \mathscr{B}^n : (\theta, B) \mapsto P_\vartheta(B)$ ein [[zettel/Übergangskern|Übergangskern]] von $(\Theta, \mathscr{B}_\Theta^d)$ nach $(\mathbb{R}^n, \mathscr{B}^n)$
- $\mu$ [[zettel/a-priori-Verteilung|a-priori-Verteilung]]
- $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^n, \mathscr{B}^n)$ ein [[zettel/Zufallsvariable|Zufallsvektor]]
- $\forall \vartheta \in \Theta : P_\vartheta$ [[zettel/Bedingte Verteilung|Bedingte Verteilung]] von $X$ unter $\vartheta$

Schreibe

$$
	\forall B \in \mathscr{B}^p, \vartheta \in \Theta : P^{(X, \vartheta)}(B, A) = \int_A P_\vartheta(B) d\mu(\vartheta)
$$

bzw.

$$
	\forall B \in \mathscr{B}^p : P^X(B) \int_\Theta P_\vartheta(B) d\mu(\vartheta)
$$