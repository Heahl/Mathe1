#definition #injektiv #surjektiv #bijektiv 

$\varphi$ heißt **surjektiv**, falls gilt:
$$
\forall \;b \in B\; \;\exists\; a \in A \; mit \; f(a)=b
$$
das heißt zu jedem Element der Bildmenge $B$ existiert ein Urbild. Somit wird jedes Element in $B$ durch die Abbildung $\varphi$ "getroffen".
![[Pasted image 20241015174945.png]]

Insbesondere gilt: $\mid A \mid \;\leq\; \mid B \mid$

##### Beispiel:
a)
	$f: \mathbb{R} \rightarrow \mathbb{R}$ mit $f(x)=x^2$ ist <u>nicht</u> surjektiv, da die negativen Zahlen in $\mathbb{R}$ nicht getroffen werden.
		$\nexists \;x \in \mathbb{R}$ mit $f(x)=x^2=-1$

b)
	$f: \mathbb{R} \rightarrow \mathbb{R}$ mit $f(x)=2x+3$ ist surjektiv
	Um dies zu zeigen, lösen wir die Gleichung $f(x)=y$ nach $x$ auf.
	$$
2x+3=y\;\;\;\mid-3
$$
$$
\Leftrightarrow 2x=y-3\;\;\;\mid:2
$$
$$
\Leftrightarrow x=\frac{y}{2}-\frac{3}{2}
$$
	Ist nun $y \in \mathbb{R}$ beliebig vorgegeben, so wähle $x=\frac{1}{2}y-\frac{3}{2}$,
	denn dann gilt: $f(x)=2x+3 = 2 \cdot (\frac{1}{2}y-\frac{3}{2})+3= y-3+3=\underline{\underline{y}}$

>[!tldr] Um zu zeigen, dass $\varphi$ surjektiv ist, muss also stets zu einem beliebigen vorgegebenen $b \in B$ ein Urbild $a \in A$ mit $\varphi(a)=b$ gefunden werden. Dagegen genügt wieder ein einziges Beispiel, das heißt ein einziger wert, für den es kein Urbild gibt, um die Surjektivität "kaputt" zu machen.

siehe auch:
[[Injektiv]]
[[Bijektiv]]
