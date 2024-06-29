Sei $d(X)$ ein [[zettel/Schätzer|Schätzer]] für $\delta(\vartheta)$.

Als Qualitätskriterium für $d(X)$ eignet sich die *mittlere quadratische Abweichung*

$$
	E_\vartheta(|d(X) - \delta(\vartheta)|^2) = \int |d(x) - \delta(\vartheta)|^2 dP_\vartheta^X(x)
$$

Falls für jedes $\vartheta \in \Theta$ der [[zettel/Erwartungswert|Erwartungswertvektor]] $e(\vartheta) = E_\vartheta(d(X)) \in \mathbb{R}^m$ existiert, gilt

$$
	E_\vartheta(|d(X) - \delta(\vartheta)|^2) = E_\vartheta(|d(x) - e(\vartheta)|^2) + |e(\vartheta) - \delta(\vartheta)|^2
$$