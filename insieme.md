# Insiemi

<div align="center">In matematica, un insieme è un insieme di cose, chiamate elementi.</div>

Gli elementi che compongono un insieme possono essere qualsiasi tipo di [[oggetto matematico]]: numeri, simboli, [[coordinate|punti nello spazio]], [[retta|linee]], altre forme geometriche, variabili o anche altri insiemi.

Alcune definizioni di base:
1. Un insieme è detto __infinito__ se contiene un numero _infinito_ di elementi, e al contrario è detto __finito__ se contiene un numero _finito_ di elementi.
2. Due insiemi si dicono __equivalenti__ se contengono gli stessi elementi, anche in ordine diverso. Ad esempio $\{2,4,6,8\} = \{4,2,8,6\}$ e $\{2,4,6,8\} \ne \{2,4,6,7\}$
3. Gli insiemi si indicano generalmente con una lettera maiuscola.
4. Gli insiemi più importanti sono:

![[schema-simboli-NUMERI1.png]]

## Notazioni insiemi
La notazione standard è la seguente:

- $X = \{x_1,x_2,x_3,x_4\} \rightarrow$ per definire un insieme X (anche detta Roster notation)

Si può usare la scrittura "$\dots$" come short-hand per non scrivere tutti gli elementi di un insieme, sottointendendo che si stia seguendo un pattern implicito:
$$ X = \{0,2,4,...,222,224,226\}$$
la medesima scrittura è utile per delineare che un insieme è infinito:
- $Z = \{...,-2,-1,0,+1,+2,...\}$
- $Z^+ = \{0,+1,+2,...\}$
- $Z^- = \{...,-2,-1,0\}$
<div id="line_spacing"></div>
##### Notazione importante:
La notazione "set-builder" consiste nella costruizione un insieme partendo da un insieme più grande attraverso l'applicazione di un [[logica#Proposizioni Aperte o Predicati|predicato]] sugli elementi di quest'ultimo:

$$X = \{x\hspace{1mm}|\;\forall x \in R, f(x)\}\hspace{.5cm} \text{or} \hspace{.5cm} X = \{x\hspace{1mm}:\;\forall x \in R, f(x)\}$$

questa notazione è "semplificabile" nel modo seguente:

$$X = \{\text{espressione} : \text{regola}\},$$

dove gli elementi di $X$ sono intesi essere tutti i valori di "espressione" che sono specificati dalla "regola". Ad esempio: si vuole definire l'insieme $E$ come l'insieme dei numeri naturali pari attraverso questa notazione. 
Alcuni modi per farlo sono:

$$E = \{2n:n\in \Bbb{N}\} = \{n \in \Bbb{N}: n\text{ is even}\}  = \{n:n=2k,k \in \Bbb{N}\}$$


---
## Insieme vuoto
Esiste un insieme speciale che gioca un ruolo importante in matematica, ed è l'insieme $\{\}$, che non possiede elementi. Tale insieme è detto __insieme vuoto__ e viene indicato dal simbolo $\emptyset$, perciò $\emptyset = \{\}$.


---
## Cardinalità degli insiemi
<div align="center">La cardinalità di un insieme indica il numero di elementi presenti al suo interno e si indica attraverso i simboli "||".</div>
ad esempio:

$$ X = \{1,2,3,4\} \rightarrow |X| = 4  $$

Si dice inoltre che due insiemi condividono una* relazione 1-1* se posseggono la medesima cardinalità.

### Casi particolari di cardinalità:
- L'insieme vuoto ha cardinalità 0: $|\emptyset| = 0$.
- Il numero di elementi di alcuni insiemi è infinito. Ad esempio l'insieme $N$ dei numeri naturali è infinito, infatti tutti gli insiemi speciali menzionati nella sezione precedente ($\Bbb{N}$,$\Bbb{Z}$,$\Bbb{Q}$,$\Bbb{R}$,...) sono infiniti. Gli insiemi infiniti hanno cardinalità infinita.

