---
tags:
aliases:
cssclass: numericomplessi
---
# Numeri complessi

I numeri complesi sono considerabili come un' estensione ulteriore dell'insieme $\Bbb{R}$, poichè un qualsiasi numero complesso $z$ è composto da una parte reale $x=\text{Re }z$ e una parte immaginaria $y=\text{Im }z$, andando così a definire un numero immaginario come una coppia del tipo $z=(x,y)$. 
## Forma cartesiana
Infatti i numeri complessi sono definiti sul piano cartesiano, appunto come una coppia di coordinate, composto dal prodotto $\Bbb{R} \times \Bbb{I}$, dove $\Bbb{I}$ è l'insieme dei numeri immaginari che funge da ordinata.
### Operazioni somma e prodotto
Nella forma **cartesiana** del tipo $z=(x,y)$, il quale significato geometrico è assimilabile ad un punto sul piano, è possibile svolgere delle operazioni come somma e prodotto in modo simile alla somma e prodotto tra vettori. Tali operazioni definite in $\Bbb{C}$ sono quindi:

<span style="font-size: 80%">**Somma:**</span> <span class="center"> $z_1+z_2$ $=(x_1,y_1)+(x_2,y_2)=(x_1+x_2,\ y_1+y_2)$ </span>

<span style="font-size: 80%">**Prodotto:**</span> <span class="center"> $z_1\cdot z_2$ $=(x_1,y_1)+(x_2,y_2)=(x_1\cdot x_2 - y_1\cdot y_2,\ x_1 \cdot y_2 + x_2 \cdot y_1)$ </span>


![[somma numeri complessi.PNG]]
 ed è utile ricordare dei casi "particolari" di utilizzo di queste operazioni come ad esempio: 
 I numeri complessi $z_1=(x_1,0)$ e $z_2=(x_2,0)$, sprovvisti di parte immaginaria, si trovano esattamente sull'asse reale del piano e sono quindi considerabili numeri reali. Questo fatto permette di poter utilizzare tutte le operazioni e proprietà già definite dell'insieme $\Bbb{R}$, come le operazioni "$+$" e "$\cdot$", che si dicono [[proprietà di chiusura|chiuse]] rispetto ad $\Bbb{R}$ (proprietà della quale tutti i numeri complessi che non si trovano sull'asse reale non godono), quindi $z_1 + z_2=(x_1+x_2,0)$ e $z_1 \cdot z_2=(x_1\cdot x_2,0)$. Lo stesso però non vale per i numeri con parte immaginaria poichè moltiplicando l'unità immaginaria $i = (0,1)$ per se stesso ottengo il numero reale $-1$, o scritto in forma cartesiana $(-1,0)$, pertanto su tali numeri complessi non è possibile operare con le operazioni comuni.

## Forma algebrica
La forma algebrica di un numero complesso è la forma in cui il numero è esplicitato attraverso l'uso delle varibili $z$, $x$ e $y$ legate algebricamente (attraverso delle operazioni) nella forma ==$z =x+iy$==.
Tale forma viene derivata dalla forma cartesiana attraverso questi passaggi:
<span class="importante"> $
\begin{array}{rcl}
(x,y) &=& (x,0)&+&(0,y)&&
\\
&=&(x,0)&+&(0,1)&\cdot&(y,0)
\\
z&=&x&+&i&\cdot&y
\end{array}$

### Operazioni somma e prodotto
 le operazioni di somma e prodotto tra numeri complessi sono:
 
 <span style="font-size: 80%">**Somma:**</span> <span class="center"> $z_1+z_2$ $=(x_1+iy_1)+(x_2+iy_2)=(x_1+x_2)+i(y_1+y_2)$ </span>

<span style="font-size: 80%">**Prodotto:**</span> <span class="center"> $z_1\cdot z_2$ $=(x_1+iy_1)\cdot(x_2+iy_2)=(x_1x_2 - y_1y_2)+i(x_1  y_2 + x_2 y_1)$ </span>

## Modulo di un numero complesso

![[Modulo numero complesso.png]]


***

Tags:  
#numericomplessi

Corso:  
#analisi1 


