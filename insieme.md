# Insiemi
##### WikipediA
In matematica, un insieme è un insieme di elementi.  
Gli elementi che compongono un insieme possono essere qualsiasi tipo di [[oggetto matematico]]: numeri, simboli, [[coordinate|punti nello spazio]], [[retta|linee]], altre forme geometriche, variabili o anche altri insiemi.

![[schema-simboli-NUMERI1.png]]

## Notazioni insiemi
La notazione standard è la seguente:

- $X = \{x_1,x_2,x_3,x_4\}$ --> per definire un insieme X (anche detta Roster notation)

Si usa la scrittura "..." come short-hand per non scrivere tutti gli elementi di un insieme, sottointendendo che si stia seguendo un pattern implicito:
$$ X = \{0,2,4,...,222,224,226\}$$
e la medesima scrittura è utile per delineare che un insieme è infinto:
- $Z = \{...,-2,-1,0,+1,+2,...\}$
- $Z^+ = \{0,+1,+2,...\}$
- $Z^- = \{...,-2,-1,0\}$

**Notazione importante:**
La notazione "set-builder" consiste nella costruizione un insieme partendo da un insieme più grande attraverso l'applicazione di una condizione sugli elementi di quest'ultimo:

- $X = \{x\hspace{1mm}|\hspace{1mm}f(x), x \in R\}$

Si possono identificare 3 parti che compongono questa notazione (dentro le graffe):
1.	la variabile $x$
2.	il simbolo "|" (tale che)
3.	$f(x), x \in R$, ovvero la regola che definisce tutti i valori che assume la variabile (i quali a loro volta formeranno l'insieme $X$)

## Cardinalità degli insiemi
	La cardinalità di un insieme indica il numero di elementi presenti al suo   interno, ad esempio:

$$ X = \{1,2,3,4\} \rightarrow |X| = 4  $$

Si dice inoltre che due insiemi condividono una* relazione 1-1* se posseggono la medesima .

### Casi particolari di cardinalità:

L'elenco degli elementi di alcuni insiemi è infinito o infinito. Ad esempio, l'insieme $N$ dei numeri naturali è infinito. Infatti, tutti gli insiemi speciali di numeri menzionati nella sezione precedente, sono infiniti. `Gli insiemi infiniti hanno cardinalità infinita`.

## L'insieme della parti
	l'insieme delle parti di X è l'insieme di tutti i sottoinsiemi di X. 
L'insieme vuoto e X stesso sono elementi dell'insieme delle parti di X, perché entrambi sono sottoinsiemi di X. Ad esempio, la potenza dell'insieme {1, 2, 3} è {∅, {1}, {2}, {3}, {1, 2}, {1, 3}, {2, 3}, {1, 2, 3}}. L'insieme delle parti di X è comunemente scritto come $P(X)$ o $2^x$.

In generale si può dire che la potenza $P(X)$ di un insieme X è scrivibile come $2^n$, dove n è il rango di X, ovvero il numero di elementi appartenenti all'insieme. Ad esempio la potenza dell'insieme {1, 2, 3} è $2^3 = 8$.

## Operazioni base degli insiemi
Le principali operazioni che si possono svolgere tra insiemi sono unione e intersezione:
#### Unione ($\cup$)
Due insiemi A e B possono essere uniti ($A \cup B$ ) come negli esempi di seguito:
- {1, 2} $\cup$ {1, 2} = {1, 2}
- {1, 2} $\cup$ {2, 3} = {1, 2, 3}
- {1, 2, 3} $\cup$ {3, 4, 5} = {1, 2, 3, 4, 5}

Le proprietà dell'operazione di _unione_ tra insiemi sono:
1. $A \cup B = B \cup A \hspace{1cm}$([[proprietà commutativa]])
2. $A \cup (B \cup C)= (A \cup B) \cup C \hspace{1cm}$([[proprietà associativa]])
3. $A \subseteq (A \cup B) \hspace{1cm}$
4. $A \cup A = A \hspace{1cm}$([[proprietà di idempotenza]])
5. $A \cup \emptyset = A \hspace{1cm}$(legge dell'[[identità]])
6. $A \subseteq B \iff	A \cup B = B \hspace{1cm}$

