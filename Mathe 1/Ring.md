#definition 

# Definition
Eine Menge $R$ zusammen mit den Verknüpfungen $+$ und $\cdot$ heißt **Ring**, falls gilt:
1. ($R, +$) ist abelsche Gruppe
2. ($R, \cdot$) ist Halbgruppe  (das heißt abgeschlossen und assoziativ)
3. Distributivgesetz:$$
\begin{alignat}{1}
&a \cdot(b+c)=a \cdot b+a \cdot c\;\;\;\text{und}\\
&(a+b)\cdot c=a \cdot b+a \cdot c
\end{alignat}
$$
	(Da man, durch die Halbgruppe bei der Multiplikation, nicht von Kommutativität ausgehen darf.)

Gibt es bezüglich der Multiplikation sogar ein neutrales Element, so heißt $R$ ein **Ring mit 1**.
Ist die Multiplikation kommutativ, so heißt $R$ ein **"kommutativer Ring (mit 1)"**. 
Ein *"nullteilerfreier kommutativer Ring mit 1* heißt **"Integritätsbereich"**. Dabei bedeutet **"nullteilerfrei"**, dass aus $a \cdot b=0$ stets $a=0\land b=0$ folgt.
Alle Elemente, die ein multiplikativ inverses besitzen, fasst man zur sogenannten **"Einhetengruppe"** $R^*$ bzw. $R^x$ zusammen.$$
R^*=\{r \in R \mid \exists r^{-1} \in \mathbb{R}\;\text{mit}\;r \cdot r^{-1}=1\}
$$
Es ergibt sich somit aus $Q^* \rightarrow Q \setminus \{0\}$.
($R^*, \cdot$) ist tatsächlich eine Gruppe.

#### Beispiel
a) ($\mathbb{Z},+,\cdot$) ist ein Integritätsbereich ("integral-domain")

b) ($\mathbb{Z}_m,+,\cdot$) ist ein kommutativer Ring mit $1$, aber <u>nicht</u> nullteilerfrei 
($\mathbb{Z}_{4}:\;\;\;2\cdot2=0$)

c) $\mathbb{Z}^*_{4}=\{1,3\}$   $\mathbb{Z}^*=\{1,-1\}$

