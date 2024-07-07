Sei $(X_t)_{t \in T}$ ein [[zettel/Stochastischer Prozess|Stochastischer Prozess]], $(\mathcal{F}_t)_{t \in T}$ eine [[zettel/Filtration|Filtration]].

Die Familie von Tupeln $(X_t, \mathcal{F}_t)_{t \in T}$ heißt *Submartingal*, falls
- $\forall s, t \in T, s \le t : X_s \le \text{E}[X_t \mid \mathcal{F}_s]$