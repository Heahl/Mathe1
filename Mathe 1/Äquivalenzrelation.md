#definition #beispiel #reflexivität #symmetrie #transitivität #satz #beweis 

## Definition
Es sei $\sim$ eine Relation auf eine Menge $M$. Grundsätzlich interessieren uns dann 3 mögliche Eigenschaften:
1. Reflexivität: $x \sim x$ klar, denn $x =x \;\;\;\forall\;x \in \mathbb{R}$
2. Symmetrie: $x \sim y \Rightarrow y \sim x\;\;\;\forall\;x,y \in M$
3. Transitivität: $x \sim y \land y \sim z \Rightarrow x \sim z\;\;\;\forall\;x,y,z \in M$
Falls **alle drei Eigenschaften** erfüllt sind, nennt man $\sim$ eine **"Äquivalenzrelation"**.

###### Beispiel
Die einfachste Relation ist die Gleichheit: $x \sim y \Leftrightarrow x=y\;\;M \in \mathbb{R}$
1. Reflexivität: $x \sim x$ klar, denn $x=x\;\;\;\forall x \in \mathbb{R}$
2. Symmetrie: $x \sim y \Leftrightarrow x=y \Leftrightarrow y=x \Leftrightarrow y \sim x$
3. Transitivität: $x \sim y \land y \sim z \Rightarrow x=y \land y =z \Rightarrow x=z \Leftrightarrow x \sim z$
$\hookrightarrow$ "=" ist also eine Äquivalenzrelation.
Dagegen ist "$\leq$" <u>keine</u> Äquivalenzrelation (Symmetrie verletzt, $3 \leq 5$ aber $5 \nleq 3$)
Ist $\sim$ eine Äquivalenzrelation, so fasst man alle Elemente von $M$, die zueinander in der Relation $\sim$ stehen, also äquivalent sind, zu einer sogenannten **Äquivalenzklasse** zusammen.
###### Beispiel
Auf $M = \mathbb{Z}$ definieren wir: $x \sim y \Leftrightarrow x$ und $x$ und $y$ lassen bei Division durch $2$ den selben Rest.
1. Zeige $\sim$ ist tatsächlich eine Äquivalenzrelation
	1. Reflexivität: $x \sim x$ klar: $x$ lässt den selben Rest wie $x$.
	2. Symmetrie: $$
\begin{alignat}{1}
x \sim y &\Leftrightarrow x \;\text{lässt den selben Rest wie y}\\
&\Leftrightarrow y \;\text{lässt den selben Rest wie}\;x \Leftrightarrow y \sim x
\end{alignat}
$$
	3. Transitivität: $$
\begin{alignat}{1}
	x \sim y \land y \sim z &\Leftrightarrow x \;\text{und}\;y\;\text{lassen den selben Rest}\\
		&\hphantom{\Leftrightarrow}\;\;y\;\text{und}\;z\;\text{lassen den selben Rest}\\
		&\Rightarrow x\;\text{und}\;z\;\text{lassen den selben Rest}\\
		&\Leftrightarrow x \sim z
\end{alignat}
$$
2. Es ergeben sich folgende Äquivalenzklassen:
	$\{0,\pm2,\pm4,\pm6,\dots\} \;\;\;\;\;\rightarrow \text{Alle geraden Zahlen, lassen Rest}\;0$
	$\{\pm1,\pm3,\pm5,\pm7,\dots\}\;\;\rightarrow\;\text{Alle ungeraden Zahlen, lassen Rest }\;1$
	Wir wählen nun aus jeder Klasse einen Repräsentanten, also eine Art "Stellvertreter" für diese Klasse aus.
		$0 \triangleq \{0,\pm2,\pm4,\dots\}\;\;\;;\;\;\;1\triangleq\{\pm1,\pm3,\pm5,\dots\}$

>[!attention] Äquivalenzklassen sind aufgrund der Transitivität entweder identisch oder disjunkt. 

>[!attention] vereinigt man die sich ergebenden Äquivalenzklassen als Menge, so ergibt sich wieder die Grundmenge.

3. Mit den Äquivalenzklassen beziehungsweise deren Repräsentanten lässt sich auch rechnen:
![[Pasted image 20241017131259.png]]

## Satz
Die auf $\mathbb{N}_0 \times \mathbb{N}_0$ definierte Relation $$
(a,b) \sim(c,d)\;\;\;\Leftrightarrow\;\;\;a+d=b+c
$$
ist eine Äquivalenzrelation.

## Beweis 
1. Reflexivität: $(a,b) \sim^! (a,b)$ klar, denn $a+b=a+b\;\;\;\checkmark$
2. Symmetrie:$$
\begin{alignat}{1}
(a,b)\sim(c,d)&\Leftrightarrow a+d=b+c\\
&\Leftrightarrow b+c=a+d\\
&\Leftrightarrow c+b=d+a\\
&\Leftrightarrow (c,d)\sim(a,b)
\end{alignat}
$$
3. Transitivität: $(a,b) \sim (c,d) \land(c,d) \sim(e,f)$
$$
\begin{alignat}{1}
&\Leftrightarrow a+d=b+c \;\;\;|+e &&\land c+f=d+e\;\;\;|+a\\
&\Leftrightarrow a+d+e=b+c+e \;\;\;&&\land\;a+c+f=a+d+e\\
&\Leftrightarrow b+c+e=a+c+f\\
&\Leftrightarrow b+e= a+f\\
&\Leftrightarrow a+f=b+e &&\Leftrightarrow(a,b)\sim(e,f)
\end{alignat}
$$
Wir erhalten somit also die Äquivalenzklassen:
$$
\begin{alignat}{1}
\{(9,2),(10,3),(8,1),(7,0),(25,18),\dots\}&\triangleq \overline{(7,0)}\\
\{(2,3),(1,2),(0,1),(31,32),\dots\}&\triangleq \overline{(0,1)}
\end{alignat}
$$Eine Veranschaulichung ist über das Koordinatensystem möglich:
![[Pasted image 20241017182531.png]]
Somit sind die einzelnen Äquivalenzklassen "Gerade", die parallel zur Winkelhalbierenden verlauften.
Alle Repräsentanten liegen quasi auf den Achsen.
Wir fassen diese zu einer neuen Menge zusammen:$$
Z:=\{\overline{(a,b)}\mid a,b \in \mathbb{N}_0\}
$$
