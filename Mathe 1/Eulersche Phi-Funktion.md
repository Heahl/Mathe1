#phi #definition #satz #beweis 

- [[#Definition]]
- [[#Satz]]
- [[#Beweis]]
---
# Definition
Für $m \in \mathbb{N}$ definieren wir:$$
\Phi(m):=\;\mid\{n \in \mathbb{N} \mid1\leq n <m \land ggT(n,m)=1\}\mid
$$
$\Phi(m)$ gibt also die Anzahl der zu $m$ teilerfremden Zahlen $< m$ an.
###### Beispiel
$$
\begin{alignat}{1}
\Phi(5)&=\;\mid\{1,2,3,4\}\mid\;&&=4\\
\Phi(6)&=\;\mid\{1,5\}\mid&&=2\\
\Phi(10)&=\;\mid\{1,3,7,9\}\mid&&=4\\
\Phi(7)&=\;\mid\{1,2,3,4,5,6\}\mid&&=6\\
\Phi(28)&=\;\mid\{1,3,5,9,11,13,15,17,19,23,25,27\}\mid\;&&=12
\end{alignat}
$$

# Satz
Es gilt:
1. Ist $ggT(a,b)=1$, so gilt: $\Phi(a \cdot b)=\Phi(a)\cdot \Phi(b)$.
2. Ist $p \in\mathbb{P}$, so gilt: $\Phi(p^\alpha)=p^\alpha-p^{\alpha-1}$.

# Beweis
1. Wir zeigen die Aussage für Primzahlen:
	von den Zahlen $1,2,\dots,p \cdot q$ sind genau $\underline{q \;\text{durch}\;p}$ teilbar 
		$(\rightarrow p,2\cdot p,3\cdot p, \dots,q \cdot p)$
	und $\underline{p \; \text{Zahlen durch}\;q}$ teilbar $(\rightarrow q,2\cdot q,3\cdot q,\dots,p \cdot q)$.
	Die Zahl $p \cdot q$ wird hierbei doppelt gezählt. $$
\Rightarrow \Phi(p \cdot q)=p \cdot q-p-q+1=(p-1)\cdot(q-1)=\Phi(p)\cdot \Phi(q)
$$
2. Von den Zahlen $1,2,3,\dots,p^\alpha$ ist jede $p$-te Zahl durch $p$ teilbar.
	Das sind $\frac{p^\alpha}{p}=p^{\alpha-1}$ viele. $$
\Rightarrow \Phi(p^\alpha)=p^\alpha-p^{\alpha-1}
$$
###### Beispiel
$$
\begin{alignat}{1}
\Phi(2024)&=\Phi(2^3 \cdot253)\\&=\Phi(2^3\cdot11\cdot23)\\&=\Phi(2^3)\cdot \Phi(11)\cdot \Phi(23)\\&=(2^3-2^2)\cdot10\cdot22&&=\underline{\underline{880\;\text{teilerfremde Zahlen <\;m.}}}
\end{alignat}
$$
