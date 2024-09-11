Sei, $(X_i)_{i \in \{ 1, \dots, n \}}$, $\vartheta_1 := \frac{p_{1, 1}}{p_{1, 1} + p_{2, 1}}$, $\vartheta_2 := \frac{p_{2, 2}}{p_{1, 2} + p_{2, 2}}$ mit den [[zettel/Schätzer|Schätzern]] der [[zettel/Maximum-Likelihood-Schätzfunktion|Maximum-Likelihood-Schätzfunktionen]] $\hat{\vartheta}_{n, 1}(X) := \frac{N_{n, 1, 1}}{N_{n, 1, 1} + N_{n, 2, 1}}$, $\hat{\vartheta}_{n, 2}(X) := \frac{N_{n, 2, 2}}{N_{n, 1, 2} + N_{n, 2, 2}}$, $\hat{\vartheta}_{n, 3}(X) := \frac{1}{n} (N_{n, 1, 1} + N_{n, 2, 1})$

mit

| | Actually Positive | Actually Negative |
|---|---|---|
| **Test Positive** | $N_{n, 1, 1}$ | $N_{n, 1, 2}$
| **Test Negative** | $N_{n, 2, 1}$ | $N_{n, 2, 2}$

und
- $p_{1, 1} + p_{1, 2} + p_{2, 1} + p_{2, 2} = 1$

Die [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B_n^P(X)$, $B_n^W(X)$, $B_n^{LR}(X)$ sind definiert als

$$
	B_n^P(X) := \{ \eta \in (0, 1)^2 \mid T_{\eta, n}^P(X) \lt \chi_{2, 1-\alpha}^2 \}
$$

mit der Plug-In-Teststatistik $T_{\eta, n}^P(X)$

$$
	T_{\eta, n}^P(X) := n \left( (\hat{\vartheta}_{n, 1}(X) - \eta_1)^2 \cdot \frac{\hat{\vartheta}_{n, 3}(X)}{\hat{\vartheta}_{n, 1}(X)(1 - \hat{\vartheta}_{n, 1})} + (\hat{\vartheta}_{n, 2}(X) - \eta_2)^2 \cdot \frac{\hat{\vartheta}_{n, 3}(X)}{\hat{\vartheta}_{n, 2}(X)(1 - \hat{\vartheta}_{n, 2})} \right)
$$

bzw.

$$
	B_n^W(X) := \{ \eta \in (0, 1)^2 \mid T_{\eta, n}^W(X) \lt \chi_{2, 1-\alpha}^2 \}
$$

mit der Wald-Teststatistik $T_{\eta, n}^W(X)$

$$
	T_{\eta, n}^W(X) := n \left( (\hat{\vartheta}_{n, 1}(X) - \eta_1)^2 \cdot \frac{\hat{\vartheta}_{n, 3}(X)}{\eta_1(1-\eta_1)} + (\hat{\vartheta}_{n, 2}(X) - \eta_2)^2 \cdot \frac{\hat{\vartheta}_{n, 3}(X)}{\eta_2(1-\eta_2)} \right)
$$

bzw.

$$
	B_n^{LR}(X) := \{ \eta \in (0, 1)^2 \mid T_{\eta, n}^{LR}(X) \lt \chi_{2, 1-\alpha}^2 \}
$$

mit der Likelihood-Ratio-Teststatistik $T_{\eta, n}^{LR}(X)$

$$
	T_{\eta, n}^{LR}(X) := 2 \left( N_{n, 1, 1} \cdot \log\left( \frac{\hat{\vartheta}_{n, 1}}{\eta_1} \right) + N_{n, 1, 2} \cdot \log\left( \frac{\hat{\vartheta}_{n, 2}}{\eta_2} \right) + N_{n, 2, 1} \cdot \log\left( \frac{\hat{\vartheta}_{n, 1}}{\eta_1} \right) + N_{n, 2, 2} \cdot \log\left( \frac{\hat{\vartheta}_{n, 2}}{\eta_2} \right) \right)
$$

Es gilt
- $\text{arve}_\vartheta(B^P, B^W) = \text{arve}_\vartheta(B^P, B^{LR}) = \text{arve}_\vartheta(B^W, B^{LR}) = 1$