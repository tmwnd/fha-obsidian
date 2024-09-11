Seien $(\mathcal{N}_d(\mu, \Sigma))_{\mu \in \mathbb{R}^d, \Sigma \in \mathcal{P}_d}$ [[zettel/Zufallsvariable|Zufallsvariablen]], $1-\alpha$ das vorgegebene Konfidenzniveau, $B_n(X) := \{ \eta \in \mathbb{R}^d \mid n(\overline{X}_n - \eta)^TS_n^{-1}(\overline{X}_n - \eta) \lt \frac{nd}{n-d} F_{d, n-d, 1-\alpha} \}$ ein [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]].

Das erwartete Volumen von $B_n$ ist definiert als

$$
	\lim_{n \to \infty} n^{\frac{d}{2}}\text{E}_\vartheta := \frac{(\chi_{d, 1-\alpha}^2)^\frac{d}{2}\pi^\frac{d}{2}}{\Gamma(\frac{d}{2}+1)} \det(\Sigma)^\frac{1}{2}
$$