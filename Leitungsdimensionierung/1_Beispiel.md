# Einfaches Beispiel

Für eine Brauerei soll eine kleine Abfüllanlage angeschlossen werden. Der Hersteller gibt ihnen einen Anschlussleistung von $8,2 \text{kW}$ an. Die Anlage soll einphasig angeschlossen werden. Bestimmen Sie den notwendigen Leitungsquerschnitt mit Betrachtung des Spannungsfall ($l=67\text{m}$). Die Leitung wird alleine auf einer Kabeltrasse verlegt. In der Halle beträgt die Temperatur 15°C.

## Allgemeine Vorgehensweise

1. Den Betriebsstrom $I_b$ berechnen.
2. Referenzverlegeart bestimmen.
3. Reduktionsfaktoren bestimmen.
4. Nennstrom $I_N$ festlegen.
5. Bestimmen der Strombelastbarkeit $I_z$ für verschiedene Querschnitte $q$.
6. Spannungsfall betrachten.

# 1. Betriebsstrom

### Aufgabe

Für eine Brauerei soll eine kleine Abfüllanlage angeschlossen werden. Der Hersteller gibt ihnen einen Anschlussleistung von $8,2 \text{kW}$ an. Die Anlage soll einphasig angeschlossen werden. Bestimmen Sie den notwendigen Leitungsquerschnitt mit Betrachtung des Spannungsfall ($l=67\text{m}$). Die Leitung wird alleine auf einer Kabeltrasse verlegt. In der Halle beträgt die Temperatur 15°C.

### Lösung

Im ersten Schritt muss der Betriebsstrom $I_b$ berechnet werden. Der Betriebsstrom kann aus der **Leistung** und der Netzspannung $230 \text{V}$ berechnet werden.

[x] $I_b$ = $\frac{8200 \text{W}}{230 \text{V}}$ = $36\text{A}$

[] $I_b$ = $\frac{230 \text{V}}{8200 \text{W}}$ = $0,03\text{A}$

[]  $I_b$ = $230 \text{V} \cdot 8,2 \text{kW}$ = $1889\text{A}$

# 2. Referenzverlegeart

### Aufgabe

Für eine Brauerei soll eine kleine Abfüllanlage angeschlossen werden. Der Hersteller gibt ihnen einen Anschlussleistung von $8,2 \text{kW}$ an. Die Anlage soll einphasig angeschlossen werden. Bestimmen Sie den notwendigen Leitungsquerschnitt mit Betrachtung des Spannungsfall ($l=67\text{m}$). Die Leitung wird alleine auf einer Kabeltrasse verlegt. In der Halle beträgt die Temperatur 15°C.

**Ergebnisse:**

| Größe               | Wert          |
| ------------------- | ------------- |
| Betriebsstrom $I_b$ | $36 \text{A}$ |

### Erklärung

In der DIN kann nicht jeder erdenklicher Fall behandelt werden, wie eine Leitung verlegt werden kann. Z.B. IM Holzfußboden, in der Betonwand, auf eine Kabeltrasse, ... . Daher gibt es sogenannten Referenzverlegeart nach den dimensioniert wird. Man sucht sich entsprechend einer Tabelle die passende Verlagert aus:

| Referenzverlegeart | Beschreibung                                                 |
| ------------------ | ------------------------------------------------------------ |
| A1                 | Aderleitungen in wärmegedämmten Wänden                       |
| A2                 | mehradrige Mantelleitungen in wärmegedämmten Wänden          |
| B1                 | Aderleitungen im Elektroinstallationsrohr/-kanal             |
| B2                 | Mantelleitung im Elektroinstallationsrohr/-kanal             |
| C                  | Auf einer Wand, nicht gelochte Kabelwannen                   |
| D                  | Kabel und Leitungen in der Erde (Ähnlich A2)                 |
| E                  | gelochte Kabelwannen, Kabelkonsolen, Kabelpritschen,  Trageseile |
| F, G               | Frei in der Luft                                             |

**Hinweis:** Die Tabelle ist stark vereinfacht. Ich empfehle ihnen in ihrem Tabellenbuch nach den genauen Beschreibungen zu suchen.

Kabeltrassen können, sowohl Kabelwannen, Kabelkonsolen und Kabelpritschen sein. In unserem Fall sollen es aber eine Kabelwannen mit **ausreichenden großen Löcher** sein.

### Lösung

Entnehmen Sie der Tabelle die Referenzverlegeart.

[] Verlegeart: A1

[] Verlegeart: A2

[] Verlegeart: B1

[] Verlegeart: B2

[] Verlegeart: C

[] Verlegeart: D

[x] Verlegeart E

[] Verlegeart: E

[] Verlegeart: F

[] Verlegeart: G

# 3. Reduktionsfaktoren

### Aufgabe

