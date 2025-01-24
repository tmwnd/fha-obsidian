Sei $(X_t)_{t \in T}$ eine [[zettel/Zeitreihe|Zeitreihe]].

Das *additive Zerlegungsmodell* $(\mu_t + \varepsilon_t)_{t \in T}$ ist definiert über
- $\forall t \in T : \mu_t := \text{E}[X_t]$ deterministisches *Signal* bzw. *Trend*
- $\forall t \in T : \varepsilon_t := (X_t - \text{E}[X_t])$ zufälliges *Rauschen*

Es gilt
- $(X_t)_{t \in T} = (\mu_t + \varepsilon_t)_{t \in T}$
- $\forall t \in T : \text{E}[\varepsilon_t] = 0$