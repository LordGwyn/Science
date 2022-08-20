# Insiemi

<div class="importante">In matematica, un insieme è un insieme di cose, chiamate elementi.</div>

Gli elementi che compongono un insieme possono essere qualsiasi tipo di [[oggetto matematico]]: numeri, simboli, [[coordinate|punti nello spazio]], [[retta|linee]], altre forme geometriche, variabili o anche altri insiemi.

Alcune definizioni di base:
1. Un insieme è detto __infinito__ se contiene un numero _infinito_ di elementi, e al contrario è detto __finito__ se contiene un numero _finito_ di elementi.
2. Due insiemi si dicono __equivalenti__ se contengono gli stessi elementi, anche in ordine diverso. Ad esempio $\{2,4,6,8\} = \{4,2,8,6\}$ e $\{2,4,6,8\} \ne \{2,4,6,7\}$
3. Gli insiemi si indicano generalmente con una lettera maiuscola.


## Notazioni insiemi
La notazione standard è la seguente:

- $X = \{x_1,x_2,x_3,x_4\} \rightarrow$ per definire un insieme X (anche detta Roster notation)

Si può usare la scrittura "$\dots$" come short-hand per non scrivere tutti gli elementi di un insieme, sottointendendo che si stia seguendo un pattern implicito:
$$ X = \{0,2,4,...,222,224,226\}$$
la medesima scrittura è utile per delineare che un insieme è infinito:
- $Z = \{...,-2,-1,0,+1,+2,...\}$
- $Z^+ = \{0,+1,+2,...\}$
- $Z^- = \{...,-2,-1,0\}$
<br>
##### Notazione importante:
La notazione "set-builder" consiste nella costruizione un insieme partendo da un insieme più grande attraverso l'applicazione di un [[logica#Proposizioni Aperte o Predicati|predicato]] sugli elementi di quest'ultimo:

$$X = \{x\hspace{1mm}|\;\forall x \in R, f(x)\}\hspace{.5cm} \text{oppure} \hspace{.5cm} X = \{x\hspace{1mm}:\;\forall x \in R, f(x)\}$$

questa notazione è "semplificabile" nel modo seguente:

$$X = \{\text{espressione} \mid \text{regola}\},$$

dove gli elementi di $X$ sono intesi essere tutti i valori di "espressione" che sono specificati dalla "regola". Ad esempio: si vuole definire l'insieme $E$ come l'insieme dei numeri naturali pari attraverso questa notazione. 
Alcuni modi per farlo sono:

$$E = \{2n|n\in \Bbb{N}\} = \{n \in \Bbb{N}| n\text{ is even}\}  = \{n|n=2k,k \in \Bbb{N}\}$$


---

## Insiemi Numerici
|Simboli|Significato|
|-|-|
|$\Bbb{N}$|Insieme dei numeri **naturali** $\{0,1,2,3,\dots\}$|
|$\Bbb{Z}$|Insieme dei numeri **interi** $\{\dots,-3,-2,-1,0,+1,+2,+3,\dots\}$|
|$\Bbb{Z}^+$|Insieme dei numeri **interi positivi** (zero escluso)|
|$\Bbb{Z}^-$|Insieme dei numeri **interi negativi** (zero escluso)|
|$\Bbb{Q}$|Insieme dei numeri **razionali** $\{\dots,-\frac{1}{2},0,+\frac{1}{2},\dots\}$|
|$\Bbb{Q}^+$|Insieme dei numeri **razionali positivi** (zero escluso)|
|$\Bbb{Q}^-$|Insieme dei numeri **razionali negativi** (zero escluso)|
|$\Bbb{R}$|Insieme dei numeri **reali** $\{\dots,-\frac{1}{2},0,+\frac{1}{2},\sqrt{2},\sqrt{3},e,\pi,\dots\}$|
|$\Bbb{R}^+$|Insieme dei numeri **reali positivi** (zero escluso)|
|$\Bbb{R}^-$|Insieme dei numeri **reali negativi** (zero escluso)|
|$\Bbb{C}$|Insieme dei numeri **complessi** $\{riempire\}$|


### Insieme  $\Bbb{N}$
L'insieme è formato dai numeri **naturali** $0, 1, 2, \dots$ 
In esso sono definite le operazioni di *somma* e *prodotto*,  che godono delle ben note proprietà [[proprietà commutativa|commutativa]], [[proprietà associativa|associativa]] e [[proprietà distributiva|distributiva]].
### Insieme  $\Bbb{Z}$
L'insieme dei numeri **interi relativi**.
In esso sono definite le operazioni di somma e prodotto e inoltre l'operazione di *differenza* che è l'inverso della somma.

