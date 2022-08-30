---
tags:
aliases:
cssclass: funzioneinvertibile
---
_Questa nota fa riferimento a $\rightarrow$ [[funzione|Funzione]]_
# Funzione invertibile
###### Definizione:
Una funzione iniettiva $f$ può essere inverita nella funzione $f^{-1}$. Il processo di inversione di $f$ è semplice: in poche parole la funzione $f^{-1}$ usa come dominio, l'*immagine* di $f$, quindi:
$$\text{dom }f^{-1} = \text{im }f$$
risulterà quindi che il [[funzione#Grafico di una funzione|grafico]] della funzione invertita sarà composto da coppie ordinate con le  componenti "invertite" del tipo $(y,x) \in \{\text{im} f \times X\}$, invece che della classica funzione che mappa gli elementi da $X$ a $Y$ ($f:X \mapsto Y$).
Il grafico di $f^{-1}$ risulta quindi essere:

<span class="importante"> $
\begin{array}{rcl}
\Gamma(f^{-1}) &= & \{\bigl(y,f^{-1}(y)\bigl) \, \in Y \times X: y\in \text{dom }f^{-1}\}
\\
&=&\{\bigl(f(x),x\bigl) \, \in Y \times X: x\in \text{dom }f\}.
\end{array}
$ </span>

e il risultato sul piano cartesiano è la stessa funzione ma specchiata lungo la retta $y=x$ sul primo e terzo quadrante.

<span id="bigText" class="text_divisor">Esempi: 

Si prende come esempio la funzione $f(x)= 2x$ che è biiettiva.
Il suo grafico viene definito nel seguente modo: ==$\Gamma(f) = \{(x,2x)\in X \times Y:x \in \text{dom }f\}$== che graficamente corrisponde a

```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=2x
```
Per trovare la funzione $f^{-1}$ è sufficiente invertire $x$ con $ $ e svolgere i calcoli per riottenere la funzione espressa per $y$ nel seguente modo:
$$
\begin{array}{rcl}
y = 2x &\rightarrow& x = 2y
\\
& \rightarrow& y = \displaystyle\frac{x}{2}
\end{array}
$$
e la nuova funzione invertita avrà come grafico $\Gamma(f^{-1})=\{(x, \frac{x}{2})\in Y \times X: x \in \text{dom }f^{-1}\}$ che graficamente corrisponde a:


```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)= x/2
```

<span id="bigText" class="text_divisor">Note:

Il concetto di [[funzione iniettiva|iniettività]], è necessario affinchè una funzione possa definirsi *invertibile*, perchè se si provasse ad invertire una funzione non iniettiva, il risultato non sarebbe più una funzione in quanto esistebbe almeno una $x$ il quale valore corrisponderebbe a 2 o più immagini $f(x)_1$ e $f(x)_2$ in contemporanea.

![[nonèunafunzione.png]]

***

Tags:  
#funzione 

Corso:  
#analisi1