Sei $f \in C^1(\mathbb{R}^d)$ [[Konvexe Funktion|konvex]], $f_* = \inf f$, $(f_t)_{t \in \mathbb{N}} \in C^1(\mathbb{R}^d)$, $(x_t)_{t \in \mathbb{N}} \in \mathbb{R}^d$, $(\gamma_t)_{t \in \mathbb{N}} \in \mathbb{R}^d$ mit
- $\lim_{t \to \infty} f_t - f_* = 0$
- $\exists x_* \in \mathbb{R^d} : \lim_{t \to \infty} \| x_t - x_* \| = 0$

Der $t$-te Schritt des *Gradientenverfahrens* ist definiert als

$$
	x_{t+1} = x_t - \gamma_tf_t'
$$

---

| $f$ [[Konvexe Funktion\|konvex]] | $f$ [[Libschitz-Stetigkeit\|L-stetig]] | $f$ [[L-Glattheit\|L-glatt]] | $f$ $\mu$-[[mu-Stetigkeit\|konvex]] | $\gamma$ | $T$ |
|--|--|--|--|--|--|
| x | x ||| $\gamma = \frac{c}{\sqrt{T}}$ | $T \in \mathcal{O}(\frac{1}{\varepsilon^2})$
| x || x || $0 \lt \gamma \lt \frac{2}{L}$ | $T \in \mathcal{O}(\frac{1}{\varepsilon})$
| x || x | x | $0 \lt \gamma \lt \frac{1}{L}$ | $T \in \mathcal{O}(\log(\frac{1}{\varepsilon}))$

---

Sei $f \in C^1(\mathbb{R}^d)$ [[Konvexe Funktion|konvex]], $f_* = \inf f$, $T \in \mathbb{N}$, $(f_t)_{t \in \{ 0, \dots, T-1\}} \in C^1(\mathbb{R}^d)$, $(x_t)_{t \in \{ 0, \dots, T-1\}} \in \mathbb{R}^d$, $\gamma \in \mathbb{R}$ mit
- $\lim_{t \to \infty} f_t - f_* = 0$
- $\exists x_* \in \mathbb{R^d} : \lim_{t \to \infty} \| x_t - x_* \| = 0$
- $\hat{t} = \arg\min_{t \in \{ 0, \dots, T-1 \}} (f_t - f_*)$.

Es gilt