### Insieme  $\Bbb{Q}$
L'insieme dei numeri **razionali**. Un numero razionale è definito come il quoziente tra un numero intero relativo $z$ e un numero naturale $n$ diverso da $0$. Non è restrittivo supporre che il denominatore sia positivo, per cui ogni razionale può essere rappresentato come:
<div class="importante"> <span class="math display"> r = \dfrac{z}{n}, \text{ con } z \in \Bbb{Z}\text{ e } n \in \Bbb{N^+} </span> </div>

### Insieme  $\Bbb{R}$
L'insieme dei numeri **reali** costituisce un'estensione dell'insieme dei numeri razionali poichè comprende i numeri irrazionali (numeri con una rappresentazione decimale *illimitata* e *non periodica* non rappresentabili come frazione tra un intero e un naturale) e fornisce un modello matematico della [[retta]], nel senso che ogni [[punto]] $P$ della retta è associato a uno e un solo numero reale $x$ detto l'ascissa di $P$, e viceversa.

Esistono alcune proprietà dei numeri reali che è necessario menzionare:
1. <span class="times">Le operazioni aritmetiche definite sui razionali si estendono ai reali, con analoghe proprietà.</span>
2. <span class="times">L'ordinamento dei razionali $x < y$ si estende anche ai reali con analoghe proprietà.</span>
3. <span class="times">I numeri razionali sono densi nei reali</span>. Ciò significa che tradue numeri reali qualunque esistono infiniti numeri razionali. Questa proprieà implica che ogni numero reale può essere approssimato può essere approssimato tanto bene quanto vogliamo da un numero razionale.
4. <span class="times">L'insieme dei numeri reali è completo</span>. Questa proprietà, che geometricamente equivale al fatto, gia menzionato, che ogni punto di una retta può essere univocamente associato a un numero reale, garantisce ad esempio l'esistenza della radice quadrata di 2, cioè la risolubilità in R dell'equazione $x^2 = 2$, così come la risolubilità di infinite altre equazioni, algebriche e non.

***
## Sottoinsieme
<div class="importante"> 
	In matematica un insieme <span class="math display"> A </span> è detto <em>sottoinsieme</em> di un insieme <span class="math display"> B </span> se tutti gli elementi di <span class="math display"> A </span> sono anche elementi di <span class="math display"> B.</span>
<div>

Matematicamente l'insieme $A$ sottoinsieme di $B$, indicato con la forma ==$A\subseteq B$==, è tale se rispetta la seguente definizione:
<div class="importante"> <span class="math display">  A\subseteq B \iff \forall x : (x\in A \implies x \in B) </span> <div>

E' quindi possibile che $A$ sia considerato sottoinsieme di $B$ anche se $A$ e $B$ possiedono gli stessi elementi. Ed è questa possibilità che stabilisce una distinzione tra i due tipi di sottoinsiemi possibili:
- Il sottoinsieme $A$ è detto *proprio* rispetto a $B$ se esiste almeno un elemento appartenente a $B$ che non appartiene ad $A$:$$
\begin{array}{rcl}
\forall x : (x\in A \implies x \in B) & \land & \exists  x \in B: x \notin A
\end{array}
$$ e si indica con ==$A \subset B$==;
- Il sottoinsieme $A$ è invece detto *improprio* rispetto a $B$ se: $$ \forall x : (x\in A \iff x \in B)$$ dove è necessario che $x$ appartenga ad $A$ perche possa appartenere anche a $B$, andando ad escludere da $B$ ogni $x$ che non appartiene ad $A$. In questo caso è praticamente possibile affermare che $A = B$, ma per esprimere il concetto che si tratta di un sottoinsieme improprio bisogna dire ==$A\subseteq B$== perchè nel simbolo $\subseteq$, similmente al concetto di $\ge$ e di $\leq$ è inclusa anche l'uguaglianza.
***

# Insiemi limitati
Sia $A$ un sottoinsieme non vuoto di $\Bbb{R}$.

- Diciamo che $A$ è ==**superiormente limitato**== se esiste un numero $b \in \Bbb{R}$ tale che
	<div class="importante"> 
		<span class="math display">
			\begin{array}{rcl}
			x \le b, & \forall x \in A
			\end{array}
		</span>
	</div> ogni <span class="math display">b</span> che soddisfa tale relazione viene detto <strong><u>un maggiorante</u></strong> di <span class="math display">A</span>.
- Diciamo che $A$ è ==**inferiormente limitato**== se esiste un numero $a \in \Bbb{R}$ tale che
	<div class="importante"> 
		<span class="math display">
			\begin{array}{rcl}
			a \le x, & \forall x \in A
			\end{array}
		</span>
	</div>ogni <span class="math display">a</span> che soddisfa tale relazione viene detto <strong><u>un minorante</u></strong> di <span class="math display">A</span>.
- Diciamo che $A$ è ==**limitato**== se è contemporaneamente superiormente e inferiormente limitato.