Für eine Brauerei soll eine kleine Abfüllanlage angeschlossen werden. Der Hersteller gibt ihnen einen Anschlussleistung von $8,2 \text{kW}$ an. Die Anlage soll einphasig angeschlossen werden. Bestimmen Sie den notwendigen Leitungsquerschnitt mit Betrachtung des Spannungsfall ($l=67\text{m}$). Die Leitung wird alleine auf einer Kabeltrasse verlegt. In der Halle beträgt die Temperatur 15°C.

**Ergebnisse:**

| Größe               | Wert          |
| ------------------- | ------------- |
| Betriebsstrom $I_b$ | $36 \text{A}$ |
| Referenzverlegeart  | E             |

### Erklärung

Es gibt eine Vielzahl von Faktoren, welche die Strombelastbarkeit einer Leitung beeinflussen. Wir unterscheiden in vier Faktoren: $f_1$ bis $f_4$:

| Reduktionsfaktoren | Beschreibung                                                 |
| ------------------ | ------------------------------------------------------------ |
| $f_1$              | Umgebungstemperatur                                          |
| $f_2$              | Leitungshäufung (Anzahl von Leitungen)                       |
| $f_3$              | Anzahl der belasteten Adern ($ 230 \text{V}$ = 2 Ader, $ 400 \text{V}$ = 3 Ader) |
| $f_4$              | Oberschwingungen                                             |

Für die vier Faktoren gibt es eine viel zahl von Tabellen:

**Reduktionsfaktor** $f_1$:

| Umgebungstemperatur | Faktor $f_1$ |
| ------------------- | ------------ |
| $10\text{°C}$       | $1,22$       |
| $15\text{°C}$       | $1,17$       |
| $20\text{°C}$       | $1,12$       |
| $30\text{°C}$       | $1,00$       |
| $40\text{°C}$       | $0,87$       |
| $50\text{°C}$       | $0,71$       |

**Reduktionsfaktor** $f_2$:

Ist bei **einer** Leitung immer $f_2 = 1$. Bei mehreren Leitungen muss die Verlegeart und Verlegeanordnung berücksichtigt werden.

**Reduktionsfaktor** $f_3$:

| Belastete Adern | 2     | 3     | 5      | 7      | 10     | 14    | 19     | 24    |
| --------------- | ----- | ----- | ------ | ------ | ------ | ----- | ------ | ----- |
| Faktor $f_3$    | $1,0$ | $1,0$ | $0,75$ | $0,65$ | $0,55$ | $0,5$ | $0,45$ | $0,4$ |

**Reduktionsfaktor** $f_4$:

| Oberschwingungsanteil | 0% - 10% | 11% - 22% | 23% - 30% | 31% - 34% | 35%  - 38% | 39% - 41% |
| --------------------- | -------- | --------- | --------- | --------- | ---------- | --------- |
| Faktor $f_4$          | $1,0$    | $0,86$    | $0,70$    | $0,67$    | $0,61$     | $0,56$    |

**Hinweis:** In vielen Fällen ist der Faktor $f_4$ = 1. So zum Beispiel wenn nichts anderes angegeben ist.

### Hinweis

Die Tabellen können sich nach Anwendungsfall und Tabellenbuch unterscheiden!

### Lösung

Bestimmen Sie die Reduktionsfaktoren $f_1$ bis $f_4$:

[] $f1 = 1,22$  $f_2 = 0,78$ $f_3 = 1,00$ $f_4 = 1,0$

[] $f1 = 1,12$  $f_2 = 1,0$ $f_3 = 0,75$ $f_4 = 0,86$

[x] $f1 = 1,17$  $f_2 = 1,0$ $f_3 = 1,0$ $f_4 = 1,0$

[] $f1 = 1,17$  $f_2 = 1,0$ $f_3 = 1,00$ $f_4 = 0,86$

# 4. Nennstrom festlegen

### Aufgabe

Für eine Brauerei soll eine kleine Abfüllanlage angeschlossen werden. Der Hersteller gibt ihnen einen Anschlussleistung von $8,2 \text{kW}$ an. Die Anlage soll einphasig angeschlossen werden. Bestimmen Sie den notwendigen Leitungsquerschnitt mit Betrachtung des Spannungsfall ($l=67\text{m}$). Die Leitung wird alleine auf einer Kabeltrasse verlegt. In der Halle beträgt die Temperatur 15°C.

**Ergebnisse:**

| Größe                | Wert          |
| -------------------- | ------------- |
| Betriebsstrom $I_b$  | $36 \text{A}$ |
| Referenzverlegeart   | E             |
| Anzahl der Leitungen | 2             |
| $f_1$                | $1,17$        |
| $f_2$                | $1,0$         |
| $f_3$                | $1,0$         |
| $f_4$                | $1,0$         |

### Erklärung

