# Esercizi con le index cards

## Indice <!-- omit in toc -->

- [Introduzione](#Introduzione)
- [Gli esercizi](#Gli esercizi)
- [Allenarsi a programmare: Modellazione e Sintassi](#Allenarsi a programmare: Modellazione e Sintassi)
- [Obiettivi degli esercizi](#Obiettivi degli esercizi)
- [Materiali](#Materiali)
- [Regole](#Regole)
  - [Come mai queste regole](#Come mai queste regole)

## Introduzione

Uno dei motivi per cui imparare a programmare è difficile è perché tutto sembra sconosciuto. Per un principiante, il codice sembra un incantesimo magico. "In che modo questa pila di `if`, `for` e `function` fa fare al computer quello che voglio?"

Quando impari la tua prima lingua straniera, hai almeno una lingua madre che puoi usare come riferimento. Quando impari il tuo primo linguaggio di programmazione, cosa potresti usare come riferimento? Questi esercizi hanno lo scopo di darti quel riferimento.

Ti daremo alcuni problemi molto semplici e ti chiederemo di risolverli utilizzando materiali fisici di uso quotidiano come schede, post-it e penne. Questi problemi chiederanno cose come "Trova il numero più grande in questo elenco di numeri" o "Dimmi quanti numeri in questo elenco di numeri sono maggiori di 10".

I problemi sono pensati per essere semplici in modo che tu possa esercitarti nella parte più difficile e meno familiare: descrivere passo dopo passo il processo che hai usato per risolvere ogni problema. Dopo aver confrontato la tua descrizione con il codice che implementa lo stesso processo, scoprirai che il codice sembra meno un incantesimo magico e più una frase in una lingua straniera.

## Gli esercizi

Prima di tuffarti negli esercizi leggi anche le prossime sezioni.

1. [Find the largest number](exercises/find-largest-number)
1. [Find the smallest number](exercises/find-smallest-number)
1. [Is in list](exercises/is-in-list)
1. [Add numbers](exercises/add-numbers)
1. [Find max even number](exercises/find-largest-even-number)
1. [Find max odd number](exercises/find-largest-odd-number)
1. [Find second-largest number](exercises/find-second-largest-number)
1. [Count specific number](exercises/count-number)
1. [Count positive numbers](exercises/count-positive-numbers)
1. [Count negative numbers](exercises/count-negative-numbers)
1. [Count larger than 10](exercises/count-larger-than-ten)
1. [Count smaller than 10](exercises/count-smaller-than-ten)
1. [Count larger than X](exercises/count-larger-than)
1. [Count smaller than Y](exercises/count-smaller-than)

## Allenarsi a programmare: Modellazione e Sintassi

> 🚨**Concetti cardine**🚨
>
> I principianti si concentrano troppo sulla sintassi e non abbastanza sulla modellazione. Ciò è comprensibile poiché la sintassi è nuova, estranea e peculiare per la programmazione. La maggior parte dei curriculum rinforzano questo atteggiamento organizzando tutto in base alla sintassi.

Che cos'è il "modello"? Ricorda, i computer sono stupidi ma veloci. Possono eseguire miliardi di operazioni al secondo, ma quelle operazioni sono così specifiche e così meccaniche che non penseresti quasi mai di doverle spiegare quando parli con un altro essere umano.

Questo non significa che i computer siano limitati. Possiamo comporre infiniti brani con un numero finito di note e possiamo comporre infiniti programmi con un numero finito di operazioni.

La programmazione è l'arte/scienza di far sì che i computer risolvano i problemi per nostro conto. Le due abilità fondamentali sono:

1. **Modellazione**

   Comprendere un problema così a fondo da poterlo risolvere in termini di quelle operazioni super-specifiche che un computer può eseguire. La comprensione che ne abbiamo è una sorta di immagine del problema nella nostra mente, chiamata un [modello mentale][wiki-mental-model].

1. **Codifica + Sintassi**

   Tradurre il tuo modello mentale del problema in codice che un computer può eseguire

Se esiste un "teorema fondamentale dell'imparare a programmare" è questo:

- Se hai un modello mentale chiaro e sufficiente conoscenza della sintassi, saprai esattamente quale codice scrivere.

Equivalentemente:

- Se non sai che codice scrivere allora il tuo modello mentale non è così chiaro come credi o non hai sufficiente conoscenza della sintassi (o probabilmente una combinazione di entrambe le cose).

Quindi, ricorda: i principianti si concentrano troppo sulla sintassi e non abbastanza sulla modellazione. Ciò è comprensibile poiché la sintassi è nuova, estranea e peculiare per la programmazione. La maggior parte dei curriculum rinforzano questo atteggiamento organizzando tutto in base alla sintassi.

## Obiettivi degli esercizi

Introdurre un piccolo pezzo di sintassi dopo l'altro rende difficile avere una visione completa di ciò che fa un programmatore. "Come si collega questo a qualcos'altro? Come farò a ricordare tutto questo?", potresti chiederti.

Questi esercizi sono stati pensati per farti giocare l'intero gioco senza farti travolgere dalla sintassi. Ti faremo risolvere i problemi come farebbe un computer e poi ti presenteremo la sintassi effettiva che il computer richiede.

Nello specifico, questi esercizi sono progettati per:

1. Presentarti i ~5 blocchi che fanno da fondamenta a qualsiasi programma che scriverai
1. Farti modellare e risolvere problemi che sai già come risolvere utilizzando quei blocchi.
1. Introdurre la sintassi di Javascript traducendo le tue soluzioni in codice funzionante

## Materiali

Ogni esercizio richiede i seguenti materiali:

- Un mazzo di ~20 [carte][wiki-index-cards] con numeri casuali compresi tra -100 e 100 stampati su un lato
- [Post-it][wiki-sticky-notes] o piccoli pezzi di carta da scarabocchiare
- Una penna o una matita

Non scriveremo neanche una riga di codice.

## Regole

Hai un pacchetto di post-it e una penna. All'inizio dell'esercizio, tu...

1. riceverai un mazzo di carte con dei numeri stampati su un lato
1. ti verrà posta una domanda riguardo ai numeri nel mazzo

Usando i post-it come foglio per gli appunti (and _solo_ i post-it) il tuo compito è di rispondere alla domanda, scrivere la risposta su un post-it e restituirlo.

Ci sono tre regole:

1. Puoi girare e guardare una sola carta per volta.

   Non si può sparpagliarle sul pavimento e, per esempio, fare affidamento sil tuo colpo d'occhio per rispondere alla domanda.

1. Ogni post-it può avere scritto _solo_ una parola o numero.
1. Per scrivere su un un post-it puoi o
   - scrivere una nuova parola o numero su un nuovo post-it
   - sostituire una parola o un numero su un post-it già scritto

### Come mai queste regole

Queste regole sono studiate per impedirti di usare delle capacità umane che un computer semplicemente non ha.

Per esempio, se ti viene consegnato un mazzo di carte con i numeri e ti viene chiesto di trovare il numero più grande, potresti sparpagliarle sul pavimento con i numeri rivolti in su. Poi daresti un'occhiata alle carte e prenderesti il numero più grande in base ad euristiche come

- Ignorare i numeri negativi
- Cercare numeri con più cifre
- Cercare numeri che iniziano per 9 o 8

Usando queste euristiche, potresti trovare un probabile candidato per "il numero più grande" e poi verificare brevemente controllando tutte le altre carte per vedere se ce ne è uno maggiore.

Ma questo è troppo intelligente per un computer!

Quindi, cominciamo a fare pratica con [gli esercizi](#Gli esercizi).

[wiki-mental-model]: https://en.wikipedia.org/wiki/Mental_model
[wiki-index-cards]: https://en.wikipedia.org/wiki/Index_card
[wiki-sticky-notes]: https://en.wikipedia.org/wiki/Post-it_Note
