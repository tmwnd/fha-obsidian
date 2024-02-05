Sei $\nu$ ein [[In-Sample Error|Stichprobenfehler]], $\mu$ eine unbekannte Wahrscheinlichkeit, $N$ die Stichprobengröße, $\epsilon$ eine akzeptierte Toleranz.

Die *Hoeffding Ungleichung* ist definiert als

$$
	\mathbb{P}[|\nu - \mu| \gt \epsilon] \le 2e^{-2 \epsilon^2 N}
$$

---

Sei $h$ eine [[Hypothese]] eines [[Datensatz|Datensatzes]], $N$ die Größe eines [[Datensatz|Datensatzes]], $\epsilon$ eine akzeptierte Toleranz.

Die *Hoeffding Ungleichung* ist definiert als

$$
	\mathbb{P}[|E_{\text{in}}(h) - E_{\text{out}}(h)| \gt \epsilon] \le 2e^{-2 \epsilon^2 N}
$$

und hat die Vorraussetzungen
- $h$ wurde festgelegt, bevor Trainingsdaten jemals ausgewertet wurden
- Trainingsdaten wurden zufällig aus einem [[Datensatz]] gezogen

---

Sei $g$ die finales [[Hypothese]] eines [[Datensatz|Datensatzes]], $N$ die Größe eines [[Datensatz|Datensatzes]], $M$ die Anzahl an getesteten [[Hypothese|Hypothesen]], $\epsilon$ eine akzeptierte Toleranz.

Die *Hoeffding Ungleichung* ist definiert als

$$
	\mathbb{P}[|E_{\text{in}}(g) - E_{\text{out}}(g)| \gt \epsilon] \le 2Me^{-2 \epsilon^2 N}
$$