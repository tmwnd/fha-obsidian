Sei $(X_t)_{t \in \mathbb{N}}$ eine [[zettel/Zeitreihe|Zeitreihe]].

Das *additive Zerlegungsmodell* $(\mu_t + \varepsilon_t)_{t \in \mathbb{N}}$ ist definiert über
- $\forall t \in \mathbb{N} : \mu_t := \text{E}[X_t]$ deterministisches *Signal* bzw. *Trend*
- $\forall t \in \mathbb{N} : \varepsilon_t := (X_t - \text{E}[X_t])$ zufälliges *Rauschen*

Es gilt
- $(X_t)_{t \in \mathbb{N}} = (\mu_t + \varepsilon_t)_{t \in \mathbb{N}}$
- $\forall t \in \mathbb{N} : \text{E}[\varepsilon_t] = 0$