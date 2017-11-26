# Teoria dei gruppi

## Funzioni, composizione, associatività
Il concetto di gruppo è strettamente legato a quello di funzione. Per chiarire questo legame consideriamo l'insieme $S$ delle funzioni biunivoche definite su un insieme $E$. 

In particolare, dato un qualunque insieme *finito* $E$ contenente $n$ elementi esistono $n!$ distinte funzioni biunivoche su di esso, anche dette *permutazioni* di $n$ elementi.. Ciascuna funzione $f_i$ definisce infatti una *corrispondenza* tra ciascuno degli $n$ elementi $x$ preso come *argomento* ed uno degli elementi $y = f_i(x)$ preso come *valore*. Per l'assunto di biunivocità l'insieme dei valori di una qualunque $f_i(x)$ coincide con $E$ ed esiste la funzione *inversa* $f^{-1}_i$ definita .  

Tra le funzioni in $S$ è sempre inclusa la *funzione identica* $e$ che fa corrispondere ciascun elemento di $E$ a se stesso:
$$e(x) = x $$

Sull'insieme $S$ è definita l'operazione di *composizione* $\circ$ che associa a due elementi $f$ e $g$ di $S$ un elemento $g \circ f$ tale che per ogni $x \in E$ $(g \circ f)(x) = g(f(x))$. L'operazione di composizione gode della proprietà associativa. Con ciò si intende che comunque date tre funzioni $f, g, h$ vale 
$$ h \circ (g \circ f) = h(g(f(x))) =(h \circ g) \circ f $$

 

A quick primer into group theory is provider in Appendix I of "Geometry" (Brannan, Esplen, Gray). 

$$ \sqrt{x^2} = x $$  
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ5MTgzNDMxOF19
-->