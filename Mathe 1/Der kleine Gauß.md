#beweis #vollständigeinduktion #gauß

(C. F. Gauß, 1777 - 1856)

Aufgabe: Addiere all [[Die natürlichen Zahlen|natürlichen Zahlen]] von 1 bis 100.
$$
1+2+3+\dots+98+99+100 = 50*100 =5050
$$
$$
1+2+\dots +n= \frac{n}{2}*(n+1)=\frac{n*(n+1)}{2}
 $$
###### Geometrisch:
![[Pasted image 20240924182217.png]]

#### <u>Vermutung:</u> $\forall \in \mathbb{N}\;gilt:\;1+2+3+\dots+n=\frac{n(n+1)}{2}$

###### Beweis via vollständiger Induktion
1. Induktionsanfang $n=1\implies\,1=\frac{1(1+1)}{2}$ 
2. Induktionsschritt $n \to n+1$
>[!info] Induktionsannahme/-voraussetzung: "Formel gilt für $n$"

Zeige: Formel gilt auch für $\nu(n)=n+1$
$$
\underbrace{1+2+3+4+\dots+n}_{=\frac{n(n+1)}{2} \,nach\,Induktionsvorauss.}+(n+1)=\frac{n(n+1)}{2}+(n+1)=\frac{n(n+1)}{2}+\frac{2(n+1)}{2}
$$
$$
=\frac{(n+1)(n+2)}{2}
$$

$q$.$e$.$d$.