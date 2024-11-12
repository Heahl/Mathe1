#definition #beweis 

Analog zum Übergang $\mathbb{N}_0\rightarrow\mathbb{Z}$ wollen wir nun auch den Übergang $\mathbb{Z}\rightarrow\mathbb{Q}$ über eine Äquivalenzrelation realisieren. Wir wissen bereits: $$
\mathbb{Q}=\{\frac{a}{b}\mid a \in\mathbb{Z},b \in \mathbb{N}\}=\{\frac{a}{b}\mid a,b \in\mathbb{Z},b \neq0\}
$$
Da die Division durch $0$ nicht definiert ist (denn $a \cdot0=b \cdot0 \nRightarrow a=b$), schließen wir $0$ zunächst aus, betrachten also $\mathbb{Q}^*=\mathbb{Q} \setminus\{0\}$.

# Definition
Auf der Menge $\mathbb{Z} \setminus \{0\}\times\mathbb{Z}\setminus\{0\}$ defineren wir:$$
(a,b)\sim(c,d) \Leftrightarrow a \cdot d=b \cdot c
$$
Hiebei handelt es sich um eine Äquivalenzrelation.

# Beweis
Reflexivität:$$
(a,b)\sim(b,a) \Rightarrow a \cdot b=b \cdot a \;\;\;\checkmark
$$
Symmetrie:$$
\begin{alignat}{1}
(a,b)\sim(c,d)&\Leftrightarrow a \cdot d=b \cdot c\\
&\Leftrightarrow b \cdot c = a \cdot d\\
&\Leftrightarrow c \cdot b=d \cdot a\\
&\Leftrightarrow (c,d)\sim(a,b)\;\;\;\checkmark
\end{alignat}
$$
Transitivität:$$
(a,b)\sim(c,d)\land(c,d)\sim(e,f)\stackrel{!}{\Rightarrow}(a,b)\sim(e,f)
$$
$$
\begin{alignat}{1}
(a,b)\sim(c,d)\land(c,d)\sim(e,f)&\Leftrightarrow a \cdot d = b \cdot c\;\;\;\mid \cdot f\;\;\;&&\land\;\;\;c \cdot f=d \cdot e\;\;\;\mid \cdot b\\
&\Leftrightarrow a \cdot d \cdot f = b \cdot c \cdot f &&\land\;\;\;b \cdot c \cdot f=b \cdot d \cdot e\\
&\Leftrightarrow a \cdot d \cdot f=b \cdot d \cdot e\\
&\Leftrightarrow a \cdot f = b \cdot e\\
&\Leftrightarrow (a,b) \sim (e,f)\;\;\;\checkmark
\end{alignat}
$$
$\square$

Als Äquivalenzklassen ergeben sich:$$
(\overline{a,b})=\{(m,n) \in \mathbb{Z} \setminus\{0\}\times\mathbb{Z}\mid(m,n)\sim(a,b)\}
$$
Diese fassen wir zusammen zur Menge $$
\mathbfsfup{Q}^*:=\{(\overline{a,b})\mid a,b \in\mathbb{Z} \setminus \{0\}\}
$$
