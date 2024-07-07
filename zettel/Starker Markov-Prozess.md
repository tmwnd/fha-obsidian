Sei $(X_t)_{t \in T}$ ein [[zettel/Stochastischer Prozess|Stochastischer Prozess]], $(\mathcal{F}_t)_{t \in T}$ eine [[zettel/Filtration|Filtration]], $\tau$ eine [[zettel/Stoppzeit|Stoppzeit]].

Die Familie von Tupeln $(X_t, \mathcal{F}_t)_{t \in T}$ heißt *starker Markov-Prozess*, falls
- $\forall t \in T, f : \mathbb{R} \to \mathbb{R} : \text{E}[f(X_{\tau+t}) \mid \mathcal{F}_\tau] = \text{E}[f(X_{\tau+t}) \mid \sigma(X_\tau)]$