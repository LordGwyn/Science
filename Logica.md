# Logica
## Proposizione logica o Statement
<div align="center">In logica, una proposizione è un enunciato al quale si può inequivocabilmente attribuire, in un certo contesto, un valore di verità V o F.</div>

Esempi di proposizioni logiche sono:
- 7 è un numero dispari (Vero)
- $3 > \sqrt{12}$ (Falso)
-  Venere è una stella (Falso)

Al contrario, l'enunciato "Milano è lontana da Roma" non è una proposizione logica poichè mancano delle precisazioni sul concetto di lontananza.
E' una proposizione logica invece l'espressione "Milano è più lontana di Torino da Roma" pur essendo falsa.

Le proposizioni logiche vengono indicate solitamente da una lettera minuscola $p$, $q$, $r$, $etc$...

### Proposizioni Aperte o Predicati
Esistono dei casi in cui una proposizione logica può riferirsi a delle variabili, come ad esempio $x$, e in tal caso la proposizione guadagna l'aggettivo "aperta", diventando una __proposizione aperta__ (_open sentence_), poichè di tale proposizione non è possibile definire il valore di verità se non attribuendo un valore alla variabile. 
Le proposizioni aperte si indicano con una lettera minuscola $p$, $q$, $r$, ... e delle parentesi tonde in questo modo: $p(x)$ per indicare che lo statement $p$ dice qualcosa riguardo $x$.
As esempio:
$$p(x): \text{The integer x is even.}$$
inoltre se una proposizione dice qualcosa riguardo a 2 o più variabili, va indicata in questo modo: $p(x,y,z,...)$

##### ATTENZIONE:  (Dio càn)
Non è sempre detto che una proposizione contenente una variabile sia aperta!!!!
Perchè, nonostante la proposizione:
$$q(x): \text{If an integer x is a multiple of 6, then x is even.}$$
contenga la variabile $x$, è comunque possibile dire che $q(x)$ sarà sempre vera, indipendentemente dal variare di $x$, mentre appunto la proposizione:
$$p(x): \text{The integer x is even.}$$
è dipendente da $x$ perchè a seconda del suo valore, la proposizione assume un valore di verità diverso (se $x = 2$, $p(x)$ è vera, se $x =3$, $p(x)$ è falsa).
Di p(x), non è possibile sapere il valore di verità finquando non si attribuisce un valore a $x$, ed è questo a rendere $p(x)$ una __proposizione aperta__.

---
## Connettivi logici
A partire da una proposizione, possiamo ottenerne altre attraverso i __connettivi logici__.

