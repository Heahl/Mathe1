#definition #beweis #beispiele 


# Definition
Eine Menge $G$ zusammen mit einer Verknüpfung $\circ$, kurz ($G,\circ$), heißt **"Gruppe"**, falls sie die folgenden Eigenschaften besitzt:
![[Pasted image 20241107161331.png]]

# Bemerkung
Sowohl das neutrale Element als auch das jeweilige inverse Element sind <u>eindeutig</u> bestimmt. Ferner gilt: $$
e \circ a = a \circ e=a \;\;\;\text{und}\;\;\;a'\circ a=a \circ a' =e
$$
# Beweis
Neutrales und Inverses Element sind eindeutig bestimmt.
1. $$
\begin{alignat}{1}
a \circ a' &\stackrel{3)}{=}e \circ(a \circ a') \stackrel{4)}{=}(a'\circ a)\circ(a \circ a')=(a''\circ a')\circ(a \circ a')\\
&\stackrel{2)}{=}a''\circ(\underbrace{a'\circ a}_{=e})\circ a' \stackrel{4)}{=}a'\circ(e \circ a')\stackrel{3)}{=}a''\circ a'=\underline{e}
\end{alignat}
$$
2. $$
a \circ e \stackrel{4)}{=}a \circ(a' \circ a)\stackrel{2)}{=}(a \circ a')\circ a \stackrel{i)}{=}e \circ a \stackrel{3)}{=}\underline{a}
$$
3. Angenommen es gäbe $e'\neq e$ mit $e' \circ a=a\;\;\;\forall a \in G$ $$
\begin{matrix}
\Rightarrow e' \circ e=e \\
\;\;\;\mid \mid\;\;\;\;\;\mid \mid\\
\;\;\;e \circ e'=e'
\end{matrix}
$$
4. Angenommen es gäbe $a''\neq a'$ mit $a'' \circ a=e$$$
\begin{alignat}{1}
&\Rightarrow a'' \circ a=e=a' \circ a\\
&\Rightarrow (a'' \circ a) \circ a' =(a' \circ a) \circ a'\\
&\stackrel{AG}{\Rightarrow}a'' \circ(a \circ a')=a' \circ(a \circ a')\\
&\Rightarrow a'' \circ e = a' \circ e\\
&\Rightarrow a''=a'   
\end{alignat}
$$
