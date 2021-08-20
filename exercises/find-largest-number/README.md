# Trova il numero più grande

Data una lista di numeri, inventiamo un processo per trovare il numero più grande.

## Contenuti <!-- omit in toc -->

- [Istruzioni](#istruzioni)
- [Obiettivo: tre descrizioni](#obiettivo:-tre-descrizioni)
- [Prima descrizione: scrivila tu](#prima-descrizione:-scrivila-tu)
- [Seconda descrizione: pseudocodice](#seconda-descrizione:-pseudocodice)
- [Terza descrizione: codice vero e proprio](#terza-descrizione:-codice-vero-e-proprio)

## Istruzioni

Immagina di avere una penna/matita e un blocco di post-it. Unə amicə ti consegna queste cose:

- Un mazzo di 20 carte con dei numeri casuali stampati su un lato, tutte a faccia in giù

Questə amicə poi ti chiede di trovare il numero più grande nel mazzo e di consegnarli un post-it con la risposta scritta sopra.

Hai due compiti:

1. Inventare un processo che produce il risultato che richiede lə tuə amicə
1. Scrivere una descrizione dettagliata del tuo processo in modo che un'altra persona possa usarla per rimetter in atto il tuo processo passo per passo

**Non dimenticare!** Qualinque sia il processo che inventi, deve seguire [le regole][regole]. Le regole sono state pensate in modo dafarti ragionare come una macchina invece che come un essere umano. Istruzioni come "Trova il numero più grande" o "Dimmi se il numero 0 è uno di quelli contenuti nelle carte" vanno bene per una persona, ma non descrivono i passi che hai compiuto per produrre la tua risposta.

## Obiettivo: tre descrizioni

Inventare il pocesso che produce la risposta alla domanda del tuo amico è solo metà dell'opera. L'altra metà è scrivere il codice che dica a un computer di portare a termine quel processo al posto tuo.

Quando [Neo di Matrix](https://www.youtube.com/watch?v=3vAnuBtyEYE) guarda il codice, non vede un miscuglio di simboli, lui vede quello che il codice descrive: una macchina che somma numeri, suona canzoni, mostra il meteo attuale, o qualsiasi altra cosa. Noi vogliamo che tu diventi come Neo il più velocemente possibile.

Per farlo, abbiamo bisogno che mostri come si presenta il processo che hai inventato quando viene descritto con codice vero e proprio. Ci arriviamo passo per passo usando tre diversi tipi di descrizione:

1. Una descrizione che scrivi a modo tuo, usando qualunque sintassi ti risulta naturale
1. Un'altra descrizione scritta in pseudocodice, un formato vicino al linguaggio umano strutturato in modo simile ad un vero programma, senza impantanarsi nella sintassi di uno specifico linguaggio di programmazione
1. Alcuni programmi veri e propri scritti in diversi linguaggi di programmazione

Dopo averlo fatto per 10-15 volte, sarai in grado di separare le parti di codice che corrispondono a qualcosa che comprendi da quelle che non lo fanno. Sarai in grado di cercare dei tutorial riguardo quelle parti che non comprendi. Quei tutorial non ti sembreranno un insieme di fatti arbitrari da memorizzare, ma al contrario, ti aiuteranno a scrivere programmi migliori e più descrittivi.

## Prima descrizione: scrivila tu

In italiano, scrivi una descrizione chiara, passo per passo, del processo che hai appena inventato. Cosa significa "chiara" e "passo per passo"? Per aiutarti a scrivere una buona descrizione, tieni a mente il seguente scenario. O, meglio ancora, provalo con un amicə!

Immagina di andare da unə amicə che non ha mai affrontato prima questo problema. Puoi darlə un blocco di post-it, una penna, e la tua descrizione del processo. Infine, puoi darlə un mazzo di carte numerate e chiederlə di portare a termine il processo descritto.

Dovresti sentirti sicurə che lə tuə amicə possa portare a termine il processo con poche o nessuna spiegazione. Non dovrebbe neanche avere bisogno di "sapere" che l'obiettivo sia di trovare il numero più grande.

Come minimo, lə tuə amicə dovrebbe avere chiare le seguenti istruzioni:

- Cosa fare prima di iniziare a voltare le carte (se necessario)
- Cosa scrivere sui post-it e quando
- Quando voltare una carta
- Tra un giro di carta e l'altro, cosa fare con le informazioni che vede
- Quando smettere di voltare
- Cosa dare dopo avere terminato di voltare tutte le carte (se necessario)
- Quando restituire il post-it contentente la risposta

## Seconda descrizione: pseudocodice

Abbiamo descritto un processo per risolvere questo problema in pseudocodice qui: [pseudocode.md](pseudocode.md).

Ricorda, lo pseudocodice è una descrizione informale, di alto livello, di un programma informatico. Il suo scopo è di comunicare la struttura di un programma ad un altrə programmatorə senza restare impantanati della sintassi di uno specifico linguaggio di programmazione. E' più strutturato del semplice italiano, ma meno strutturato dei un codice eseguibile vero e proprio.

La tua descrizione e lo pseudocodice sono descrizioni di processi che producono lo stesso risultato. I passi descritti possono non essere identici dal momento che c'è più di un modo di calcolare il risultato.

Prova ad affiancarli e verifica che producono lo stesso risultato. Quali aspetti dello pseudocodice ti sono chiari? Quali parti ti confondono? Descrivono la stessa sequenza di passi? Se no, in cosa differiscono?

## Terza descrizione: codice vero e proprio

Infine, dai un'occhiata a [syntax.md](syntax.md). Questo contiene delle vere e proprie implementazioni in diversi linguaggi di programmazione. Vedi come questi programmi rappresentano la stessa procedura contenuta nella tua descrizione e nello pseudocodice?

Mettili fianco a fianco con lo pseudocodice e la tua descrizione. Prendi nota di quali pezzi di sintassi corrispondono a cose che comprendi e quali no. Puoi ricercare in rete molti di questi pezzi di sintassi per trovarne le spiegazioni.

In cosa differiscono i linguaggi tra loro? Come rappresentano gli elementi come il mazzo di carte o scrivere un numero su un post-it?