<span id="bigText" class="text_divisor">Note: </span>

In termini di [[intervallo|intervalli]], un insieme è superiormente limitato se è contenuto in un intervallo del tipo $(-\infty,b]$ o anche $(-\infty,b)$  per qualche $b \in \Bbb{R}$.
Similmente $A$, è limitato se contenuto in un intervallo del tipo $[a,b]$, che vuol dire che per ogni $x$ l'insieme è definito come $a \le x \le b$. Da questo non è difficile convincersi che, dato un numero reale e positivo $c$, un insieme limitato può essere definito attraverso l'espressione:

<span class="importante"> $
\begin{array}{rcl}
|x| \le c, && \text{per ogni } x\in A
\end{array}$
</span>

dove l'intervallo sarà del tipo $[x_1,x_2]$, dove $x_1$ e $x_2$ sono le soluzioni dell'equazione $|x| \le c$.

### Massimo e Minimo

Dato un insieme $A \subset \Bbb{R}$:
- Si dice che $A$ ammette un **<u>massimo</u>** ($x_M$) se esiste un elemento ==$x_M \in A$== tale che
	<div class="importante"> 
		<span class="math display">
		\begin{array}{rcl}
		x \le x_M, && \text{per ogni } x\in A
		\end{array}
		</span>
	 </div>

- Si dice che $A$ ammette un **<u>minimo</u>** ($x_m$) se esiste un elemento ==$x_m \in A$== tale che
	<div class="importante"> 
		<span class="math display">
		\begin{array}{rcl}
		x \ge x_m, && \text{per ogni } x\in A
		\end{array}
		</span>
	 </div>

<div id="line_spacing"></div>

A differenza dei maggioranti e minoranti, il <strong>minimo</strong> e il <strong>massimo</strong> sono elementi appartenenti all'insieme di riferimento, quindi in caso $A$ permetta un massimo $x_M$, allora si può dire che l'insieme è superiormente limitato e $x_M$ è il più piccolo dei maggioranti (e analogamente anche nel caso in cui $A$ ammetta un minimo).

<span class="attenzione"> E' sempre vero dire che se un insieme ammette un massimo, allora è superiormente limitato, tuttavia non è sempre vero il contrario: un insieme può essere superiormente limitato senza ammettere un massimo.</span>
<div id="line_spacing"></div>

### Estremo superiore e inferiore

Sia $A \subset \Bbb{R}$ un insieme **superiormente limitato**:
- <span class="importante"> Chiamiamo **estremo superiore** di $A$ il più piccolo dei **maggioranti** di $A$ </span> denotiamo tale numero con =="$\sup{A}$"==

Sia $A \subset \Bbb{R}$ un insieme **inferiormente limitato**:
- <span class="importante"> Chiamiamo **estremo inferiore** di $A$ il più piccolo dei **maggioranti** di $A$ </span>denotiamo tale numero con =="$\inf{A}$"==

<span class="teorema"> <span class="teorema_titolo">[[teorema degli insiemi limitati]] </span> Se un qualsiasi insieme $A \subset \Bbb{R}$ è **superiormente limitato** (ovvero che ammette dei maggioranti), allora ammette un **estremo superiore**. 
Analogamente, vale anche per un insieme **inferiormente limitato**.</span>


***

## Insieme vuoto
Esiste un insieme speciale che gioca un ruolo importante in matematica, ed è l'insieme $\{\}$, che non possiede elementi. Tale insieme è detto __insieme vuoto__ e viene indicato dal simbolo $\emptyset$, perciò $\emptyset = \{\}$.


---
## Cardinalità degli insiemi
<div class="importante">La cardinalità di un insieme indica il numero di elementi presenti al suo interno e si indica attraverso i simboli "<span class="math display">|\cdots|</span>".</div>
ad esempio:

$$ X = \{1,2,3,4\} \rightarrow |X| = 4  $$

Si dice inoltre che due insiemi condividono una** relazione 1-1** se posseggono la medesima cardinalità.

### Casi particolari di cardinalità:
- L'insieme vuoto ha cardinalità 0: $|\emptyset| = 0$.
- Il numero di elementi di alcuni insiemi è infinito. Ad esempio l'insieme $N$ dei numeri naturali è infinito, infatti tutti gli insiemi speciali menzionati nella sezione precedente ($\Bbb{N}$,$\Bbb{Z}$,$\Bbb{Q}$,$\Bbb{R}$,...) sono infiniti. Gli insiemi infiniti hanno cardinalità infinita.

---
## L'insieme della parti
<div class="importante">
L'insieme delle parti di <span class="math display">X</span>, indicato dal simbolo <span class="math display">\mathcal{P}(X)</span>, è l'insieme di tutti i sottoinsiemi di <span class="math display">X</span>.
</div>

