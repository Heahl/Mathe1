#zahlsystem #base10 #base8 #base16 #base2 #umwandeln #g-adisch

- üblich: [[Dezimalsystem]] (10er-Sytem)
- Ein Zahlsystem kann jedoch jede beliebige Basis haben (g-adisches System)
- Ziffern 0,1,2,...,g-1 (aus der Menge der Grundziffern)
- ab 10 Buchstaben

#### Zahldarstellung:
$$
z=(z_{n},z_{n-1,\dots,z_{1},z_{0}})_{g}=\sum_{i=0}^{n}z_{i}*g^{i}
$$
#### Beispiele:
[[Oktalsystem]]: Ziffern 0,1,...,7
	 - $(6314)_{8}=4*8^{0}+1*8^{1}+3*8^{2}+6*8^{3}=3276_{10}$ 
[[Binärsystem]]: Ziffern 0,1
	 - $101101_{2}=1*2^{0}+0*2^{1}+1*2^{2}+1*2^{3}+0*2^{4}+1*2^{5}=45$ 
[[Hexadecimalsystem]]: Ziffern 0,1,...,9,A,B,...,F
	 - $AFFE_{16}=14*16^{0}+15*16^{1}+15*16^{2}+10*16^{3}=45054$

##### Umgekehrt kann man durch fortgesetztes dividieren in beliebige Alternativsysteme wechseln:

![[Pasted image 20240925182810.png]]
![[Pasted image 20240925182828.png]]
![[Pasted image 20240925182852.png]]

###### Besonders angenehm ist das Umwandeln, wenn die Basen Potenzen ein und derselben Zahl sind:

$13321_{4}$ soll in $()_{2}$ umgewandelt werden.
Da $4^{1}=2^{2}$, entspricht eine Ziffer im 4er-System einem Block von zwei Ziffern im Dualsystem.$$
\implies 13321_{4}=111111001_{2}
$$
Analog:
$$
(\underbrace{01}_{1}\underbrace{20}_{6}\underbrace{02}_{2}\underbrace{21}_{7}\underbrace{12}_{5}\underbrace{21}_{7})_{3} = 16258_{9}
$$


![[Pasted image 20240927195215.png]]

![[Pasted image 20240927195230.png]]![[Pasted image 20240928073021.png]]