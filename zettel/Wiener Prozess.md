Sei $(W_t)_{t \in \mathbb{R}_0}$ ein [[zettel/Stochastischer Prozess|Stochastischer Prozess]].

$(W_t)_{t \in \mathbb{R}_0}$ heißt *Wiener Prozess*, falls
- $W_0 = 0$ f. s.
- $(W_t)_{t \in \mathbb{R}_0}$ hat [[zettel/Stochastischer Prozess/Unabhängige Inkremente|unabhängige Inkremente]]
- $(W_t)_{t \in \mathbb{R}_0}$ hat [[zettel/Stochastischer Prozess/Stationäre und normalverteilte Inkremente|stationäre und normalverteilte Inkremente]]
- $(W_t)_{t \in \mathbb{R}_0}$ hat stetige [[zettel/Stochastischer Prozess/Pfad|Pfade]]

Schreibe
- $(B_t)_{t \in \mathbb{R}_0}$
- $(W_t)_{t \in \mathbb{R}_0}$

Es gilt
- $\forall t \in \mathbb{R}_0 : W_t = W_t - W_0 \sim \mathcal{N}(0, t)$
- $\forall s, t \in \mathbb{R}_0, s \lt t : \text{Cov}[W_t, W_s] = s$