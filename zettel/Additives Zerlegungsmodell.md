Sei $(X_t)_{t \in \mathbb{N}}$ eine Zeitreihe.

Das *additive Zerlegungsmodell* $(\mu_t + \epsilon_t)_{t \in \mathbb{N}}$ ist definiert über
- $\forall t \in \mathbb{N} : \mu_t := \text{E}[X_t]$ deterministisch
- $\forall t \in \mathbb{N} : \epsilon_t := (X_t - \text{E}[X_t])$ zufällig

Es gilt
- $\forall t \in \mathbb{N} : \text{E}[\epsilon_t] = 0$