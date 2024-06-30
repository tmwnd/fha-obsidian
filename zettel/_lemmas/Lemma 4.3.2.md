Seien $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Messraum|Messräume]], $X = (X_1, X_2)$ eine $2$-dimensionale [[zettel/Zufallsvariable|Zufallsvariable]], $\mu_1, \mu_2$ $\sigma$-[[zettel/Maß|endliche]] TODO [[zettel/Maß|Maße]] auf $(R_1, \mathscr{S}_1)$ bzw. $(R_2, \mathscr{S}_2)$ mit
- $\mu = \mu_1 \otimes \mu_2$ dem [[zettel/Produktmaß|Produktmaß]] auf $\mu_1$ und $\mu_2$
- $X$ hat eine  $\mu$-Dichte $f$

Es gilt nach dem [[zettel/Satz von Fubini|Satz von Fubini]]

$$
	\forall B \in \mathscr{S}_1 : P(X_1 \in B) = P(X_1 \in B, X_2 \in R_2) = \int_{B \times R_2} f d\underbrace{(\mu_1 \otimes \mu_2)}_{= \mu} \overset{\text{Fubini}}{=} \int_B \left( \int_{R_2} f(x_1, x_2) d\mu_2(x_2) \right) d\mu_1(x_1)
$$

mit
- $x_1 \in R_1$
- $x_2 \in R_2$
- $f_{X_1}(x_1) = \int_{R_2} f(x_1, x_2) d\mu_2(x_2)$ ist die $\mu_1$-[[zettel/μ-Dichte|Dichte]] von $X$
- $f_{X_2}(x_2) = \int_{R_1} f(x_1, x_2) d\mu_1(x_1)$ ist die $\mu_2$-[[zettel/μ-Dichte|Dichte]] von $X$