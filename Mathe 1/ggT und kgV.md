#definition 

# Definition
Es seien $a, b \in \mathbb{Z}$.
Mit:$$
ggT(a,b) :=max\{t \in\mathbb{Z} \mid\;\;\;t \mid a \land t \mid b\}
$$
bezeichnen wer den **größten gemeinsamen Teiler** von $a$ und $b$. Dagegen ist $$
kgV(a,b):=min\{n \in\mathbb{N} \mid\;\;\;a \mid n \land b \mid n \}
$$
das **kleinste gemeinsame Vielfache**. Für mehr als 2 Zahlen definieren wir ggT und kgV induktiv:
- $ggT(a_1,a_2,\dots,a_n)=ggT(ggT(a_1,\dots,a_{n-1}),a_n)$
- $kgV(a_1,a_2,\dots,a_n)= kgV(kgV(a_1,\dots,a_{n-1}),a_n)$

# Zur Bestimmung nutzen wir den [[euklidischer Algorithmus|euklidischen Algorithmus]]