- Il più semplice tra questi è la _negazione_:
$$ \neg p \hspace{1cm}\textit{che leggiamo `non p'} $$
che nega l'affermazione della proposizione p.

- La _congiunzione logica_ (_AND logica_) è la seguente:
$$ p \land q \hspace{1cm} \textit{che leggiamo `p e q'}$$

- La _disgiunzione logica_ (_OR logica_) è la seguente:
$$ p \lor q \hspace{1cm} \textit{che leggiamo `p oppure q'}$$

<div id="line_spacing"></div>

### Implicazione logica
Esiste inoltre un connettivo detto _implicazione logica_:
$$ p \implies q \hspace{1cm} \textit{che leggiamo `se p allora q' o `solo se q allora p'}$$
dove $p$ è la premessa e $q$ e la conclusione.

C'è da premettere che esistono 2 tipi di implicazioni: quella __semantica__ e quella __formale__. La differenza tra le due è che nell'implicazione semantica si va a valutare la veridicità dell'implicazione in base al rapporto causa-effetto che collega la premessa alla conclusione. L'implicazione formale invece si limita solamente a giudicare la veridicità o la falsità di un implicazione in base ai valori logici di $p$ e $q$ ed è questo il tipo di implicazione usato nella matematica poichè è quello che riesce a mantenere la coerenza logica dell'implicazione.

Osservando la tabella di verità:

![[tabellaveritàimplicazionesingola.PNG]]

si osserva che $p \implies q$ è falsa solo se da un'implicazione vera si ha una conclusione falsa, mentre in tutti gli altri casi è vera. 
Ora, concentrandosi sui casi in cui l'implicazione è vera, si possono dedurre 2 proprietà:
- data un'implicazione vera: se l'antecedente $p$ è vera, allora la conseguente $q$ è necessariamente vera.
- data un'implicazione vera: se la conseguente $q$ è falsa allora l'antecedente $p$ è necessariamente falsa 
<div id="line_spacing"></div>
#### Condizione sufficiente e necessaria
Con queste due proprietà è ora possibile spiegare il concetto di condizione sufficiente e condizione necessaria. Partiamo dall'esempio:
$$p \implies q$$
Esistono due modi distinti per leggere questa espressione, ed entrambi mantengono la medesima valenza logica:
1. "se $p$, allora $q$" (_<span style="color: #F9E79F">if</span> p, <span style="color: #F9E79F">then</span> q_)
2. "solo se $q$ allora $p$" (_<span style="color: #F9E79F">only if</span> q, <span style="color: #F9E79F">then</span> p_)

Data l'implicazione $p \implies q$ vera a prescindere:
- Quando dico "se $p$, allora $q$", sto esprimendo l'implicazione in funzione della __ condizione sufficiente__, ovvero $p$. Il concetto è che, dicendo $p$, si sta automaticamente dicendo anche $q$ perchè $q$ è sottointesa in $p$ a livello logico. Ad esempio se dico: <center> Se è un cane, allora è un mammifero</center>per poter verificare che la proposizione "è un mammifero"  sia corretta è sufficiente dire che "è un cane", perchè nella parola "cane" si sta automaticamente sottointendendo tutto ciò che definisce un cane, tra cui il fatto che sia un mammifero.<div id="line_spacing"></div>
- Quando dico "solo se $q$, allora $p$", sto stavolta esprimendo l'implicazione in funzione della __ condizione necessaria__ $q$, ovvero la condizione senza il quale $p$ non può verificarsi, appunto necessaria.  
  Ad esempio dicendo: <center> Solo se è un mammifero, allora è un cane</center> non sto dicendo una contraddizione grazie alla parola "_solo_", che esprime la condizione necessaria per essere un cane, ovvero quella di essere un mammifero (l'attributo "mammifero" non riesce a definire un cane di per sé, bensì tutti gli animali mammiferi sulla terra, tra cui il cane).


Che quindi venga espressa la proposizione in funzione della condizione sufficiente o di quella necessaria, sempre della stessa proposizione $p \implies q$ si sta parlando.

Esempio:

Si voglione mettere in relazione le proposizioni "il cielo è nuvoloso" e "piove", in modo da capire quale è la premessa e quale è la conclusione dell'implicazione. Si costruisce quindi una tabella di verità verificando per ogni riga la coerenza logica delle due proposizioni:

||il cielo è nuvoloso | piove | $p \implies q$
-|-|-|-
1|V|V|V
2|V|F|V
3|F|V|F
4|F|F|V

La riga 1 e la 4 non hanno problemi perchè è coerente sia il fatto che sia nuvoloso e che piova, sia che non sia nuovoloso e che non piova, per questo entrambe sono vere nell'implicazione.
La riga 2 è coerente anch'essa poichè è plausibile che il cielo sia nuvoloso, ma non piova.
Il problema si trova nella riga 3, dove è impossbile che piova senza nuvole; per questo l'implicazione è falsa.

A questo punto se compariamo questa tabella alla tabella di verità generale dell'implicazione:

![[tabellaveritàimplicazionesingola.PNG]]

si può concludere che controintuitivamente la premessa $p$ è "piove" e la conclusione $q$ è "il cielo è nuvoloso", formando quindi la proposizione "_se <span style="color: #F9E79F">piove</span>, allora <span style="color: #F9E79F">il cielo è nuovoloso</span>_" perchè il fatto che piova è sufficiente per dire che ci sono delle nuvole e il fatto che sia nuvoloso è perlomeno necessario affinchè possa piovere.

La stessa tabella di verità si può ottenere con la proposizione $\neg p \lor q$. Pertanto, il connettivo logico $\implies$ può essere espresso in funzione dei connettivi primari $\neg$ e $\lor$.

### Doppia implicazione (o equivalenza logica)
$$p \iff q \hspace{1cm} \textrm{che leggiamo `se e solo se p, allora q'}$$
Questa espressione è composta da 2 parti unite dalla congiunzione "e", ovvero: _<span style="color: #F9E79F">se</span> _ e _<span style="color: #F9E79F">solo se</span>_ che come visto nell'implicazione, hanno due significati distinti: 
- dire __se__ p, __allora__ q significa dire $p \implies q$
- dire __solo se__ p, __allora__ q significa dire $q \implies p$

quindi dicendo "se e solo se" in lingua logica si intende  $(p \implies q) \land (q \implies p)$, ovvero $p \iff q$. Inoltre questo significa che $p$ diventa contemporaneamente _condizione sufficiente_ __E__ _condizione necessaria_ per $q$.

Esempio:
Se si prende come esempio l'implicazione logica:
<center>se vieni promosso, allora ti compro il motorino</center>

in questa proposizione sto assicurando $q$ (comprare il motorino) al verificarsi di $p$ (venire promosso), ma nulla mi vieta di comprare comunque il motorino anche se non si viene promossi (tabella di verità dell'implicazione). 
Mentre invece:
<center>se e solo se vieni promosso, allora ti compro il motorino</center>

significa che sto vincolando $q$ alla proposizione $p$, poiche $p$ è sia la condizione necessaria sia quella sufficiente, per far sì che si verifichi $q$.

La doppia implicazione logica è vera se $p$ e $q$ hanno gli stessi valori di verità, ed è falsa se $p$ e $q$ hanno valori di verità diversi.

![[tabellaveritàimplicazionedoppia.PNG]]
La proposizione $p \iff q$ è la congiunzione delle proposizioni $p \implies q$ e $q \implies p$, vale a dire che le proposizioni $p \iff q$ e $(p \implies q)\land(q \implies p)$ hanno gli stessi valori di verità; dunque, il connettivo $\iff$ è esprimibile tramite i conntettivi primari $\land$, $\neg$ e $\lor$

___

## Quantificatori
I quantificatori sono:
- "$\boldsymbol{\forall}$", che si legge "__per ogni__ elemento..."
- "$\boldsymbol{\exists}$", che si legge "esiste __almeno__ un elemento..."
 - "$\boldsymbol{\exists}!$", che si legge "esiste __solo__ un elemento..."
- "$\boldsymbol{\nexists}$", che si legge "non esiste alcun elemento..."

Esempi :
- La proposizione "<span style="color: #F9E79F">$\text{For every} \; n \in Z, 2n \; \text{is even}$</span>" può essere riscritta nei modi seguenti:
$$\forall n \in Z, 2n \; \text{is even}\hspace{.5cm}\text{or}\hspace{.5cm} \forall n \in Z, E(2n)$$

- La proposizione "<span style="color: #F9E79F">$\text{There exists a subset X of N for which} \; |X| = 5$</span>" può essere riscritta come:$$∃ X,(X ⊆ N)∧(|X| = 5)\hspace{.5cm} \text{or} \hspace{.5cm} ∃ X ⊆ N,|X| = 5\hspace{.5cm} \text{or} \hspace{.5cm}∃ X ∈ P(N),|X| = 5$$

in particolare il quantificatore $\forall$ è detto "quantificatore universale", mentre $\exists$ è detto "quantificatore esistenziale".

I quantificatori sono quindi dei simboli che aiutano a definire una "quantita", qualora facciano riferimento a delle proposizioni aperte del tipo $p(x)$, (che assumono un valore di verità dipendentemente da una variabile), e questa caratterisca è fondamentale, perchè ha il potere di trasformare una proposizione aperta in una proposizione normale, attribuendole un valore di verità senza alterarne il contenuto. 
Ad esempio si prende in considerazion la proposizione:

$$p(x):\text{(x is even) ⇒ (x is a multiple of 6)}$$

che è una proposizione aperta, dal momento che è vera per alcuni valori di $x$ (-6, 12, 18, ...) ed è falsa per tutti gli altri (2, 4, ...). Ma quando si va ad aggiungere un quantificatore all'inizio della premessa, come di seguito:

$$p(x):\forall x \in \Bbb{Z},\text{(x is even) ⇒ (x is a multiple of 6)}$$

si sta andando a specificare che __per ogni__ $x$ che è numero pari, allora $x$ deve essere multiplo di 6, e non è questo il caso, perchè alcuni lo sono ed altri no, quindi $p(x)$, non vale __per ogni__ $x$, quindi $p(x)$ (con il quantificatore $\forall$) diventa falsa. __Non è più una proposizione aperta__.
Similarmente questa considerazione è applicabile anche al quantificatore $\exists$:
$$p(x):\exists x \in \Bbb{Z},\text{(x is even) ⇒ (x is a multiple of 6)}$$
solo che sta volta $p(x)$ sarà vera, perchè esiste __almeno una__ $x$ pari, multiplo di 6.
<div id="line_spacing"></div>

E' utile soffermarsi infine sulla negazione di una proposizione quantificata.
Prendendo $p(x)$ come esempio:

$$p(x):\text{(x is even) ⇒ (x is a multiple of 6)}$$

so che se scrivo "$\forall x \in \Bbb{Z}, p(x)$", sto dicendo "ogni numero intero pari è multiplo di 6", che è falso. Quindi logicamente l'affermazione "$\neg(\forall x \in \Bbb{Z}, p(x))$", deve essere vera, ma __ATTENZIONE__: "$\neg(\forall x \in \Bbb{Z}, p(x))$", non vuol dire che "__non esistono__ numeri pari multipli di 6" (che esistono), bensi vuole dire "__esiste almeno__ un numero pari  __non__ multiplo di 6" che si può riscrivere come: "$\exists x \in \Bbb{Z}, \neg p(x)$". 
Quindi come regola generale vale che:

<div align="center"><span class="math display">\neg(\forall x \in \Bbb{Z}, p(x)) \iff \exists x \in \Bbb{Z}, \neg p(x)</span></div>

e viceversa:

<div align="center">
<span class="math display">\neg(\exists x \in \Bbb{Z}, p(x)) \iff \forall x \in \Bbb{Z}, \neg p(x)</span>
 </div>


___
## Regole di dimostrazione
La proposizione $p \implies q$ può essere espressa in varie altre forme logicamente equivalenti a questa. Tali forme rappresentano delle __regole di dimostrazione__ utili a riottenere l'implicazione originaria per la dimostrazione di [[teorema|teoremi]].

_roba correlata_ ($\rightarrow$ [[leggi di DeMorgan]])

Di dimostrazioni ne esistono 2 categorie: quella __diretta__ e quelle __indirette__.

### Dimostrazione diretta
La dimostrazione di una proposizione $p \implies q$ tramite dimostrazione diretta, è un modo semplice e lineare di verificare il valore di vertà di una proposizione tramite una combinazione di fatti già verificati, come [[assioma|assiomi]], [[teorema|teoremi]], [[lemma|lemmi]] senza fare nessuna assunzione iniziale, o in altre parole, andando direttamente al sodo, supponendo vera $p$.

<div id="line_spacing"></div>

Quelle __indirette__ invece sono:

### Contronominale
Data una qualsiasi implicazione $p \implies q$ esiste un' implicazione logicamente identica $\neg q \implies \neg p$ detta _contronominale_ che detta in formule si scrive in questo modo:

<div align="center"><span class="math display">(p \implies q) \iff (\neg q \implies \neg p)</span></div>

La dimostrazione è semplice:
Basta guardare le tabelle di verità di "$p \implies q$" e di "$\neg q \implies \neg p$" ed è possibile verificare subito che le due proposizioni sono logicamente identiche:

![[contrapositiveTruthTable.PNG]]

quindi dal momento che $p \implies q$, è logicamente equivalente a $\neg q \implies \neg p$, segue che per dimostrare che $p \implies q$ è vera, è sufficiente dimostrare che $\neg q \implies \neg p$ sia a sua volta vera. Basta quindi assumere $\neg q$ vera (o in altre parole supporre $q$ falsa) e procedere con la dimostrazione diretta.

Ad esempio nella proposizione:
<center>Se un numero naturale è dispari, allora non è divisibile per 10</center>

$p$ è _"un numero dispari"_ e $q$ è _"non è divisibile per 10"_.
Si negano $q$ e $p$ e si prova dimostrare vera la proposizione $\neg q \implies \neg p$:
<center>Se un numero naturale è divisibile per 10, allora è pari</center>

proseguendo con la dimostrazione diretta, è facile provare che un qualsiasi numero naturale diviso per 10 è pari, perchè 10 stesso è divisibile per 2, quindi un numero naturale divisibile per 10 è anche divisibile per 2. Da questo segue che se un numero naturale è divisibile per 10 allora è pari, poichè qualsiasi numero divisibile per 2 è pari per definizione.

### Dimostrazione per assurdo
L'idea di base è assumere che l'affermazione che vogliamo dimostrare sia falsa, e poi mostrare che questa ipotesi porta ad una conclusione contraddittoria. Si è quindi portati a concludere che si ha sbagliato a presumere che l'affermazione iniziale fosse falsa, quindi l'affermazione deve essere vera.

In formule logiche:

<div align="center"><span class="math display">(p \implies q) \iff (p \land \neg q \implies r \land \neg r)</span></div>

<div id="line_spacing"></div>

Si può iniziare a definire una procedura attraverso un esempio:
Si considera una proposizione $P$ del tipo "$p \implies q$" come ad esempio:
<center>Se considero il numero <span class="math display">\sqrt{2}</span>, allora è irrazionale</center>

Partendo dal presupposto che non si conosce il valore di verità di $P$, il primo passo che devo fare per verificare la sua veridicità è negarla ($\neg P$). E lo si fa mantenendo vera la premessa e negando la conclusione in questo modo:

<center>Se considero il numero <span class="math display">\sqrt{2}</span>, allora è razionale</center>

e da qua si procede con la dimostrazione diretta, fino a quando non si otterrà uno statement conclusivo $r$ che si dimostra contraddittorio. 
Se quindi $\sqrt{2}$ è razionale allora:
$$\sqrt{2} = \frac{a}{b} \; \textrm{con }a,b \in Z$$

Se questa frazione è completamente ridotta è possibile dire che $a$ e $b$ non possono essere entrambi pari (altrimenti la frazione sarebbe ulteriormente semplificabile). 
Se si eleva al quadrato da entrambi i lati  si ottiene:
$$ a^2  = 2b^2$$
e da questo segue che $a^2$ è pari (perchè è $2 \; \times$ un numero qualsiasi). Inoltre, attraverso un teorema già dimostrato, il fatto che $a^2$ sia pari implica che anche $a$ è pari, quindi si può dire che $a = 2c$. Quindi secondo l'affermazione di prima $b$ deve essere necessariamente dispari (questa è la proposizione $r$ che verrà usata per contraddire la conclusione della dimostrazione). 
Detto questo si sostituisce $a$ con $2c$ nell'equazione e si ottiene:
$$\displaylines{(2c)^2 = 2b^2 \\ 4c^2 = 2b^2 \\ b^2 = 2c^2}$$
che dimostra che $b^2$ è pari, e di conseguenza $b$ è pari, portando ad una contradizione del tipo $r \land \neg r$ dove $r$ può essere sia "$b$ è pari", sia "$b$ non è pari", questo non ha inportanza perchè tanto alla fine la proposizione $r \land \neg r$ sarà sempre negativa.
Questa dimostrazione ha portato a concludere che se si suppone vera $\neg P : p \implies \neg q$, allora è automaticamente implicita l'esistenza della conclusione $r \land \neg r$ (che si traduce come "$b$ è sia pari, sia dispari"), che è sempre falsa, riottenendo così la formulazione logica di inizio paragrafo ==$p \land \neg q \implies r \land \neg r$==.

Quindi alla fine, se si è riusciti a dimostrare che $p \land \neg q \implies r \land \neg r$, segue che la proposizione originale $P: p \implies q$ __deve essere vera__.

### Dimostrazione per induzione
La dimostrazione per induzione è un tipo di dimostrazione che funziona nei casi in cui si vuole dimostrare la validità assoluta di una certa congettura/tesi, e la sua definizione è la seguente:

<div align="center">
Sia <span class="math display">n_0 \ge 0</span> un intero e sia <span class="math display">S(n)</span> un predicato definito per ogni intero <span class="math display">n \gt n_0</span>,
<br>e supposto che valgono le seguenti condizioni:<br>
i.) <span class="math display">S(n_0)</span> è vero<br>
ii.) per ogni <span class="math display">n \gt n_0</span>, se <span class="math display">S(n)</span> è vero, allora <span class="math display">S(n+1)</span> è vero<br><br>
allora, <span class="math display">S(n)</span> è vero per ogni <span class="math display">n \gt n_0</span>

</div>

Esempio:
$$\text{Conjecture: The sum of the first n odd natural numbers equals}\;n^2.$$
che si può tradurre graficamente nel seguente modo:

![[inductionproofExaple.PNG]]

questa congettura (che per comodità verrà chiama "$S$") prevede che preso un numero $n$, $n^2$ sia ottenibile tramite la somma di tutti i primi numeri dispari fino a $(2n-1)$, e dato che $S$ deve essere valida per qualsiasi numero naturale $n$, è possibile utilizzare un pedice tipo $S_1$, $S_2$, $S_3$, ... per indicare il numero preso in considerazione è 1, 2 o 3, mentre per la regola generale basta scrivere $S_n$ esattamente come qui di seguito:
- $S_1 = 1 + (1^2 - 1) = 1$
- $S_n = 1+3+5+7+\dots+(2n-1) = n^2$

Per proseguire con la dimostrazione per induzione bisogna iniziare a dimostrare un caso in cui, dato un numero $n_0$, sia vera la regola $S(n_0)$ e per comodità si sceglie ==$n_0 = 1$== dato che è già stato dimostrato vero attraverso dimostrazione diretta, per l'appunto:
$$S_1 = 1 + (1^2 - 1) = 1$$

Adesso serve dimostrare la seconda condizione indicata dal teorema: "per ogni $n \gt n_0$, se $S(n)$ è vero, allora $S(n+1)$ è vero", e per dimostrarla è utile soffermarsi sulla parte del "per ogni", che implica il fatto che non è possibile andare a dimostrare caso per caso ogni numero intero maggiore di $n_0$. Sarà quindi necessario l'uso di variabili, quindi scritta in linguaggio logico, la seconda condizione diventa $\forall n \gt 1, \;  S_n \implies S_{n+1}$ che significa che per ogni $n \gt 1$, bisogna dimostrare che se $1+3+5+7+\dots+(2n-1) = n^2 \implies1+3$$+5+7+\dots+(2(n+1)-1) = (n+1)^2$.

La dimostrazione è la seguente:
$$
\begin{array}{rcl}
1+3+5+7+\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot+(2(n+1)-1)&=\\
1+3+5+7+\dots+(2n-1)+(2(n+1)-1)&=\\
(1+3+5+7+\dots+(2n-1))+(2(n+1)-1&=\\
n^2+(2(n+1)-1)&=&n^2 + 2n +1\\
&=&(n+1)^2
\end{array}
$$

Quindi $1+3+5+7+\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot\cdot+(2(n+1)-1) = (n+1)^2$. Questo prova che $S_n \implies S_{n+1}$.

Si può quindi concludere per induzione che $1+3+5+7+\dots+(2n-1) = n^2$ per ogni $n \in \Bbb{N}$. 


---
Tags:
#prerequisiti
#logica

Corso:
#analisi1
