# Teoria dei gruppi

## Funzioni, composizione, associatività
Il concetto di gruppo è strettamente legato a quello di funzione. Per chiarire questo legame consideriamo l'insieme $S$ delle funzioni biunivoche definite su un insieme $E$. 

In particolare, dato un qualunque insieme *finito* $E$ contenente $n$ elementi vi sono esattamente $n!$ distinte funzioni biunivoche definite su di esso. Ciascuna funzione $f_i$ definisce infatti una *corrispondenza* tra ciascuno degli $n$ elementi $x$ preso come *argomento* ed uno degli altri elementi $y = f_i(x) \neq x$ preso come *valore*. Il numero delle funzioni contenute in $S$ è dunque $n!$ cioè il numero delle *permutazioni* di $n$ elementi.

Sull'insieme $S$ è definita l'operazione di composizione $\circ$ che associa a due elementi $f$ e $g$ di $S$ un elemento $h = g \circ f$ tale che per ogni $x \in E$ $h(x) = g(f(x))$. L'operazione di composizione gode della proprietà associativa. Con ciò si intende che comunque date tre funzioni $f, g, h$ vale 
$$ h \circ (g \circ f) = (h \circ g) \circ f $$

 

A quick primer into group theory is provider in Appendix I of "Geometry" (Brannan, Esplen, Gray). 

$$ \sqrt{x^2} = x $$  
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzODkxNDg2MV19
-->