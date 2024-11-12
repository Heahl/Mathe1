#primzahl #satz #beweis 

# Satz
Für jede beliebige Zahl $n \in \mathbb{N}$ gibt es $n$ aufeinanderfolgende Zahlen, die *nicht* prim sind.

# Beweis
Betrachte die Zahlen $$
(n+1)!+2,(n+1)!+3,(n+1)!+4,\dots,(n+1)!+(n+1)
$$
Dies sind $n$ aufeinanderfolgende Zahlen.

Es gilt:
$$
\left.
    \begin{aligned}
         & 2 \mid (n+1)!+2 \\
         & 3 \mid (n+1)!+3\\
         & \;\;\;\vdots\\
         & (n+1)\mid(n+1)!+(n+1) \\
    \end{aligned}
\right\} \;\text{diese Zahlen sind alle kein Primzahlen}
$$
###### Beispiel
$$
n=5\Rightarrow \cancel{722},\cancel{723},\cancel{724},\cancel{725},\cancel{726}\;\;\;\text{(Quersumme: 12)}
$$
