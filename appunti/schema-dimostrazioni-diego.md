# dimostrazione

## introduzione

$$
\forall
$$

Per dimostrare $\forall . P (x)$ (per ogni x vale P (x)):

*“sia x (un insieme) fissato; . . . ”*

(i “. . .” sono una prova di P (x ))

$$
\implies
$$

Per dimostrare $P \implies Q$:

*“Assumo P (H ). . . . ”*

(“H ”) è il nome dell’ipotesi;

i “. . .” sono una prova di Q)

$$
\iff
$$

Per dimostrare $P \iff Q$ si dimostra sia $P \implies Q$ che $Q \implies P$.

$$
\land
$$

Per dimostrare $P \wedge Q$ (P e Q) si dimostrano sia P che Q.

$$
\lor
$$

Per dimostrare $P \vee Q$ (P o Q) basta dimostrare P oppure Q

dichiarandolo:

*“dimostro P ”* oppure *“dimostro Q"*

$$
\exists
$$

Per dimostrare $\exists x . P(x)$ (esiste un x per cui vale P (x )):

“scelgo E e dimostro P (E ) ; . . . ”

(i “. . .” sono una prova di P (E ))

E può essere un’espressione qualsiasi (es. $B \cap C$).


## eliminazione

$$
\forall
$$

Da un’ipotesi o un risultato intermedio $\forall x . P (x )$ potete
concludere che P valga per ciò che volete.

$$
\implies
$$

Da un’ipotesi o un risultato intermedio $P \implies Q$ e da un’ipotesi o
un risultato intermedio P potete concludere che Q vale.

(variante)

Da un’ipotesi o un risultato intermedio $P \implies Q$ di nome H , se
volete concludere Q, potete procedere dicendo

*“per H , per dimostare Q mi posso ridurre a dimostrare P ”*

$$
\iff
$$

L’ipotesi $P \iff Q$ può essere usata sia come un’ipotesi 
$P \implies Q$, che come un’ipotesi $Q \implies P$.

$$
Assurdo
$$

Se ho dimostrato l’assurdo posso concludere qualunque cosa.

$$
\land
$$

Un’ipotesi o un risultato intermedio $P \wedge Q$ può essere usato sia
come P che come Q. In alternativa, invece di concludere o
assumere $P \wedge Q$ (H ), si può direttamente concludere o
assumere P (H1) e Q (H2).

$$
\lor
$$

Data un’ipotesi o un risultato intermedio $P \vee Q$, si può
proseguire nella dimostrazione per casi, una volta assumendo
che P valga e una volta che Q valga:

*“procedo per casi:*

*caso in cui valga P (H ): . . .*

*caso in cui valga Q (H ): . . . "*

$$
\exists
$$

Da un’ipotesi o un risultato intermedio $\exists x .P (x )$ potete
procedere nella prova dicendo

“sia x t.c. P (x ) (H )”

x deve essere una variabile non in uso in nessuna ipotesi o
nella conclusione

## altro e abbreviazioni

**Per ogni tale che**

“sia x tale che P (x ). . . . ”

abbrevia

“sia x (un insieme) fissato; assumo P (x ); . . . ”

per dimostrare $\forall x .P (x ) \implies Q(x )$


**Da H1, . . . , Hn**

“da H1, . . . , Hn ho P (H )”

dove ogni Hi ha la forma $\forall ~x .Qi1(~x ) \implies \dots \implies Qini (~x )$ abbrevia
l’applicazione di un numero arbitrario di regole di eliminazione
del per ogni e dell’implicazione applicate a partire dalle ipotesi
H1, . . . , Hn e tali per cui la conclusione finale sia P . Il nome H
verrà poi usato quando P è una conclusione intermedia.

**Quindi**

“quindi” e sinonimi sono un modo per fare riferimento all’ultima
ipotesi/risultato intermedio, magari omettendone del tutto il
nome nel testo

**Ovvio**

il lettore è in grado da se di ricostruire la prova, non indica che la prova è intuitiva

**Espansione di definizioni**
“P , ovvero Q” usato per espandere da qualche parte in P una
definizione, ottenendo la frase Q
Esempio: $A \subseteq B$ ovvero $\forall X .(X \in A \implies X \in B)$.

**Esplicitazione della conclusione**

Talvolta conviene esplicitare la conclusione corrente (cosa
resta da dimostrare) attraverso *“dobbiamo dimostrare P ”.*

**Negazione**

Non P è un’abbreviazione per $P \implies$ assurdo.
Pertanto per dimostrare non P si assume che P valga e si
dimostra l’assurdo.
Inoltre, data un’ipotesi (o risultato intermedio) non P e un’altra
ipotesi o risultato intermedio P si conclude l’assurdo.

