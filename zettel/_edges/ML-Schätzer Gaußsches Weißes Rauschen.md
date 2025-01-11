Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ von $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{GWN}(0, \sigma^2)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]], $\Gamma_n :=\text{E}[XX^T]$.

Es gllt
- die Dichte von $(X_t)_{t \in \mathbb{Z}}$ ist definiert als

$$
	\forall x \in \mathbb{R}^n : f(x, \Gamma_n) := \frac{1}{\sqrt{2\pi}^n \det(\Gamma_n)} \cdot \exp\left( -\frac{1}{2} x^T \Gamma_n^{-1} x \right)
$$

Der ML-Schätzer $\hat{\phi}, \hat{\vartheta}, \hat{\sigma}^2$ für $\phi, \vartheta, \sigma^2$ ist definiert als

$$
	\hat{\phi}, \hat{\vartheta}, \hat{\sigma}^2 := \underset{\hat{\sigma}^2 \in \mathbb{R}_0^+, \hat{\phi} \in \mathbb{R}^p, \hat{\vartheta} \in \mathbb{R}^q}{\arg\max} f((x_t)_{t \in \mathbb{Z}} \mid \Gamma_n) = \underset{\hat{\sigma}^2 \in \mathbb{R}_0^+, \hat{\phi} \in \mathbb{R}^p, \hat{\vartheta} \in \mathbb{R}^q}{\arg\max} = \prod_{t \in \mathbb{Z}} f(x_t \mid \Gamma_n)
$$