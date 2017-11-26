# Teoria dei gruppi

## Funzioni, composizione, associatività
Il concetto di gruppo è strettamente legato a quello di funzione. Per chiarire questo legame consideriamo l'insieme $S$ delle funzioni biunivoche definite su un insieme $E$. 

In particolare, dato un qualunque insieme *finito* $E$ contenente $n$ elementi esistono $n!$ distinte funzioni biunivoche su di esso, dette *permutazioni* di $n$ elementi. Ciascuna funzione $f_i$ definisce infatti una *corrispondenza* tra ciascuno degli $n$ elementi $x$ preso come *argomento* ed uno degli elementi $y = f_i(x)$ preso come *valore*. 

Per l'assunto di biunivocità l'insieme dei valori di una qualunque $f_i(x)$ coincide con $E$ ed esiste la funzione *inversa* $f^{-1}_i$ definita dalla proprietà 
$$f^{-1}_i(f_i(x)) = x = f_i(f^{-1}_i(x))$$
  
Tra le funzioni in $S$ è sempre inclusa la *funzione identica* $e$ che fa corrispondere ciascun elemento di $E$ a se stesso:
$$e(x) = x $$

Sull'insieme $S$ è definita l'operazione di *composizione* $\circ$ che associa a due elementi $f$ e $g$ di $S$ un elemento $g \circ f$ tale che per ogni $x \in E$ $(g \circ f)(x) = g(f(x))$. L'operazione di composizione gode della *proprietà associativa*. Con ciò si intende che comunque date tre funzioni $f, g, h$ vale 
$$ h \circ (g \circ f) = h(g(f(x))) =(h \circ g) \circ f $$

 Una funzione definita sull'insieme prodotto $S\times S$ a valori in $S$ si dice *operazioni binaria*. L'operazione $\circ$ definita sull'insieme $S$ rappresenta il modello cui possono essere ricondotte tutte le *operazioni binarie associative*. 

In effetti capita in diversi contesti di definire una certa operazione $\diamond$ in un insieme e di chiedersi se per tale operazione valga la proprietà associativa:
$$ c \diamond (b \diamond a) = (c \diamond b) \diamond a$$
La soluzione è di trovare una possibile identificazione degli elementi $a, b, c$ dell'insieme con delle funzioni (trasformazioni) dell'insieme in se stesso. Se questa identificazione è possibile l'associatività deriva immediatamente dalla identificazione dell'operazione 
 

A quick primer into group theory is provider in Appendix I of "Geometry" (Brannan, Esplen, Gray). 

$$ \sqrt{x^2} = x $$  
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAwMDkyMzY4NCwtOTE2ODk4NTAxXX0=
-->