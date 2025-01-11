Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $\vartheta \in \Theta \subseteq \mathbb{R}^k$, $\text{AIK}$ das [[zettel/Akaike-Informationskriterium|Akaike-Informationskriterium]] für einen Schätzer $\hat{\vartheta}$ von $\vartheta$.

Die korrigierte Version $\text{AICc}$ des $\text{AIC}$ für kleine Stichproben $n$ ist definiert als

$$
	\text{AICc} := \text{AIC} + \frac{2k^2 + 2k}{n-k-1}
$$