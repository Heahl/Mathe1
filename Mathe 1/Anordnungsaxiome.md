#axiom 

Auf manchen Körpern gibt es die Ordnungsrelation "$<$", in Worten "kleiner als", das heißt für beliebige Elemente $a,b, \in K$ gilt genau eine der folgenden Beziehungen:$$
\begin{array}{ccc} \\
&a<b,&&a=b,&&a>b
\end{array}
$$
## Axiom
Es gelten die folgenden Verträglichkeitsbedingungen:
1. $a<b$ $\land$ $b<c$ $\Rightarrow a<c$ (Transitivität)
2. $a<b$ $\Rightarrow$ $a+c<b+c$   $\forall c \in K$ 
3. $a<b$ $\land$ $c >0$ $\Rightarrow$ $a \cdot c < b \cdot c$

#### Bemerkung
- statt $a<b$ ist auch $b>a$ erlaubt 
- $a \leq b$ bedeutet $a< b$ $\lor$ $a=b$
- ein Körper mit Ordnungsrelation heißt "angeordneter Körper"
- in jedem angeordneten Körper gilt $0<1$ (neutrales Element der Addition ist kleiner als neutrales Element der Multiplikation), denn angenommen es wäre $$
\begin{alignat}{1}
1<0\;\;\;&\stackrel{3.)}{\Rightarrow}a \cdot 0 \;\text{für}\;a>0\\
&\Rightarrow a<0   \;\;\;\dagger
\end{alignat}
$$
- $\mathbb{Q}$ und $\mathbb{R}$ sind angeordnete Körper, $\mathbb{Z}_p$ dagegen nicht.
	Beispiel: $\mathbb{Z}_2=\{0,1\}$. Angenommen er wäre angeordnet:$$
\begin{array}{clcl} \\
&0<1&oder&1<0&&\mid+1 \\
&1<0 \;\dagger&\hphantom{oder} &0<1 \;\dagger
\end{array}
$$
