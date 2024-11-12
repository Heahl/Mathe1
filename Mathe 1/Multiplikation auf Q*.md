#definition #satz #beweis 

- [[#Definition]]
- [[#Satz]]
- [[#Beweis]]
---
# Definition
Auf $Q^*$ defineren wir nun eine Multiplikation $\odot$ als:$$
(\overline{a,b})\odot(\overline{c,d})=(\overline{a \cdot c,b \cdot d})
$$
Auch hier muss die Wohldefiniertheit gezeigt werden. Ebenfalls gelten Assoziativgesetz und Kommutativgesetz.
> [!info] Dieses Thema wird in Übung 6 behandelt.

### Bemerkung
In $\mathbb{Q}^*$ können wir nun beliebige Gleichungen der Form $$
(\overline{a,b})\odot x =(\overline{c,d})
$$
lösen, denn für $$
x=(\overline{c,d})\odot(\overline{b,a})
$$
gilt: $$
(\overline{a,b})\odot[(\overline{c,d})\odot(\overline{b,a})]=(\overline{a \cdot c \cdot b,b \cdot d \cdot a})\stackrel{?}{=}(\overline{c,d})
$$
Prüfe also ob $$
(a \cdot c \cdot b,b \cdot d \cdot a)\stackrel{?}{\sim}(\overline{c,d})
$$
Ja, denn $$
a \cdot c \cdot b \cdot d = b \cdot d \cdot a \cdot c \;\;\;\checkmark
$$
# Satz
Es gilt: $$
(Q^*,\odot)\stackrel{\sim}{=}(\mathbb{Q}^*,\cdot)
$$
# Beweis
Offenbar stellen die Äquivalenzklassen von $Q^*$ nichts anderes als Bruchzahlen dar: $$
(\overline{a,b})=\frac{a}{b}
$$
Der Übergang von einem Repräsentanten zum Anderen ist nichts anderes als Kürzen bzw. Erweitern:$$
\begin{array}{ccccccccc} (\overline{2,4}) & = & (\overline{1,2}) & = & (\overline{3,6}) & = & (\overline{4,8}) & = & \dots \\ \widehat{=} & & \widehat{=} & & \widehat{=} & & \widehat{=} & & \hphantom{\dots} \\ \frac{2}{4} & = & \frac{1}{2} & = & \frac{3}{6} & = & \frac{4}{8} & = & \dots \end{array}
$$
Die Multiplikation in $Q^*$ entspricht der üblichen Multiplikation in $\mathbb{Q}^*$:$$
(\overline{a,b})\odot(\overline{c,d})=(\overline{a \cdot c,b \cdot d}) \Leftrightarrow \frac{a}{b}\cdot \frac{c}{d}=\frac{a \cdot c}{b \cdot d}
$$
In beiden Mengen sind die ganzen Zahlen $a \neq 0$ enthalten.$$
a \in \mathbb{Z} \setminus \{0\} \;\;\;\text{entspricht:}\;\;\; (\overline{a,1})\;\widehat{=}\;\frac{a}{1} 
$$
Wir können nun sogar die $0$ einbeziehen!$$
0 \Leftrightarrow \frac{0}{1} \Leftrightarrow (\overline{0,1 })
$$
