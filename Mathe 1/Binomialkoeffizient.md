#beweis 

Wie gehabt gilt:
$$
\begin{pmatrix}
n\\k
\end{pmatrix}=\frac{n!}{(n-k)!\cdot k!}
$$
Binomialkoeffizienten haben tolle Eigenschaften:
1. $$
\left(\begin{matrix}
n\\0
\end{matrix}\right)=\left(\begin{matrix}
n\\n
\end{matrix}\right)=1\;\;\;\forall\;n \in \mathbb{N};
$$$$
\begin{pmatrix}
n\\1
\end{pmatrix}=\begin{pmatrix}
n\\n-1
\end{pmatrix}=n\;\;\;\forall\;n \in \mathbb{N};
$$
$$
\begin{pmatrix}
n\\k 
\end{pmatrix}=\begin{pmatrix}
n\\ n-k
\end{pmatrix}\;\;\;\forall\;n \in \mathbb{N} \;\;\forall\;k \leq n(k \in \mathbb{N}) 
$$
2. $$
\begin{pmatrix}
n\\k
\end{pmatrix}+\begin{pmatrix}
n\\k+1
\end{pmatrix}=\begin{pmatrix}
n+1\\k+1
\end{pmatrix}
$$
### Beweis
1. $$
\begin{pmatrix}
n\\0
\end{pmatrix}=\frac{n!}{(n-0)!\cdot0!}=\frac{n!}{n!\cdot1}=1
$$$$
\begin{pmatrix}
n\\n
\end{pmatrix}=\frac{n!}{(n-n)!\cdot n!}=1
$$
![[Pasted image 20241016133933.png]]

2. 
![[Pasted image 20241016133950.png]]
3. Die [[Binomialkoeffizient|Biko's]] stehen in engem Zusammenhang zum [[Paskal'sches Zahlendreieck|Paskal'schen Zahlendreieck]].

4. Es gilt:$$
\sum^{n}_{k=0}\begin{pmatrix}
n\\k
\end{pmatrix}=2^n
$$
### Beweis
setze $a=b=1$ in den [[binomischer Lehrsatz|binomischen Lehrsatz]] ein $$
\Rightarrow2^n=\sum^{n}_{k=0}\begin{pmatrix}
n\\k
\end{pmatrix}\cdot \underbrace{1^{n-k}\cdot1^k}_{=1}
$$
