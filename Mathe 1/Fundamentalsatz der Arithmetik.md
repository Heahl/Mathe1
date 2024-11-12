#satz #beweis #primzahl 
# Satz
Jede Zahl $n \in\mathbb{N}_{\leq2}$ kann mit Ausnahme der Reihenfolge eindeutig durch ein Produkt aus Primzahlen dargestellt werden.
# Beweis
- für $p \in \mathbb{P}$ sind wir fertig
- falls $n$ dagegen zusammengesetzt ist, also $n=n_1 \cdot n_2$, untersuchen wir, ob $n_1 \in\mathbb{P} \lor n_2 \in\mathbb{P} \lor \dots$
- zur Eindeutigkeit: angenommen, es gäbe **zwei** Zerlegungen:$$
\begin{alignat}{1}
n &=p_1\cdot p_2\cdot \,\dots \,\cdot p_{r'}=q_1\cdot q_2\cdot \,\dots\, q_{s'} \;\text{gemeinsame Primzahlen wegkürzen}\\
&\Rightarrow p_1\cdot p_2\cdot \,\dots\,\cdot p_r=q_1\cdot q_2 \cdot\,\dots\,\cdot q_s\;\text{mit}\;p_i \neq q_j\;\;\;\forall \;i=1,\dots,r\;\;\;\forall\;j=1, \dots,s\\
&\Rightarrow p_1 \mid q_1\cdot\,\dots\,\cdot q_s \;\;\;\Rightarrow p_1 \mid q_j \;\text{für mindestens ein} \;q_j\\
&\Rightarrow p_1 = q_j \;\text{geht nicht!} 
\end{alignat}
$$
$\square$

# Bemerkung
Dieser Fundamentalsatz ist <u>keine</u> Selbstverständlichkeit.
<u>Beispiel:</u> $$
M=2\cdot\mathbb{N}=\{2,4,6,8,10,\dots\}
$$
Hierzu wären $2,6,10,14$ Primzahlen, dagegen sind $4,8,12,\dots$ zusammengesetzt.
Nun gilt:$$
60=\underbrace{2 \cdot30=6\cdot10}_{\text{nicht eindeutig}}
$$
Hier würde die Zerlegung in Primfaktoren also nicht eindeutig sein.