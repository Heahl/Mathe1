#definition #korollar #teilbarkeitsregeln #beweis 

- [[#Definition]]
- [[#Korollar]]
- [[#Beweis]]
-----

# Definition
Es seien $a,b \in \mathbb{Z}$. $b$ heißt ein Teiler von $a$, in Zeichen $b \mid a$, wenn es ein $c \in \mathbb{Z}$ gibt mit $a=b \cdot c$.
$b \nmid a$ heißt dann: $b$ ist <u>kein</u> Teiler von $a$.

# Korollar
Es seien $a,b,c \in \mathbb{Z}$ mit $b,c \neq 0$.
Dann gilt:
$$
\begin{alignat}{1}
\text{i)}\;c \mid b\;\;\;&\land b \mid a \;&& \Rightarrow c \mid a \;\;\text{(Transitiv)}\\
\text{ii)}\;b \mid a \;\;\;&\Rightarrow b \cdot c \mid a \cdot c\\
iii)\; c \mid b \;\;\;&\land c \mid a && \Rightarrow c \mid a \cdot m + b \cdot n\;\;\;\forall \;m,n \in \mathbb{Z}\\
iv)\; b \mid a \;\;&\; b \mid a \cdot n \;\;\;&&\forall\;n \in \mathbb{Z}\\
v) \;a \mid b \;\;&\land\;\;b \mid a &&\Rightarrow a = \pm b\\
vi)\;a \mid b\;\; &\land\;a,b > 0 &&\Rightarrow a \leq b
\end{alignat}
$$
# Beweis
zu i)
$$
\begin{alignat}{1}
c \mid b \land b \mid a\;\;\;&\Rightarrow \exists \;m_1,m_2 \in \mathbb{Z}\;\text{mit} \;b =c \cdot m_1 \land a = b \cdot m_2\\
&\Rightarrow a = c \cdot \underbrace{m_1 \cdot m_2}_{m \;\in\;\mathbb{Z}}\\
&\Rightarrow c \mid a
\end{alignat}
$$
zu ii)
$$
\begin{alignat}{1}
b \mid a\;\;\;&\Rightarrow \exists \;m \in \mathbb{Z}\;\text{mit} \;a =b \cdot m \;\;\;\mid \cdot c\\
&\Rightarrow a \cdot c=b \cdot m \cdot c\\
&\Rightarrow a \cdot c = (b \cdot c) \cdot m\\
&\Rightarrow b \cdot c \mid a \cdot c
\end{alignat}
$$
zu iii)
> [!info] Der Rest wird in der Übung gelöst.


