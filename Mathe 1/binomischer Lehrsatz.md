#satz #beweis 

## Satz 
$$
(a+b)^n=\sum^{n}_{k=0} \begin{pmatrix}
n\\k
\end{pmatrix}\cdot a^{n-k}\cdot b^k
$$

### Beweis
zu Zeigen: [[#Satz|s.o.]]
1. Induktionsanfang $n=1$
$$
(a+b)^1=a+b=a+b \;\;\checkmark
$$
2. Induktionsschritt $n \rightarrow n+1$
$$
\begin{alignat}{1}
(a+b)^{n+1}&=(a+b)\cdot(a+b)^n\\
&= (a+b)\cdot \sum^{n}_{k=0}\begin{pmatrix}
n\\k
\end{pmatrix} \cdot a^{n-k}\cdot b^k\\
&=\sum^{n}_{k=0}\begin{pmatrix}
n\\k
\end{pmatrix}\cdot a^{n+1-k}\cdot b^k+\sum^{n}_{k=0}\begin{pmatrix}
n\\k-1
\end{pmatrix} \cdot a^{n-(k-1)}\cdot b^{k-1+1}\\
&=a^{n+1}+\sum^{n}_{k=1}\begin{pmatrix}
n\\k
\end{pmatrix}\cdot a^{n+1-k}\cdot b^k+\sum^{n}_{k=1}\begin{pmatrix}
n\\k-1
\end{pmatrix}\cdot a^{n+1-k}\cdot b^k+b{n+1}\\
&=a^{n+1}+\sum^{n}_{k=1}\underbrace{(\begin{pmatrix}
n\\k
\end{pmatrix}+\begin{pmatrix}
n\\k-1
\end{pmatrix})}_{\begin{pmatrix}
n+1\\k
\end{pmatrix}}\cdot a^{n+1-k}\cdot b^k + b^{n+1}\\
&= \sum^{n+1}_{k=0}\begin{pmatrix}
n+1\\k
\end{pmatrix}\cdot a^{n+1-k}\cdot b^k \;\;\;\checkmark\;\;\square
\end{alignat}
$$
