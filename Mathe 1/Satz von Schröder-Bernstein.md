#satz #injektiv #surjektiv #bijektiv 

## Satz
Ist $\varphi :A \rightarrow B$ eine [[Bijektiv|bijektive]] Abbildung, so sind die Mengen $A$ und $B$ gleich mächtig, dass heißt
$$
\mid A \mid\;=\;\mid B \mid
$$

### Beweis
Sei als $\varphi$ [[Bijektiv|bijektiv]], das heißt $\varphi$ ist [[Injektiv]] und [[Surjektiv]].
![[Pasted image 20241016080806.png]]

## Satz
Es seien $A_1, A_2, \dots,A_m$ sowie $A$ Mengen mit $\mid A \mid\;=n$ und $\mid A_i \mid =n_i$ $\forall \,i=1, \dots, m$. Dann gilt:
1. $$
\mid X^{m}_{i=1}{A_i} \mid= \prod^{m}_{i=1}n_i
$$
2. $$
\mid P(A) \mid=2^n
$$
### Beweis
1. Es gilt: $A_1 \times A_2 \times \dots \times A_m=\{(a_1,a_2,\dots,a_m)\mid a_i \in A_i \;\forall \,i=1, \dots, m\}$
	Für das n-Tupel $(a_1,a_2,\dots,a_m)$ gibt es in der
		1. Komponente $n_1$ mögliche Werte
		2. Komponente $n_2$ mögliche Werte
					 $\vdots$ 
		m. Komponente $n_m$ mögliche Werte
	insgesamt also $n_1\cdot n_2 \cdot \,\dots \,\cdot n_m$ Eintragsmöglichkeiten.
	Das heißt $\mid A_1 \times \dots \times A_m \mid = n_1 \cdot\,\dots\,\cdot n_m$

2. Sei also $\mid A \mid \;=n$ zum Beispiel $A=\{a_1,a_2,\dots,a_n\}$.
	Ist nun $B \subseteq A$ eine Teilmenge, so können wir für jedes $a_i \in A(i=1,\dots,n)$ entscheiden, ob es zu $B$ gehört oder nicht.
	Wir assoziieren daher zu $B$ einen $n$-stelligen $0-1$-Vektor $(x_1,x_2,\dots,x_n)$ derart, dass:
	![[Pasted image 20241016084108.png]]
	Zur Teilmenge $\emptyset$ gehört dann der Vektor $(0,\dots,0)$.
	Zu $B=\{a_1,a_3\}$ gehört $(1,0,1,0,\dots,0)$ usw. bis $B=A \rightarrow(1,1,\dots,1)$.
	Diese Teilmengen-$0-1$-Vektor-Zuordnung ist offensichtlich [[Bijektiv]]. Daher gibt es genauso viele Teilmengen von $A$ wie $n$-stellige $0-1$-Vektoren. Die entspricht $\mid\{0,1\}^n \mid\;=2^n$   $\square$

> [!attention] Man sieht also: Es ist mitunter nicht immer sofort ersichtlich, wie viele Elemente eine Menge hat.


