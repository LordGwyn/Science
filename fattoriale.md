---
tags:
aliases:
cssclass: statisticaeprobabilità
---
# Statistica e Probabilità
Introduzione e argomenti di base.
## Intro
Per iniziare a considerare un qualsiasi scenario dove è necessario calcolare la probabilità che un evento possa accadere, è prima doveroso comprendere il contesto di tale evento. Si prende come esempio la situazione in cui si lancia una fair-moneta che garantisce, una volta lanciata, che c'è il 50% di probabilità che esca **testa** e il 50% di probabilità che esca **croce**. In questa situazione gli outcome possibili a seguito di un lancio sono due, ovvero testa (d'ora in poi **<mark>H</mark>**) o croce (**<mark>T</mark>**), e questi due eventi che racchiudono il 100% delle possibilità di cosa potrà mai uscire dopo il lancio della moneta (si esclude il caso in cui la moneta cade in verticale), formano insieme il cosidetto **spazio campionario** (sample space).
Lo spazio campionario viene definito con la lettera $S$, e più in generale definisce tutti i possibili outcome al verificarsi di un certo evento. Ad esempio:
- spazio camp. di un lancio di una moneta: $S=\{H,T\},\; |S|=2$
- spazio camp. di un lancio di un dado: $S=\{1,2,3,4,5,6\},\; |S|=6$
- spazio camp. di un'estrazione di $n$ biglie da un urna: $S=\{1,\dots,n\},\; |S|=n$

Una volta definito lo spazio campionario è possibile definire con facilità la probabilità che un certo evento accada, ad esempio se lancio un dado so che appena si ferma potrà uscire solo un numero, ma prima di lanciarlo, guardando lo spazio campionario, sapevo che c'erano 6 possibilità distinte come outcome del numero finale, tutte equamente probabili. Allora posso dire che la probabilità che, una volta lanciato il dado, esca un qualsiasi numero è di $\frac{1}{6}$.
Le cose si complicano però quando dallo studio di un singolo evento si passano a studiare i casi in cui di fanno molteplici tiri/estrazioni a differenza del contesto. Allora è qua che entrano in gioco i concetti di *permutazione* e *combinazione* .

## Permutazione <span style="font-size: 70%; font-weight:300;"> vs.</span> Combinazione
I concetti di *permutazione* e *combinazione* sono definiti sulle sequenze di eventi che siano tra loro dipendenti o indipendenti. La differenza tra le due è una fondamentalmente:<span class="importante"> Nella **permutazione** **<u>conta</u>** l'ordine con cui gli eventi si susseguono, mentre <br>nella **combinazione** **<u>no</u>**. </span> vale a dire (nell'esempio in cui di lancia 3 volte un dado a 6 facce):
1. le sequenze $(1,2,3)$ e $(3,2,1)$ valgono come due **permutazioni** *distinte*
2. le sequenze $(1,2,3)$ e $(3,2,1)$ sono considerate la *stessa* **combinazione**

vale a  dire che nel primo caso l'ordine con il quale gli stessi numeri sono usciti è determinante per definire le due sequenze come diverse, mentre nel secondo no :).

Una volta appresi questi concetti di base è possibile iniziare ad addentrarsi in concetti più complicate del calcolo combinatorio.


## Fattoriale
L'operazione "fattoriale" si può dire la più semplice trai casi di calcolo combinatorio. Esso risponde a domande del tipo: "Quanti numeri posso scrivere usando le cifre "12345" senza ripetezioni ????", o "Qual' è la probabilità che estraendo tutte le biglie da un'urna, escano in un preciso ordine?", ovvero i casi in cui si susseguono degli eventi tra loro **dipendenti** (nel caso dell'urna, se si estrae una biglia, si va ridurre il numero totale di biglie rimanenti nell'urna, andando a cambiare la probabilità di estrazione di una seconda biglia).

Concettualmente il fattoriale si sviluppa in questo modo:

<span class="center">- <mark>In un'urna ho $n$ biglie numerate da $1$ a $n$</mark> - 
1. Il sample space $|S|$ vale quindi $n$. Quindi posso dire che alla prima estrazione ho $n$ probabilità di estrarre una bilgia.
2. Ripeto l'estrazione con le biglie rimanenti, che stavolta saranno $n-1$.
3. Ripeto tante estrazione fino a finire le biglie, ovvero quando estraggo 1 biglia rimanente.
4. Ottengo così una sequenza di biglie numerate (es. suppenendo ci fossero 5 biglie, ottengo $(1,2,3,4,5)$) 

</span>

La domanda è: Qual'è la probabilità di ottenere proprio quella sequenza?
La risposta è il fattoriale che tiene in considerazione il cambiamento di ogni estrazione, e combina le probabilità di ciascuna di esse in questo modo:
<span class="importante"> $P = n!=n \cdot (n-1) \cdot (n-2)\; \cdot \; ... \, \cdot \;1$ </span>

Il risultato sono tutte le possibili permutazioni di sequenze di $n$ biglie estratte, quindi la probabilità di ottenere una qualsiasi sequenza da $n$ estrazioni, è di $\frac{1}{n!}$.

e va bene così si è capito il concetto.

## Permutazioni <sup>n</sup>P<sub>r</sub>
Non so bene come chiamare questa cosa, ma sostanzialmente  è il calcolo delle probabilità di $k$ estrazioni a partire da $n$ oggetti, dove $k \leq n$.
C'è da chiarire un presuposto prima di inziare. nei due scenari:
 1. P<sub>1</sub>: $S=\{1,2,3\}$, con 3 estrazioni.
 2. P<sub>2</sub>: $S=\{1,2,3,4,5\}$, con 3 estrazioni.

non c'è la stessa probabilità che vengano estratte due sequenze identiche.

Ciòdetto capiamo il perchè. 
Sappiamo già che la prob. che esca fuori $(1,2,3)$ nel caso P<sub>1</sub> è $\displaystyle\frac{1}{3!}=\frac{1}{6}=16.66\%$
Calcoliamo P<sub>2</sub>: In pratica serve utilizzare questa formula:
<span class="importante"> $P = \displaystyle\frac{n!}{(n-k)!}$ </span>
Il motivo è prestodetto: a noi serve calcolare la probabilità delle prime $k$ estrazioni, ovvero dobbiamo calcolare $\displaystyle^nP_k = n \cdot (n-1)\cdot [\dots] \cdot (n - (k+1))$ (che non è altro che un secondo modo di riscrivere la formula di sopra, e il "$+1$" c'è perchè contando le estrazioni si tiene in considerazione anche la prima) che vuol dire automaticamente che dobbiamo escludere dal calcolo tutte le rimanenti parti del fattoriale perchè corrisponderebbero ad estrazioni che non dovrebberoavvenire. Per fare ciò si mette al denominatore un termine che semplificandosi col numeratore, lascia soltanto il numero di estrazioni interessate.
Esempio con $n$=10 e $k$=3:
$$ \begin{array}{rcl}
=\frac{n!}{(n-k)!}=&
\\
=\frac{10!}{(10 -3)!}=&
\\
=\frac{10\cdot 9 \cdot 10\cdot 9 \cdot 8\cdot 7 \cdot 6\cdot 5 \cdot 4\cdot 3 \cdot 2 \cdot 1}{7 \cdot 6\cdot 5 \cdot 4\cdot 3 \cdot 2 \cdot 1} = dfsd &

\end{array}
$$

***

Tags:  
#statisticaeprobabilità

Corso:  
[#tag](app://obsidian.md/index.html#tag)