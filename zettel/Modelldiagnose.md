Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ [[zettel/ARMA-Prozess/Invertierbarkeit|invertierbar]] mit $p, q$ unbekannt, $\hat{\phi}, \hat{\vartheta}$ Schätzer für $\phi, \vartheta$ und
- $(\hat{\varepsilon}_t)_{t \in \mathbb{Z}}$ ein Schätzer für die Residuen von $(X_t)_{t \in \mathbb{Z}}$ definiert als

$$
	\forall t \in \mathbb{Z} : \hat{\varepsilon}_t = \sum_{i \in \mathbb{Z}} \hat{\vartheta}^{-1} B^i\left( \sum_{j \in \mathbb{Z}} \hat{\phi}_j B^j(X_t) \right) = X_t - \hat{X}_t
$$

Zur *Modelldiagnose* sind folgende Schritte notwendig
1. Plotte Residuen $(\hat{\varepsilon}_t)_{t \in \mathbb{Z}}$
2. Plotte [[zettel/ACF|ACF]] bzw. [[zettel/PACF|PACF]] der Residuen $(\hat{\varepsilon}_t)_{t \in \mathbb{Z}}$
3. Teste die Residuen $(\hat{\varepsilon}_t)_{t \in \mathbb{Z}}$ auf Korrelation ([[zettel/Ljung-Box-Test|Ljung-Box-Test]])
4. Teste die Residuen $(\hat{\varepsilon}_t)_{t \in \mathbb{Z}}$ auf Trend ([[zettel/Rank-Test|Rank-Test]])
5. Teste die Residuen $(\hat{\varepsilon}_t)_{t \in \mathbb{Z}}$ auf Normalverteilung (Shapiro-Wilk-Test)