#vollständigeinduktion #geometrischesumme

$$
\forall \; q\in \mathbb{R} \setminus \{ 1 \} \; gilt: q^{0}+q^{1}+q^{2}+\dots+q^{n}=\frac{1-q^{n+1}}{1-q}\;\;\;\forall \;n\in \mathbb{N}
$$
##### Bsp: $q=2$ , $n=4$ 
$$
2^{0}+2^{1}+2^{3}+2^{4}=1+2+4+8+16=31
$$
$$
sowie\;\;\; \frac{1-2^{5}}{1-2}=\frac{-31}{-1}=31 

$$
### Beweis via [[Die vollständige Induktion|vollständiger Induktion]]:
1. Induktionsanfang $n=1$ 
$$
q^{0}+q^{1}=1+q=\frac{(1+q)(1-q)}{1-q}=\frac{1-q^{2}}{1-q}
$$
2. Induktionsstart $n\to n+1$
$$
q^{0}+q^{1}+q^{2}+\dots+q^{n}+q^{n+1}=\frac{1-q^{n+1}}{1-q}+q^{n+1}
$$
$$
= \frac{1-q^{n+1}}{1-q}+\frac{q^{n+1}(1-q)}{1-q}
$$
$$
=\frac{1-q^{n+1}+q^{n+1}-q^{n+2}}{1-q}
$$
$$
=\frac{1-q^{n+2}}{1-q}
$$
$q.e.d.$


