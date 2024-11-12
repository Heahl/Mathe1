#definition #wohldefiniert #satz #beweis 
## Definition
Auf $\mathbb{Z}$ können wir nun eine Addition definieren, wir setzen für $a,b,c,d \in \mathbb{N}_0$:
$$
\overline{(a,b)} \oplus \overline{(c,d)}=\overline{(a+c,b+d)}
$$
Zum Beispiel sind:$$
\begin{array}
\overline{\overline{(1,3)}}\oplus \overline{(7,4)}&=\overline{(8,7)}\\
\overline{(2,4)}\oplus \overline{(8,5)}&=\overline{(10,9)}\\
\end{array} \;\text{Repräsentanten derselben Klasse}
$$
Wir müssen nun zeigen, dass diese Addition **wohldefiniert**, das heißt unabhängig von der Wahl der Repräsentanten, ist. Zu zeigen sei:
$$
\begin{alignat}{1}
(a_1,b_1) \stackrel{(*)}{\sim}(a_2,b_2)\;\;\;&\land\;\;\;(c_1,d_1)\stackrel{(**)}{\sim}(c_2,d_2)\\
\Rightarrow(a_1+c_1,b_1+d_1)\;\;\;&\sim\;\;\;(a_2+c_2,b_2+d_2)
\end{alignat}
$$
Wir müssen also zeigen, dass $$
\begin{alignat}{1}
a_1+c_1+b_2+d_2 &\stackrel{!}{=}b_1+d_1+a_2+c_2 \;\;\;\text{gilt.}\\
a_1+c_1+b_2+d_2 &\overset{KG}{\underset{AG}{=}}\underbrace{(a_1+b_2)}_{\downarrow*}+\underbrace{(c_1+d_2)}_{\downarrow**}\\
&=(b_1+a_2)+(d_1+c_2) \overset{KG}{\underset{AG}{=}}b_1+d_1+a_2+c_2
\end{alignat}
$$
	