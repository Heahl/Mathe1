#lemma #beweis 

## Lemma
Die Gleichung $b+x=a$ und $d+x=c$ haben für $a,b,c,d \in \mathbb{N}_0$ genau dann die selbe Lösung in $\mathbb{N}_0$, falls $a+d=b+c$ mit $b \leq a;\;d \leq c$ gilt.

## Beweis
"$\Rightarrow$" Sei $x_0 \in \mathbb{N}_0$ die gemeinsame Lösung
$$
\begin{alignat}{1}
	&\Rightarrow b+x_0=a  &&\land&&&\;\; d+x_0=c \;\;\text{mit}\;\;b \leq a,\;d \leq c\\
	&\Rightarrow d+(b+x_0)=d+a\;\; &&\land&&& b+(d+x_0)=b+c\\
	&\Rightarrow \underline{a+d=b+c} \;\;\;\checkmark
\end{alignat}
$$
"$\Leftarrow$" Sei nun $b \leq a,\;d \leq c$ mit $a+d=b+c$
$$
\begin{alignat}{1}
&\text{wegen} \;\;&&b \leq a \Rightarrow \exists \;x_1 \in \mathbb{N}_0 \;\;\text{mit}\;\;b+x_1=a\\
& &&d \leq c \Rightarrow \exists \;x_2 \in \mathbb{N}_0 \;\;\text{mit}\;\;d+x_2=c\\
&\Rightarrow b+d&&+c_2=b+c=a+d=b+x_1+d\\
&\Rightarrow x_1 =&&x_2\;\;\;\checkmark\;\;\;\square
\end{alignat}
$$
