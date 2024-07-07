Sei $(X_t)_{t \in T}$ ein [[zettel/Stochastischer Prozess|Stochastischer Prozess]], $(\mathcal{F}_t)_{t \in T}$ eine [[zettel/Filtration|Filtration]].

Die Familie von Tupeln $(X_t, \mathcal{F}_t)_{t \in T}$ heißt *Markov-Prozess*, falls
- $\forall s, t \in T, s \le t, f : \mathbb{R} \to \mathbb{R} : \text{E}[f(X_{t+s}) \mid \mathcal{F}_t] = \text{E}[f(X_{t+s}) \mid \sigma(X_t)]$