#lotto #wahrscheinlichkeit

Eine Urne enthalte $n$ gleichartige, aber unterscheidbare Kugeln (ähnlich wie beim Lotto). Wir stellen uns die Kugeln also durchnummeriert vor (von $1$ bis $n$).
Nun werden $k$ Kugeln von diesen $n$ gezogen. Dies kann auf 4 Arten geschehen:

![[Pasted image 20241016090034.png]]

### 1. Ziehen mit Reihenfolge, mit Zurücklegen
Ziehungsergebnisse:$$
\{(n_1,n_2,\dots,n_k)\mid n_i \in \{1,\dots,n\},i=1,\dots,k \}
$$
dies ist das k-fache [[Kartesisches Produkt und Potenzmenge|kartesische Produkt]] der Menge $\{1,\dots,k\}\;\;\;\Rightarrow\;\;\;n^k$ Möglichkeiten

<u>Alternative</u>
![[Pasted image 20241016120816.png]]
###### Beispiel Telefonanlage HOST:
-> 03831/45-XXXX
4-stellige Durchwahl, jeweils eine der Ziffern $0,1,\dots,9$ möglich.
$n=10\;\;\;k=4$ mit Reihenfolge und Zurücklegen $\Rightarrow10^4=10.000$ verschiedene Anschlüsse.

### 2. Ziehen mit Reihenfolge, ohne Zurücklegen
![[Pasted image 20241016121208.png]]
###### Beispiel Umordnung Buchstaben in "MATHE"
Wie viele Möglichkeiten gibt es die Buchstaben im Wort „MATHE“anzuordnen?
Mit Reihenfolge (MATHE $\neq$ THEMA) ohne Zurücklegen jeder Buchstabe kommt nur einmal vor.
$$
n=5\;\;\;k=5\;\;\;\Rightarrow\;\;\;\frac{5!}{0!}=5!=120 \;\mathsf{Möglichkeiten}
$$
### 3. Ziehen ohne Reihenfolge, ohne Zurücklegen
Von den $\frac{n!}{(n-k)!}$ Möglichkeiten beim Ziehen mit Beachtung der Reihenfolge und ohne Zurücklegen liefern je $k!$ durch umordnen (permutieren) die gleichen Ergebnisse.
Damit ergeben sich insgesamt 
![[Pasted image 20241016123120.png]]
relevante Möglichkeiten.
###### Beispiel Lotto
"6 aus 49" $n=49,k=6$
![[Pasted image 20241016123310.png]]

### 4. Ziehen ohne Reihenfolge, mit Zurücklegen
###### Beispiel
![[Pasted image 20241016123412.png]]
Diese "Manipulation" lässt den Wert $k$ unverändert, jedoch wird $n$ quasi vergrößert:
$1,\dots,n+(k-1)$
Somit entspricht dies dem Ziehen ohne Zurücklegen und ohne Reihenfolge aus $n+k-1$Kugeln.
$\Rightarrow$ Dies ergibt $\left(\begin{matrix}n+k-1\\k \end{matrix} \right)$ Möglichkeiten.
###### Beispiel Konditorei
In einer Konditorei werden $4$ verschiedene Torten verkauft. Sie wollen $7$ Stücke Kuchen kaufen.$$
n=4\;\;\;k=7 \;\;\Rightarrow\;\;\left( \begin{matrix}
n+k-1\\ k
\end{matrix} \right) = \left (\begin{matrix}
10\\7
\end{matrix}\right) =\frac{10!}{3!\cdot7!}=\left (\begin{matrix}
10\\3
 \end{matrix} \right)=\frac{10\cdot9\cdot8}{1\cdot2\cdot3}=\underline{\underline{120}}
$$