---
## L'insieme della parti
<div align="center">L'insieme delle parti di <span class="math display">X</span>, indicato dal simbolo <span class="math display">\mathcal{P}(X)</span>, è l'insieme di tutti i sottoinsiemi di <span class="math display">X</span>.</div>

L'insieme vuoto e $X$ stesso sono elementi dell'insieme delle parti di $X$, perché entrambi sono sottoinsiemi di $X$. Ad esempio, la potenza dell'insieme {1, 2, 3} è {∅, {1}, {2}, {3}, {1, 2}, {1, 3}, {2, 3}, {1, 2, 3}}. L'insieme delle parti di X è comunemente scritto come $P(X)$ o $2^x$.

In generale si può dire che la potenza $\mathcal{P}(X)$ di un insieme X è scrivibile come $2^n$, dove n è il rango di X, ovvero il numero di elementi appartenenti all'insieme. Ad esempio la potenza dell'insieme {1, 2, 3} è $2^3 = 8$.

---
## Insieme complementare
Dato un insieme A, sottoinsieme di X si definisce ==*complementare*== di A in X, il sottoinsieme:

$$ CA=\{x \in X \; | \; x \notin A\} $$

talvolta per specificare l'insieme di riferimento del complementare, viene usata la notazione $C_XA$.
Alcune propretà base degli insiemi complementari vengono immediate:
- $CX = \emptyset$
- $C\emptyset = X$
- $C(CA) = A$

---
## Operazioni base degli insiemi
Le principali operazioni che si possono svolgere tra insiemi sono unione e intersezione:

#### Unione
si definisce unione tra un sottoinsieme A e un sottoinsieme B, l'insieme:

$$A \cup B = \{ x \in X \;|\; x \in A \;\textrm{oppure}\; x \in B \}$$

Le proprietà dell'operazione di _unione_ tra insiemi sono:
1. $A \cup B = B \cup A \hspace{1cm}$([[proprietà commutativa]])
2. $A \cup (B \cup C)= (A \cup B) \cup C \hspace{1cm}$([[proprietà associativa]])
3. $(A \cup B) \cap C = (A \cap C) \cup (B \cap C)\hspace{1cm}$([[proprietà distributiva]])

#### Intersezione
si definisce intersezione tra un sottoinsieme A e un sottoinsieme B, l'insieme:

$$A \cap B = \{ x \in X \;|\; x \in A \;\textrm{e}\; x \in B \}$$

Le proprietà dell'operazione di _intersezione_ tra insiemi sono:
1. $A \cap B = B \cap A \hspace{1cm}$([[proprietà commutativa]])
2. $A \cap (B \cap C)= (A \cap B) \cap C \hspace{1cm}$([[proprietà associativa]])
3. $(A \cap B) \cup C = (A \cup C) \cap (B \cup C)\hspace{1cm}$([[proprietà distributiva]])

___
## Differenza tra insiemi
Il primo tipo di differenza tra insiemi è la _differenza non simmetrica_ che si definisce in questo modo:

$$ A \setminus B = \{ x \in A \;|\; x \notin B \} =  A \cap C_XB$$

![[sottrazione insieme asimmetrica.PNG]]

dove l'insieme $A \setminus B$ contiene tutti gli elementi di A che non sono in B, ovvero che sono "propietari" di A.

Il secondo tipo di differenza è detta _simmetrica_ ed è definita nel modo seguente:

$$ A \;\Delta\; B = (A \setminus B) \cup (B \setminus A) = (A \cup B) \setminus (A \cap B)$$

![[sottrazione insieme simmetrica.PNG]]

la quale seleziona gli elementi che stanno o in A o in B, ma non in entrambi.

---

Tags:
#prerequisiti
#differenza_insiemi
#cardinalità 
#unione
#intersezione

Corso:
#analisi1