L'insieme vuoto e $X$ stesso sono elementi dell'insieme delle parti di $X$, perché entrambi sono sottoinsiemi di $X$. Ad esempio, l'insieme delle parti di {1, 2, 3} è: 
$$\emptyset, \{1\}, \{2\}, \{3\}, \{1, 2\}, \{1, 3\}, \{2, 3\}, \{1, 2, 3\}$$ 
L'insieme delle parti di $X$ è comunemente scritto come $\mathcal{P}(X)$ o $2^x$.

In generale si può dire che la potenza $\mathcal{P}(X)$ di un insieme X è scrivibile come $2^n$, dove n è il rango di X, ovvero il numero di elementi appartenenti all'insieme. Ad esempio la potenza dell'insieme {1, 2, 3} è $2^3 = 8$.

---
## Insieme complementare
Dato un insieme $A$, sottoinsieme di $X$ si definisce **<u>complementare</u>** di $A$ in $X$, il sottoinsieme:

<span class="importante"> $A^C := \{x \in X \; | \; x \notin A\}$ <span>

Talvolta per specificare l'insieme di riferimento del complementare, viene usata la notazione $C_X A$.
Alcune propretà base degli insiemi complementari vengono immediate:
- $X^C = \emptyset$
- $\emptyset^C = X$(qualsiasi insieme)
- $\left(A^C\right)^C = A$
***

## Partizione di un insieme

Una partizione $P$ di un insieme $S$ è una collezione (ovvero un insieme) degli elementi di $S$ che rispetta le seguenti due condizioni:
1. ==Tutti gli elementi di $P$ devono essere dei sottoinsiemi **<u>non vuoti</u>** dell'insieme $S$.==
2. ==**<u>Ogni elemento</u>** di $S$ deve essere presente **<u>esattamente</u>** 1 volta in 1 elemento di $P$.==

Detto a parole una partizione non è altro che una suddivisione in sottoinsiemi disgiunti (senza elementi in comune) dell'l'isieme di riferimento $S$.

<span id="bigText" class="text_divisor">Esempi: </span>
Sono una partizione di $S = \{1,2,3\}$ i seguenti insiemi:
- $\{\{1\},\{2\},\{3\}\}$
- $\{\{3\},\{2\},\{1\}\}$
- $\{\{1,2\},\{3\}\}$
- $\{\{1\},\{2,3\}\}$
- $\{\{2\},\{1,3\}\}$
- $\{\{1,2,3\}\}$
- $..$.

Non sono una partizione di $S$ invece:
- $\{\{1\},\{2\},\{\}\}$ (i sottoinsiemi devono essere non vuoti)
- $\{\{1\},\{2\}\}$ (**ogni** elemento di $S$ deve appartenere a $P$)
- $\{\{1,3\},\{2,3\}\}$ (ogni elemento di $S$ deve essere presente **esattamente** una volta in  un elemento di $P$)
- $\{\{1,3\},\{2,4\}\}$ (4 non appartiene ad $S$, quindi $P$ non è composta da soli sottoinsiemi di $S$)

***
## Operazioni base degli insiemi
Le principali operazioni che si possono svolgere tra insiemi sono unione e intersezione:

<span id="bigText">Unione: </span>
si definisce unione tra un sottoinsieme A e un sottoinsieme B, l'insieme:

$$A \cup B = \{ x \in X \;|\; x \in A \;\textrm{oppure}\; x \in B \}$$

Le proprietà dell'operazione di _unione_ tra insiemi sono:
1. $A \cup B = B \cup A \hspace{1cm}$([[proprietà commutativa]])
2. $A \cup (B \cup C)= (A \cup B) \cup C \hspace{1cm}$([[proprietà associativa]])
3. $(A \cup B) \cap C = (A \cap C) \cup (B \cap C)\hspace{1cm}$([[proprietà distributiva]])

<span id="bigText">Intersezione: </span>
si definisce intersezione tra un sottoinsieme A e un sottoinsieme B, l'insieme:

$$A \cap B = \{ x \in X \;|\; x \in A \;\textrm{e}\; x \in B \}$$

Le proprietà dell'operazione di _intersezione_ tra insiemi sono:
1. $A \cap B = B \cap A \hspace{1cm}$([[proprietà commutativa]])
2. $A \cap (B \cap C)= (A \cap B) \cap C \hspace{1cm}$([[proprietà associativa]])
3. $(A \cap B) \cup C = (A \cup C) \cap (B \cup C)\hspace{1cm}$([[proprietà distributiva]])

___
## Differenza tra insiemi
Il primo tipo di differenza tra insiemi è la _differenza non simmetrica_ che si definisce in questo modo:

$$ A \setminus B = \{ x \in A \;|\; x \notin B \} =  A \cap C_XB $$

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