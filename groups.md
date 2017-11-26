# Teoria dei gruppi

## Funzioni, composizione, associatività
Il concetto di gruppo è strettamente legato a quello di funzione. Per chiarire questo legame consideriamo l'insieme $S$ delle funzioni biunivoche definite su un insieme $E$. 

In particolare, dato un qualunque insieme *finito* $E$ contenente $n$ elementi esistono $n!$ distinte funzioni biunivoche su di esso, dette *permutazioni* di $n$ elementi. Ciascuna funzione $f_i : E \mapsto E$ definisce una *corrispondenza* tra ciascuno degli $n$ elementi $x \in E$ preso come *argomento* ed un elemento $y \in E =f_i(x)$ che ne costituisce il *valore*. 

Per l'assunto di biunivocità l'insieme dei valori di una qualunque $f_i(x)$ coincide con $E$ ed esiste la funzione *inversa* $f^{-1}_i$ definita dalla proprietà 
$$f^{-1}_i(f_i(x)) = x = f_i(f^{-1}_i(x))$$
  
Tra le funzioni contenute in $S$ vi è la *funzione identica* $e$ che fa corrispondere ciascun elemento di $E$ a se stesso:
$$e(x) = x $$
Sull'insieme $S$ è definita l'operazione di *composizione* $\circ$ che associa a due funzioni $f$ e $g$ di $S$ una funzione $g \circ f$ tale che per ogni $x \in E$ $(g \circ f)(x) = g(f(x))$. Dalla definizione segue che l'operazione di composizione tra funzioni gode della *proprietà associativa*. Con ciò si intende che comunque date tre funzioni $f, g, h$ vale 
$$ h \circ (g \circ f) = h(g(f(x))) =(h \circ g) \circ f $$

Per un qualsiasi insieme $A$ una funzione definita sull'insieme prodotto $A\times A$ a valori in $A$ si dice *operazioni binaria*. 

In un senso che ora cerchiamo di precisare, l'operazione $\circ$ definita sull'insieme di funzioni $S$ rappresenta un modello cui possono essere ricondotte tutte le *operazioni binarie associative*. In effetti capita in diversi contesti di definire una certa operazione $\diamond$ in un insieme $A$ e di chiedersi se per tale operazione valga la proprietà associativa, cioè se per qualsiasi $a, b, c \in A$ valga:
$$ c \diamond (b \diamond a) = (c \diamond b) \diamond a$$
Per rispondere alla domanda si può tentare l'identificazione di ciascun elemento $x$ dell'insieme $A$ con una *trasformazione* dell'insieme $A$ in se stesso. Se questa identificazione è possibile la risposta è positiva in virtù della associatività della composizione di funzioni.

Per fare un esempio concreto consideriamo l'operazione di addizione $+$ nell'insieme $\mathcal Z$ degli interi naturali.  Nella maggior parte delle presentazioni moderne è assunto come *assioma* che per tale operazione valga la proprietà associativa, ovvero che per qualsiasi $a, b, c \in \mathcal Z$ valga
$$c + (b + a) = (c + b) + a$$

Identifichiamo ora ciascun elemento $a \in \mathcal Z$ con una funzione  $f_{a} : \mathcal Z \mapsto \mathcal Z$ tale che per ogni $x \in \mathcal Z$ valga $f_{a}(x) = x + a$. 

Da ciò segue 
$$ x + (a + b) = f_{a+b}(x) = (f_{b} \circ f_{a})(x) = (x+a) + b$$
Questo risultato dimostra che l'identificazione $a \leftrightarrow f_{a}$ di ciascun elemento di $A$ con la funzione $f_{a}(x) = x+a$ impone che per l'operazione di addizione valga la proprietà associativa.  

## Definizione di gruppo
Sia $G$ un insieme e $\circ$ una operazione binaria definita su $G$. Allora $(G, \circ )$ è un **gruppo** rispetto all'*operazione* $\circ$ se valgono i seguenti quattro assiomi.
||||
|:--|:--|:--|
|G1| Chiusura | $\forall g_{1},g_{2} \in G, g_{1} \circ g_{2} \in G$|
|G2| Identità |Esiste un elemento identità $e \in G$ tale che per ogni $g \in G$ $$g \circ e = g = e \circ g $$|
|G3| Inverso | Per ogni $g \in G$ esiste un elemento inverso $g^{-1}  \in G$ tale che $$ g \circ g^{-1} = e = g^{-1} \circ g$$|
|G4|Associatività |Per ogni $g_{1},g_{2},g_{3} \in G$, $$g_{1} \circ (g_{2} \circ g_{3}) = (g_{1} \circ g_{2}) \circ g_{3}$$  |

In ogni gruppo l'elemento identità è unico ed ogni elemento ha un unico inverso. Inoltre, se se $g \in G$ allora ${(g^{-1})}^{-1} = g$.
se l'operazione binaria $\circ$ di un gruppo $G$ è **commutativa** (cioè $g_{1} \circ g_{2} = g_{2} \circ g_{1}$ per ogni $g_{1}, g_{2} \in G$) diciamo che il gruppo è **commutativo** o **Abeliano**.

### Sottogruppi ###
Un sottoinsieme $H$ di un gruppo $G$ è un **sottogruppo** di $G$ se esso è un gruppo rispetto alla medesima operazione binaria. Ciò si può esprimere con maggior precisione nel modo seguente. 
Sia $(G, \circ )$ un gruppo con identità $e$, e sia $H \subset G$ un sottoinsieme di $G$. Allora $(H, \circ )$ è un **sottogruppo** di $(H, \circ )$rispetto all'*operazione* $\circ$ se valgono i seguenti quattro assiomi.




 

 


<!--stackedit_data:
eyJoaXN0b3J5IjpbOTMyMzExNTUxLDY3MjM0NjI5MiwtMjEyNT
I2MjUxOCwtMTUyMzEyMDA3NiwtMTk5MDAxNTcyMCw4Njg1NTIx
MTIsMTg5MzA2MzgyNiwtMTY0MDY3NjU0MiwxNjUwMDA0NDI4LD
E1NzgwNDcyOTgsMTY0ODQ1NzQ1OCwxMjI0NDQ0MzkwLDE3MDA3
MDkyOTldfQ==
-->