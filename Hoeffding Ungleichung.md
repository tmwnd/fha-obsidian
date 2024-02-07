Sei $\nu$ ein [[In-Sample Error|Stichprobenfehler]], $\mu$ eine unbekannte Wahrscheinlichkeit, $N$ die Stichprobengröße, $\epsilon$ eine akzeptierte Toleranz.

Die *Hoeffding Ungleichung* ist definiert als

$$
	\mathbb{P}[|\nu - \mu| \gt \epsilon] \le 2e^{-2 \epsilon^2 N}
$$

---

Sei $X, y$ ein [[Datensatz]], $h$ eine [[Hypothese]] auf $X, y$, $N = |X|$, $\epsilon$ eine akzeptierte Toleranz.

Die *Hoeffding Ungleichung* ist definiert als

$$
	\mathbb{P}[|E_{\text{in}}(h) - E_{\text{out}}(h)| \gt \epsilon] \le 2e^{-2 \epsilon^2 N}
$$

und hat die Vorraussetzungen
- $h$ wurde festgelegt, bevor Trainingsdaten jemals ausgewertet wurden
- Trainingsdaten wurden zufällig aus einem [[Datensatz]] gezogen

---

Sei $X, y$ ein [[Datensatz]], $g$ die finale [[Hypothese]] von $X, y$, $N = |X|$, $M$ die Anzahl an getesteten [[Hypothese|Hypothesen]], $\epsilon$ eine akzeptierte Toleranz.

Die *Hoeffding Ungleichung* ist definiert als

$$
	\mathbb{P}[|E_{\text{in}}(g) - E_{\text{out}}(g)| \gt \epsilon] \le 2Me^{-2 \epsilon^2 N} = \delta
$$

Es gilt mit einer Wahrscheinlichkeit von $\delta$ für den [[Out-Sample Error]], [[In-Sample Error]]

$$
	E_\text{out}(g) = E_\text{in}(g) + \sqrt{\frac{1}{N} \ln{\frac{2M}{\delta}}}
$$

---

```py
def h(x, w):
	return np.sign(x @ w)
```

```py
eps = np.linspace(0, .8, 9)
nu = h(X)

P = [(np.abs(nu - .5) > e).mean() for e in eps]
H = [2 * np.exp(-2 * e**2 * 10) for e in eps]

ax.plot(eps, P, labeln="$\nu$")
ax.plot(eps, H, c="red", label="Hoeffding Schranke")
```