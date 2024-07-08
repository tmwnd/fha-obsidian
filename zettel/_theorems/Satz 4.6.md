Sei $(X_t)_{t \in \mathbb{R}_0}$ ein [[zettel/Stochastischer Prozess|Stochastischer Prozess]], $(\mathcal{F}_t)_{t \in \mathbb{R}_0}$ eine [[zettel/Filtration|Filtration]], $S$, $T$ [[zettel/Stoppzeit|Stoppzeiten]], $M \gt 0$ mit
- $\forall t \in \mathbb{R}_0 : \text{E}[|X_t|] \lt \infty$
- $(X_t)_{t \in \mathbb{R}_0}$ [[zettel/_edges/Adaption Stochastischer Prozess Filtration|adaptiert]] $(\mathcal{F}_t)_{t \in \mathbb{R}_0}$
- $S \le T \le M$

Wir betrachten die folgenden Aussagen
- a) $(X_t, \mathcal{F}_t)_{t \in \mathbb{R}_0}$ ist ein [[zettel/Martingal|Martingal]]
- b) $\forall \tau \lt M, \omega \in \Omega : \text{E}[X_\tau] = \text{E}[X_0]$
- c) $\text{E}[X_T \mid \mathcal{F}_S] = X_S$

Es gilt
- a) $\iff$ b) $\iff$ c)