$$
	f_\hat{t} - f_* \le \underbrace{\frac{1}{T} \sum_{t=0}^{T-1} (f_t - f_*)}_{\text{mittlere Abweichung von } f_*} \le \frac{\gamma}{2}\underbrace{\frac{\sum_{t=0}^{T-1} \| f_t' \|_2^2}{T}}_\text{mittlerer Gradient} + \frac{1}{2\gamma}\overbrace{\underbrace{\frac{\| x_0 - x_* \|_2^2 - \| x_T - X_* \|_2^2}{T}}_\text{Startfehler}}^{e_0}
$$

---

Sei $f \in C^1(\mathbb{R}^d)$ [[Konvexe Funktion|konvex]] und [[Libschitz-Stetigkeit|L-stetig]], $f_* = \inf f$, $T \in \mathbb{N}$, $(f_t)_{t \in \{ 0, \dots, T-1\}} \in C^1(\mathbb{R}^d)$, $(x_t)_{t \in \{ 0, \dots, T-1\}} \in \mathbb{R}^d$, $c \gt 0$, $\omega \in (0, 1)$, $\gamma = \frac{c}{T^\omega}$ mit
- $\lim_{t \to \infty} f_t - f_* = 0$
- $\exists x_* \in \mathbb{R^d} : \lim_{t \to \infty} \| x_t - x_* \| = 0$
- $\hat{t} = \arg\min_{t \in \{ 0, \dots, T-1 \}} (f_t - f_*)$.

Es gilt

$$
	f_\hat{t} - f_* \le \frac{1}{T} \sum_{t=0}^{T-1} (f_t - f_*) = \mathcal{O}\left(\left( \frac{1}{T} \right)^{\min(\omega, 1-\omega)} \right)
$$

Falls $e_0 = \| x_0, x_* \|_2$ und $\gamma = \frac{e_0}{L_f\sqrt{T}}$ gilt

$$
	f_\hat{t} - f_* \le \frac{1}{T} \sum_{t=0}^{T-1} (f_t - f_*) \le \frac{L_fe_0}{\sqrt{T}}
$$

Sei $\varepsilon$ die geforderte Genauigkeit.

Es gilt

$$
	T \ge \left( \frac{e_0}{L_f\varepsilon} \right)^2 \implies f_\hat{t} - f_* \le \varepsilon
$$

mit $\mathcal{O}(\frac{1}{\varepsilon^2})$

---

Sei $f \in C^1(\mathbb{R}^d)$ [[Konvexe Funktion|konvex]] und [[L-Glattheit|L-glatt]], $f_* = \inf f$, $T \in \mathbb{N}$, $(f_t)_{t \in \{ 0, \dots, T-1\}} \in C^1(\mathbb{R}^d)$, $(x_t)_{t \in \{ 0, \dots, T-1\}} \in \mathbb{R}^d$, $c \gt 0$, $\omega \in (0, 1)$, $0 \lt \gamma \lt \frac{2}{L}$ mit
- $\lim_{t \to \infty} f_t - f_* = 0$
- $\exists x_* \in \mathbb{R^d} : \lim_{t \to \infty} \| x_t - x_* \| = 0$
- $\hat{t} = \arg\min_{t \in \{ 0, \dots, T-1 \}} (f_t - f_*)$

$$
	f_T - f_* \le \frac{1}{T+1}\left( \frac{\gamma}{2\beta}(f_0 - f_*) + \frac{1}{2\gamma} \| x_0 - x_* \|_2^2 \right) = \mathcal{O}\left( \frac{1}{T} \right)
$$

Sei $\varepsilon$ die geforderte Genauigkeit.

Es gilt

$$
	T \ge \frac{1}{\varepsilon}\left( \frac{\gamma}{2\beta} (f_0 - f_*) + \frac{1}{2\gamma} \| x_0 - x_* \|_2^2 \right) - 1 \implies f_T - f_* \le \varepsilon
$$

mit $\mathcal{O}(\frac{1}{\varepsilon})$

---

Sei $f \in C^1(\mathbb{R}^d)$ [[Konvexe Funktion|konvex]], [[L-Glattheit|L-glatt]] und $\mu$-[[mu-konvexe Funktion|konvex]], $f_* = \inf f$, $T \in \mathbb{N}$, $(f_t)_{t \in \{ 0, \dots, T-1\}} \in C^1(\mathbb{R}^d)$, $(x_t)_{t \in \{ 0, \dots, T-1\}} \in \mathbb{R}^d$, $c \gt 0$, $\omega \in (0, 1)$, $0 \lt \gamma \lt \frac{1}{L}$ mit
- $\lim_{t \to \infty} f_t - f_* = 0$
- $\exists x_* \in \mathbb{R^d} : \lim_{t \to \infty} \| x_t - x_* \| = 0$
- $\hat{t} = \arg\min_{t \in \{ 0, \dots, T-1 \}} (f_t - f_*)$
- $\rho = 1 - \gamma\mu \in [0, 1)$

$$
	f_T - f_* \le \frac{L}{2} \rho^T \| x_0 - x_* \|_2^2
$$

Sei $\varepsilon$ die geforderte Genauigkeit.

Es gilt

$$
	T \ge \frac{1}{|\log(\rho)|} \left( \log \left( \frac{L}{2} \| x_0 -x_* \|_2^2 \right) + \log \left( \frac{1}{\varepsilon} \right)\right) \implies f_T - f_* \le \varepsilon
$$

mit $\mathcal{O}(\log(\frac{1}{\varepsilon}))$

---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Daten-Paare, $l$ eine differenzierbare [[Loss-Funktion]], $w^{(0)} \in \mathbb{R}^n$, $\gamma^{(k)} \ge 0$ die Schrittlänge.

Die $k$-te Iteration des *Gradientenverfahrens* ist definiert als

$$
	w^{(k+1)} = w^{(k)} - \gamma^{(k)}l'\left( w^{(k)} \right)
$$