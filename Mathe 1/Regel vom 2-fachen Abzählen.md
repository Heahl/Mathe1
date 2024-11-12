#satz #beweis #beispiel

## Satz
Es seien im Folgenden $S$ und $T$ zwei Mengen, sowie $I$ eine Inzidenzrelation zischen $S$ und $T$.
Ein einfaches Beispiel liefert die Geometrie:
		$S$ = Menge von Punkten
		T = Menge von Geraden

Für $P \in S$ und $g \in T$ gilt dann:
$$
P \in g \;\;\;\Leftrightarrow\;\;\;\mathsf{Punkt}\;P\;\mathsf{liegt\;auf\;der\;Geraden}\;g
$$
Ist nun $a \in S$, so bezeichnen wir mit $r(a)$ die Anzahl der zu $a$ inzidenten Elemente aus $T$.
Umgekehrt ist für $b \in T$ die Zahl $r(b)$ die Anzahl der zu $b$ inzidenten Elemente aus $S$.

<u>Dann gilt:</u>
$$
\sum_{a \in S}r(a)=\sum_{b \in T}r(b)
$$

### Beweis
Sei $S =\{a_1,a_2,a_3,\dots,a_m\},\;T=\{b_1,b_2,\dots,b_n\}$
![[Pasted image 20241016144303.png]]

Wir schreiben:
$$k_{ij} = \left\{
\begin{matrix}
1, & a_i\; I(\rightarrow \text{ist inzident})\; b_j \\
0, & \text{sonst}
\end{matrix}
\right.
$$

Dann gilt:
$$
\begin{alignat}{1}
r(a_i)&=\text{Anzahl der 1-en in der i-ten Zeile}\\
r(b_j)&=\text{Anzahl der 1-en in der j-ten Spalte}\\
\Rightarrow \sum_{a \in S}r(a)&=\text{Anzahl aller 1-en (Zeilenweise gezählt)}\\
&\text{Anzahl aller 1-en (Spaltenweise gezählt)}=\sum_{b \in T}r(b)
\end{alignat}
$$
###### Beispiel
Von 6 angebotenen Vorlesungen im Wahlbereich muss jeder Studierende 2 besuchen.
Die Hörerzahlen sind 30, 50, 40, 22, 18 und 34.
Wie viele Studierende gibt es insgesamt?
$S =$ Menge der Studenten $= \{s_1,s_2,s_3,\dots,s_n\}$ (das $n$ wird gesucht)
$T =$ Menge der Vorlesungen $= \{V_1,V_2,V_3,V_4,V_5,V_6\}$
![[Pasted image 20241017122849.png]]

