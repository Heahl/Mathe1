Wir sagen "a ist kongruent zu b mod m", in Zeichen $$
a \equiv b\;\;\;\text{mod} \;m
$$
wenn $a$ und $b$ bei Division durch $m$ den selben Rest lassen.
<u>Also:</u>
$$
a \equiv b \;\;\;\text{mod} \;m \;\;\;\Leftrightarrow\;\;\;m \mid a-b
$$
#### Beispiel
$$
\begin{alignat}{1}
-5 \equiv 7 \equiv 15\;\;\;\text{mod} \;4\text{, denn}\;-5 &=(-2)\cdot 4+ \underline{\underline{3}}\\
7 &= 1 \cdot 4+\underline{\underline{3}}\\
15&=3 \cdot 4 + \underline{\underline{3}}
\end{alignat}
$$
$$
\text{bzw.}\;\;\;\;\;\;4\mid -5-7\;\;\;\;\;\;4\mid-5-15\;\;\;\;\;\;4\mid7-15
$$
Um genau zu sein, ist die Relation $\sim$ auf $\mathbb{Z}$ mit $$
a \sim b \Leftrightarrow a \equiv b \;\;\;\text{mod}\;m
$$
eine Äquivalenzrelation.

1. Reflexivität:$$
a \sim a: \;\text{klar, denn} \;\;\; a \equiv a \;\;\;\text{mod} \;m
$$
2. Symmetrie:$$
\begin{alignat}{1}
a \sim b &\Leftrightarrow a \equiv b\;\;\;\text{mod}\;m\\
&\Leftrightarrow b \equiv a\;\;\;\text{mod}\;m\\
&\Leftrightarrow b \sim a
\end{alignat}
$$
3. Transitivität:$$
\begin{alignat}{1}
a \sim b \land b \sim c &\Leftrightarrow a \equiv b\;\;\;\text{mod}\;m\;\;\;\land\;\;\;b \equiv c\;\;\;\text{mod}\;m\\
&\Leftrightarrow a \equiv c\;\;\;\text{mod}\;m\\
&\Leftrightarrow a \sim c
\end{alignat}
$$
Als Äquivalenzklassen ergeben sich hier die sogenannten <u>"Restklassen  mod m"</u> $$
\overline{a}=\{b \in \mathbb{Z} \mid b \equiv a\;\;\;\text{mod}\;m\}
$$
#### Beispiel 
$$
\begin{alignat}{1}
m&=4\;\;\;\rightarrow 4 \;\text{mögliche Reste:}\;\;\;0,1,2,3\\
\overline{0}&=\{\dots,-8,-4,0,4,8,\dots\}\\ 
\overline{1}&=\{\dots,-7,-3,1,5,9,\dots\}\\
\overline{2}&=\{\dots,-6,-2,2,6,10,\dots\}\\
\overline{3}&=\{\dots,-5,-1,3,7,11,\dots\}
\end{alignat}
$$

Das Rechnen mit den Restklassen erfolgt wieder Repräsentantenweise:
1. $$
\overline{a}+\overline{b}=\overline{a+b}
$$
2. $$
\overline{a}\cdot \overline{b}=\overline{a \cdot b}
$$

Dies ist wohldefiniert, denn:$$
\begin{alignat}{1}
\text{Sei}\;\overline{a}=\overline{a'}\;\land\;\overline{b}=\overline{b'}&\Rightarrow a \equiv a'\;\;\;\text{mod}\;m\;\;\land\;\;b \equiv b'\;\;\;\text{mod}\;m\\
&\Rightarrow m \mid a-a'\;\;\;\land\;\;\;m \mid b-b'\\
&\Rightarrow m \mid (a-a')+(b-b')\\
&\Rightarrow m \mid (a+b)-(a'+b')\\
&\Rightarrow a+b \equiv a'+b'\;\;\;\text{mod}\;m\\
&\Rightarrow \overline{a+b}=\overline{a'+b'}
\end{alignat}
$$
Multiplikation analog.

Damit lassen sich nun die Verknüpfungstafeln aufstellen.
![[Pasted image 20241112153955.png]]

#### Beispiel
$$
\begin{alignat}{1}
\overline{1}+\overline{3}&=\overline{4}=\{0,\pm4,\pm8,\pm12,\dots\}\\
&=\overline{0}\text{, weil}\;0 \equiv4\;\;\;\text{mod}\;4
\end{alignat}
$$
![[Pasted image 20241112155120.png]]

#### Beispiel
$$
\begin{alignat}{1}
\overline{3}\cdot \overline{3}&=\overline{9}=\{\dots,-3,1,5,9,\dots\}\\
&=\overline{1}\text{, weil}\; 1 \equiv 9\;\;\;\text{mod}\;4
\end{alignat}
$$


Für die Restklassen $\;\;\;\text{mod}\;m$ schreiben wir kurz $\mathbb{Z}_m$.
Wir sehen:
- ($\mathbb{Z}$,+) ist eine abelsche Gruppe
- ($\mathbb{Z} \setminus \{0\},\cdot$) ist keine Gruppe. ($2 \cdot 2 =0 \notin \mathbb{Z}_4 \setminus \{0\} \rightarrow$ <u>nicht</u> abgeschlossen)
								(außerdem hat 2 kein Inverses) 

Allgemein gilt:
- ($\mathbb{Z}_m,+$) ist stets eine abelsche Gruppe.
- ($\mathbb{Z}_p \setminus \{0\},\cdot$) ist nur für $p \in \mathbb{P}$, also Primzahlen, eine abelsche Gruppe.