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
L'operazione "fattoriale" si può dire la più semplice trai casi di calcolo combinatorio. Esso risponde a domande del tipo: "Quanti numeri posso scrivere usando le cifre "12345" senza ripetezioni ????", o "Qual' è la probabilità che estraendo tutte le biglie da un'urna, escano in un preciso ordine?", ovvero i casi in cui si susseguono degli eventi tra loro **dipendenti**.

<span id="bigText" class="text_divisor">Note: </span>

<span id="bigText" class="text_divisor">Esempi: </span>

***

Tags:  
#statisticaeprobabilità

Corso:  
[#tag](app://obsidian.md/index.html#tag)