Der Nennstrom $I_N$ bestimmt den Leistungsschutzschalter (LS). Dabei ist der Nennstrom der Strom, welcher dauerhaft fließen kann ohne das der LS auslöst.

![Leistungsschutzschalter](https://upload.wikimedia.org/wikipedia/commons/f/fd/Jtecul.jpg)

Leitungsschutzschalter gibt es mit vielen Nennströme. Die nachfolgende Tabelle listet die gebräuchlichsten auf Nennströme auf:

| Nennstrom $I_N$ |
| --------------- |
| $6 \text{A}$    |
| $10 \text{A}$   |
| $13 \text{A}$   |
| $16 \text{A}$   |
| $20 \text{A}$   |
| $25 \text{A}$   |
| $32 \text{A}$   |
| $40 \text{A}$   |
| $50 \text{A}$   |
| $63 \text{A}$   |
| $80 \text{A}$   |

Bei der Festlegung der des Nennstromes muss folgende Bedingung gelten:

$I_b \le I_N$.

Also muss der **Betriebsstrom kleiner gleich des Nennstroms** sein. Dabei empfiehlt es sich den Nennstrom nicht größer als notwendig zu wählen.

### Lösung

[] $I_N = 6 \text{A}$

[] $I_N = 32 \text{A}$

[x] $I_N = 40 \text{A}$

# 5. Strombelastbarkeit bestimmen festlegen

### Aufgabe

Für eine Brauerei soll eine kleine Abfüllanlage angeschlossen werden. Der Hersteller gibt ihnen einen Anschlussleistung von $8,2 \text{kW}$ an. Die Anlage soll einphasig angeschlossen werden. Bestimmen Sie den notwendigen Leitungsquerschnitt mit Betrachtung des Spannungsfall ($l=67\text{m}$). Die Leitung wird alleine auf einer Kabeltrasse verlegt. In der Halle beträgt die Temperatur 15°C.

**Ergebnisse:**

| Größe                | Wert          |
| -------------------- | ------------- |
| Betriebsstrom $I_b$  | $36 \text{A}$ |
| Referenzverlegeart   | E             |
| Anzahl der Leitungen | 2             |
| $f_1$                | $1,17$        |
| $f_2$                | $1,0$         |
| $f_3$                | $1,0$         |
| $f_4$                | $1,0$         |
| Nennstrom $I_N$      | $40 \text{A}$ |

### Erklärung

Um die **Strombelastbarkeit der Leitung** $I_z$ bestimmen zu können muss die **zulässige Strombelastbarkeit der Leitung** $I_r$ aus Tabellen abgelesen werden. Im folgenden ist die Tabelle für die Referenzverlegeart E, 2 belastetet Adern angeben:

| Querschnitt in $\text{mm}^2$ | zulässige Strombelastbarkeit $I_r$ in A |
| ---------------------------- | --------------------------------------- |
| 1,5                          | 22                                      |
| 2,5                          | 30                                      |
| 4                            | 40                                      |
| 6                            | 51                                      |
| 10                           | 70                                      |
| 16                           | 94                                      |
| 25                           | 119                                     |
| 35                           | 148                                     |
| 50                           | 180                                     |
| 70                           | 232                                     |
| 95                           | 282                                     |
| 120                          | 328                                     |

Die Strombelastbarkeit der Leitung $I_z$ berechnet sich wie folgt:

$I_z = I_r \cdot f_1 \cdot f_2 \cdot f_3 \cdot f_4$.

Bei der Auswahl des Querschnittes muss nun folgende Bedingung gelten:

$I_b \le I_N \le I_z$.

Auch hier wählt man nicht unnötig große Leitungsquerschnitte aus.

### Lösung

[] $q = 2,5 \text{mm}^2$ mit $I_r = 30 \text{A}$

[x] $q = 4 \text{mm}^2$ mit $I_r = 40 \text{A}$

[] $q = 6 \text{mm}^2$ mit $I_r = 51 \text{A}$

# Kurze Zusammenfassung

Der Querschnitt $q$ der Leitung muss mindestens $4 \text{mm}^2$ betragen, damit wären Sie für den ersten Schritt fertig. Nun soll aber noch der Spannungsfall betrachtet werden, dieser darf in der Regel nicht größer als $3\%$ der Nennspannung $U_N$ betragen:

| Nennspannung $U_N$ | maximaler Spannungsabfall $\Delta U_{\text{Max}}$       |
| ------------------ | ------------------------------------------------------- |
| $230 \text{V}$     | $230 \text{V} \cdot \frac{3\%}{100\%}$ = $6,9 \text{V}$ |
| $400 \text{V}$     | $400 \text{V} \cdot \frac{3\%}{100\%}$ = $12 \text{V}$  |

In der DIN ist die Betrachtung des Spannungsfall ein **ausdrückliche** Empfehlung. Es kann von dieser Forderung abgesehen werde, wenn z.B. der nötige Querschnitt nicht mehr **ökologisch** und **ökonomisch** vertretbar ist. 

Die bis jetzt berechneten $4 \text{mm}^2$ ist der Mindestquerschnitt der eingehalten werden **muss**.

# 6. Spannungsfall berechnen

### Aufgabe

Für eine Brauerei soll eine kleine Abfüllanlage angeschlossen werden. Der Hersteller gibt ihnen einen Anschlussleistung von $8,2 \text{kW}$ an. Die Anlage soll einphasig angeschlossen werden. Bestimmen Sie den notwendigen Leitungsquerschnitt mit Betrachtung des Spannungsfall ($l=67\text{m}$). Die Leitung wird alleine auf einer Kabeltrasse verlegt. In der Halle beträgt die Temperatur 15°C.

**Ergebnisse:**

| Größe                | Wert            |
| -------------------- | --------------- |
| Betriebsstrom $I_b$  | $36 \text{A}$   |
| Referenzverlegeart   | E               |
| Anzahl der Leitungen | 2               |
| $f_1$                | $1,17$          |
| $f_2$                | $1,0$           |
| $f_3$                | $1,0$           |
| $f_4$                | $1,0$           |
| Nennstrom $I_N$      | $40 \text{A}$   |
| Mindestquerschnitt   | $4 \text{mm}^2$ |

### Erklärung

Der Spannungsfall bestimmt die Leistung, welche noch am Verbraucher zur Verfügung steht. Je länger die Leitung ist, um so weniger Leistung steht zur Verfügung.

Der einfache Spannungsfall $\Delta U$ kann über folgende Gleichung berechnet werden:

$\Delta U$ = $\frac{2\cdot l \cdot I \cdot \cos{\varphi}}{\varkappa \cdot q}$ = $\frac{2\cdot l \cdot I \cdot \cos{\varphi}}{\gamma \cdot A}$

Es muss folgende Bedingung gelten:

$\Delta U \le \Delta U_{\text{Max}}$.

| Nennspannung   | maximaler Spannungsabfall $\Delta U_{\text{Max}}$     |
| -------------- | ----------------------------------------------------- |
| $230 \text{V}$ | $230 \text{V} \cdot \frac{3\%}{100\%} = 6,9 \text{V}$ |
| $400 \text{V}$ | $400 \text{V} \cdot \frac{3\%}{100\%} = 12 \text{V}$  |

Je nach Tabellenbuch gibt es zwei Varianten der Gleichung, die erste Variante mit $\varkappa$ als spezifische Leitfähigkeit  und $q$ als Querschnitt. Die zweite Variante verwendet $\gamma$ für die spezifische Leitfähigkeit und $A$ als Querschnitt. Beide Varianten sind richtig:

Die spezifische Leitfähigkeit ist eine Materialeigenschaft des Leiters, für Kupfer beträgt $\varkappa$, $\gamma$:

$\varkappa = \gamma = 56 \frac{\text{S} \cdot \text{m}}{\text{mm}^2}$ 

$\cos{\varphi}$ wird als Leistungsfaktor bezeichnet, wenn nichts anderes geben ist  $\cos{\varphi} =  1$.

$I$ ist der der Strom der durch die Leitung fließt. Dabei haben wir vier Ströme zur Verfügung: $I_b$, $I_N$, $I_r$ und $I_z$. Die Ströme $I_r$ und $I_z$ sind nur für die Berechnung notwendig, diese werden durch den LS im Normalbetrieb nicht erreicht. Für die Berechnung kann der Betriebsstrom $I_b$ und der Nennstrom $I_N$ verwendet werden. 

**Meine Empfehlung** ist den Nennstrom $I_N$ als Rechnungsgrund zu verwenden, weil damit nehmen Sie den größten Strom an der dauerhaft fließen kann. Das kann z.B. wichtig werden, wenn das Geräte ausgetauscht werden und der neue Betriebsstrom größer wird. $I_N$ kann aber zu einem noch größeren Querschnitt führen, daher kann der kleinere Strom $I_b$ benutzt werde. 

### Lösung

Berechnen Sie die Querschnitt für den Spannungsfall. Verwenden Sie dafür die Nennstrom $I_N$.

[] $q = 4 \text{mm}^2$

[] $q = 6 \text{mm}^2$

[] $q = 10 \text{mm}^2$

[x] $q = 16 \text{mm}^2$

[] $q = 25 \text{mm}^2$

# Zusammenfassung Ergebnisse

Sie haben in diesem kurzen Beispiel erfolgreich den Leitungsquerschnitt für eine Abfüllanlage berechnet. Dabei sind haben sie eine Mindestquerschnitt von $4\text{mm}^2$ heraus bekommen und mit Betrachtung des Spannungsfalls einen Querschnitt $16 \text{mm}^2$.  