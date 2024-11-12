#definition #aufrunden #abrunden #satz #beweis 
### Inhalt
- [[#Definition]]
- [[#Satz]]
- [[#Beweis]]
-------
# Definition
Für $\alpha \in \mathbb{R}$ definieren wir $$
\lfloor \alpha \rfloor= z \in\mathbb{Z} \;\text{mit}\;z \leq a < z +1
$$
als "Gauß-Klammer" nach unten $\rightarrow$ abrunden und $$
\lceil \alpha \rceil=z \in\mathbb{Z} \;\text{mit}\;z-1 < a \leq z
$$als "Gauß-Klammer" nach oben $\rightarrow$ aufrunden.

###### Beispiele
- $\lfloor3\rfloor=\lceil3\rceil=3$ 
- $\lceil-\pi \rceil=-3$
- $\lfloor-\pi \rfloor=-4$
- $\lfloor \sqrt{2}\rfloor=1$
- $\lceil \sqrt{2}\rceil=2$

> [!question] Warum brauchen wir das? --> Während in $\mathbb{R}$ bzw. $\mathbb{Q}$ beliebig dividiert werden darf (Achtung: 0!), klappt das in $\mathbb{Z}$ nicht immer. Hier gibt es dafür die "Division mit Rest"

# Satz
Es seien $a,b \in \mathbb{Z}$ mit $b > 0$.
Dann gibt es ganze Zahlen $q,r \in \mathbb{Z}$ mit $$
a=q \cdot b+r\;\text{mit}\;0 \leq r<b
$$
Dabei sind $q$ und $r$ eindeutig bestimmt.

# Beweis
Da $$
\begin{alignat}{}
\lfloor a \rfloor \leq a < \lfloor a \rfloor+1\;\;\;&\mid-\lfloor a \rfloor\\
\Leftrightarrow 0 \leq a - \lfloor a \rfloor < 1 \;\;&\hphantom{-}\forall a \in\mathbb{R}
\end{alignat}
$$Insbesondere gilt dies auch für $\frac{a}{b}$ $$
\begin{alignat}{1}
&0 \leq \frac{a}{b}-\lfloor \frac{a}{b} \rfloor<1\;\;\;\mid \cdot \;b\\
\Leftrightarrow\;&0 \leq a - b \cdot \lfloor \frac{a}{b} \rfloor < b
\end{alignat}
$$Setze nun $q :=\lfloor \frac{a}{b} \rfloor$ mit $r := a- \lfloor \frac{a}{b}\rfloor\cdot b$.
Dann gilt:$$
a=q \cdot b + r = \cancel{b \cdot \lfloor \frac{a}{b} \rfloor}+a-\cancel{\lfloor \frac{a}{b}\rfloor \cdot b}
$$
