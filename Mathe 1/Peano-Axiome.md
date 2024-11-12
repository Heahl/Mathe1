#axiom #peano #nachfolger 

(nach Giuseppe Peano, 1858 - 1932)

Setze:
$$\nu(n) \; als \; Nachfolger\; von\; n$$

### P1)
1 ist eine [[Die natürlichen Zahlen|natürliche Zahl]].
$$1 \in \mathbb{N}$$

### P2)
Jede [[Die natürlichen Zahlen|natürliche Zahl]] hat eine [[Die natürlichen Zahlen|natürliche Zahl]] als Nachfolger.
$$\forall\;n\in \mathbb{N}\implies\nu(n)\in \mathbb{N}$$

### P3)
1 ist kein Nachfolger einer natürlichen Zahl.
$$\forall\;n\in \mathbb{N}\implies \nu(n)\neq 1$$

### P4)
[[Die natürlichen Zahlen|Natürliche Zahlen]] mit gleichen Nachfolgern sind gleich.
$$\forall\;n,m\in \mathbb{N}\implies[\nu(n) =\nu(m)\implies n=m]$$
>[!info]+  Das heißt verschiedene [[Die natürlichen Zahlen|natürliche Zahlen]] haben auch verschiedene Nachfolger, beziehungsweise jede [[Die natürlichen Zahlen|natürliche Zahl]] hat <u>genau einen</u> Nachfolger. 

### P5)
Jede Menge, die 1 enthält, sowie mit jeder [[Die natürlichen Zahlen|natürlichen Zahl]] auch jeder Nachfolger, enthält bereits alle [[Die natürlichen Zahlen|natürlichen Zahlen]].
$$\forall\;X\;mit\;(1\in X\;\cap\forall\;n\in \mathbb{N}(n\in X\implies \nu(n)\in X))\implies \mathbb{N}\in X$$
>[!info] Das fünfte Peano-Axiom heißt auch "Induktionsaxiom" und bildet die Grundlage für die Beweismethode der [[Die vollständige Induktion|vollständigen Induktion]]




