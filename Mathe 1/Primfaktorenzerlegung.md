zur Bestimmung von $kgV$ und $ggT$.
#satz #primzahl 

# Satz
Es seien $a,b \in \mathbb{Z}$ mit Primfaktorzerlegung
$$
a=\prod^{\infty}_{i=1}p_i^{r_i}\;\;\;,\;\;\;b=\prod^{\infty}_{i=1}p_i^{s_i}
$$
Dabei gilt: $r_i=0$ für *fast alle*, das heißt alle bis auf endlich viele $i \in \{1,2,\dots,\infty\}$.

Dann gilt:$$
\begin{alignat}{1}
ggT(a,b)&=\prod^{\infty}_{i=1}p_i^{min\{r_i,s_i\}}\\
kgV(a,b)&=\prod^{\infty}_{i=1}p_i^{max\{r_i,s_i\}}
\end{alignat}
$$
###### Beispiel
$$
\begin{alignat}{1}
a=1440\cdot12^2\cdot10=&\;\;\;\;\;\;2^5&&\;\;\;\;\;\;3^2&&&\;5&&&&\;&&&&&\\
&\uparrow \text{MAX}&& \uparrow \text{MAX} &&& &&&& \uparrow \text{MIN} &&&&&\\
&\downarrow \text{MIN}&& \downarrow \text{MIN} &&& &&&& \;\;\;\downarrow \text{MAX} &&&&&\\
b=420=6\cdot7\cdot10=&\;\;\;\;\;\;2^2&&\;\;\;\;\;\;3&&&\;5&&&&7\\
\text{Minimum:}\;ggT(a,b)=&\;\;\;\;\;\;2^2&&\;\;\;\;\;\;3&&& 5&&&&  &&&&&\;\;\;=60\\
\text{Maximum:}\;kgV(a,b)=&\;\;\;\;\;\;2^5&&\;\;\;\;\;\;3^2 &&&5&&&& 7&&&&&\;\;\;=10.080
\end{alignat}
$$
Die Zahlen $a$ und $b$ werden in ihre Primfaktoren zerlegt. Die Primfaktoren werden je nach Anforderung verglichen und wieder als Primfaktoren des $ggT$ respektive $kgV$ zusammengesetzt.