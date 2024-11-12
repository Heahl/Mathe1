#satz #korollar #beweis #zusammenhang 

- [[#Satz]]
- [[#Satz von Bezout]]
- [[#Beispiel]]
- [[#Korollar - ggT und gemeinsame Teiler]]
- [[#Beweis - ggT und gemeinsame Teiler]]
- [[#Satz - Zusammenhang ggT und kgV]]
- [[#Beweis - Zusammenhang ggT und kgV]]
-----
# Satz
Es seien $a,b \in \mathbb{Z}$. Dann lässt sich der $ggT(a,b)$ mit Hilfe des **Euklidischen Algorithmus** bestimmen.

###### Beispiel
$ggT(1440,420)$
$$
\begin{alignat}{1}
1440:420=3\;\;\;&\text{Rest}\;180\\
420:180=2\;\;\; &\text{Rest} \;\underline{\underline{60}}\\
180:60=3\;\;\;&\text{Rest}\;0\\
ggT(1440,420)&=60
\end{alignat}
$$
Rückwärts bietet der euklidische Algorithmus eine Möglichkeit für eine hübsche Darstellung des $ggT$.$$
\begin{alignat}{1}
\Rightarrow60&=420-2\cdot180\\
&=420-2\cdot(1440-3\cdot120)\\
&=7\cdot420-2\cdot1440
\end{alignat}
$$
> [!important] Wird später sehr nützlich sein!

Das ist immer möglich, denn es gilt:
# Satz von Bezout
Es seien $a,b \in\mathbb{Z}$. Dann gibt es $m,n \in\mathbb{Z}$ mit $$
ggT(a,b)=m \cdot a-n \cdot b
$$
Diese Zahlen ergeben sich aus dem Euklidischen Algorithmus.

# Korollar - ggT und gemeinsame Teiler
Es seien $a,b \in \mathbb{Z}$ und $d$ ein gemeinsamer Teiler, also $$
d \mid a \;\;\;\land\;\;\;d \mid b
$$
Dann gilt:$$
d \mid ggT(a,b)
$$
# Beweis - ggT und gemeinsame Teiler
Aus $d \mid a \;\;\;\land\;\;\;d \mid b\;\;\;\Rightarrow\;\exists\;m_1,m_2 \in \mathbb{Z}$ mit $a=d \cdot m_1\;\;\;\land\;\;\;b=d \cdot m_2$. Wir stellen $ggT(a,b)$ über den euklidischen Algorithmus (siehe Satz 10) dar:$$
\begin{alignat}{1}
ggT(a,b)&=m \cdot a+n \cdot b\\
&=d \cdot m \cdot m_1+d \cdot n \cdot m_2\\
&=d \underbrace{(m \cdot m_1+n \cdot m_2)}_{=\;k \;\in\;\mathbb{Z}}\\
&=d \mid ggT(a,b)
\end{alignat}
$$
$\square$


Zwischen $ggT$ und $kgV$ besteht ein einfacher Zusammenhang:
# Satz - Zusammenhang ggT und kgV
Es seien $a,b \in\mathbb{Z}$.
Dann gilt:$$
ggT(a,b)\cdot kgV(a,b)=\;\mid a \cdot b \mid
$$
# Beweis - Zusammenhang ggT und kgV
**Teil 1:** Sei zunächst $ggT(a,b)=1$. Ohne Einschränkungen (o.E.) setzen wir:$$
a,b > 0
$$
$kgV(a,b)$ ist Vielfaches von $a$ und $b$ $$
\begin{alignat}{1}
&kgV(a,b)=m \cdot a\\
&\Rightarrow b \mid ma \overset{ggT(a,b=1)}{\Rightarrow} b \mid m\\
&\Rightarrow b \leq m \;\;\;\mid \cdot a\\
&\Rightarrow a \cdot b \leq m \cdot a = kgV(a,b) \leq a \cdot b\\
&\Rightarrow kgV(a,b) = a \cdot b
\end{alignat}
$$
Also:$$
ggT(a,b)\cdot kgV(a,b)=1 \cdot(a \cdot b)= a \cdot b
$$
$\square$

**Teil 2:** Ist dagegen $ggT(a,b) = g \neq 1$, so gilt:$$
ggT(\frac{a}{g},\frac{b}{g})=1
$$
$$
\begin{alignat}{1}
&\overset{(1)}{=}ggT(\frac{a}{g},\frac{b}{g}) \cdot kgV(\frac{a}{g},\frac{b}{g})=\frac{a}{g}\cdot \frac{b}{g}\;\;\;\mid\;\cdot g^2\\
&\Rightarrow \underbrace{g \cdot ggT(\frac{a}{g},\frac{b}{g})}_{ggT(a,b)}\cdot \underbrace{g \cdot kgV(\frac{a}{g},\frac{b}{g})}_{kgV(a,b)}=a \cdot b\\
&\Rightarrow ggT(a,b)\cdot kgV(a,b)=a \cdot b
\end{alignat}
$$
$\square$

