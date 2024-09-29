<!-- Filename: Help6.x:List_Filters / Display title: Filtri di Elenco -->

## Scopo¶

La maggior parte dei componenti ha viste elenco che mostrano elementi del database. Ci possono essere centinaia di elementi, forse migliaia, o persino milioni. Quindi i filtri elenco vengono utilizzati per ridurre l'elenco visualizzato a quelli che probabilmente contengono quello su cui devi lavorare.

Ad esempio, gli elementi cestinati di solito non vengono visualizzati per impostazione predefinita. Se desideri vedere i tuoi elementi cestinati, devi impostare il filtro **- Seleziona Stato -** su **Cestinato**. Lo screenshot seguente mostra i filtri per la pagina degli articoli.

## Opzioni di Filtro Elenco Articoli¶

![Elenco articoli](../../../it/images/common-elements/articles-list-filter-options.png)

Per **mostrare** o **nascondere** le Opzioni, seleziona il pulsante **Opzioni Filtro**. Nota
che le Opzioni sono sempre visualizzate al ritorno su qualsiasi pagina in cui è stata selezionata un'Opzione.

Il numero di Opzioni visualizzate varia in base al componente. Anche il componente Contenuto, che mostra l'elenco degli Articoli, può avere filtri aggiuntivi. Ad esempio, un filtro **- Seleziona Fase -** viene visualizzato se il componente Contenuto ha i **Flussi di Lavoro** abilitati.

## La Barra di Ricerca

### Ricerca per Testo

*Passa sopra* o *Seleziona* il campo di *Ricerca* per vedere un *Tooltip* o ascoltare un *Audio*
equivalente che indica quali campi verranno ricercati. Il comportamento predefinito
è cercare il testo inserito all'interno del titolo.

Il componente di contenuto consente di usare un prefisso per cercare all'interno dell'ID, Autore o
Contenuto. Ciascuno di questi termini richiede due punti ma può essere in qualsiasi *Maiuscolo o minuscolo*. Ad esempio *ID:19* o *Autore:Giovanni* o *contenuto:lorem ipsum*.

Per eseguire una ricerca, inserisci parte del termine di ricerca e seleziona l'icona **Cerca**
(<span class="filter-search-bar__button-icon icon-search" aria-hidden="true"></span>).

### Opzioni di Filtro e Pulisci

Il pulsante **Opzioni di Filtro** viene utilizzato per attivare o disattivare la visualizzazione dei vari filtri. Se
non ci sono filtri per un componente, questo pulsante sarà assente.

Il pulsante **Pulisci** viene utilizzato per cancellare tutti i filtri e ripristinare la lista allo stato
non filtrato. Se non ci sono filtri per un componente, questo pulsante sarà assente.

### Ordine dei Risultati

L'ordine in cui vengono presentati i risultati è selezionabile dall'utente. Per gli articoli, l'ordine
predefinito è *ID Discendente*, che mette gli articoli più recenti in cima alla lista. Ma potresti voler cercare articoli per numero di visite,
*Visite discendente*, o articoli che spariranno presto,
*Fine Pubblicazione crescente*.

L'ordine dei risultati può essere cambiato selezionando un'icona di ordinamento nell'intestazione delle colonne della lista. L'icona predefinita *ID Discendente* è rappresentata da un
carello giù (<span class="ms-1 icon-caret-down" aria-hidden="true"></span>).
Cambia in un carello su se l'ordine di ordinamento viene invertito, *ID Ascendente*.

### Numero di Risultati

Il numero di risultati in una lista è impostato nella pagina Configurazione Globale, scheda Sito, campo Limite Elenco Predefinito. Il valore predefinito per una nuova installazione è 20.

Ci sono occasioni in cui questo non è conveniente. Potresti voler vedere *50* o
*100*. Fai attenzione se scegli *Tutti*. Potrebbe richiedere molto tempo per recuperare
i risultati e rendere la pagina. Il server potrebbe esaurire la memoria o il tempo e attivare un errore fatale. E il tuo browser potrebbe impiegare molto tempo per visualizzare la pagina.

Il valore predefinito per questo set di documentazione è stato impostato a 5 perché è
sufficiente per screenshot illustrativi.

## Come Usare i Filtri

Lo scopo di ciascun filtro dovrebbe essere evidente dalla sua etichetta del selettore non filtrata. Ad esempio, il filtro **- Seleziona Stato -** degli Articoli offre cinque opzioni: *Cestinate*, *Non Pubblicate*, *Pubblicate*, *Archiviato* e *Tutto*. Quest'ultima è funzionalmente equivalente a non filtrato (*- Seleziona Stato -*).

Quando viene cambiata un'opzione del filtro, la pagina si ricarica automaticamente con i nuovi risultati filtrati dall'opzione di filtro scelta.

## Nascondi Colonne

Alcuni elenchi di componenti hanno molte colonne e possono essere troppo larghi per il tuo schermo. Questo
è particolarmente vero per alcune traduzioni del testo dell'intestazione delle colonne. Il risultato più
fastidioso è che i Titoli potrebbero andare a capo e diventare difficili da leggere.

Per fare più spazio per il Titolo, puoi aprire l'elenco a discesa delle Colonne e
selezionare le colonne meno importanti da nascondere. Quindi chiudi di nuovo l'elenco delle Colonne. 
L'effetto è immediato poiché utilizza JavaScript per nascondere le colonne selezionate nel layout.
Sono ancora presenti nella pagina.

Le tue impostazioni vengono salvate dal tuo browser e saranno utilizzate fino a quando non le cambierai di nuovo,
anche se effettui il logout e il login di nuovo.

*Tradotto da openai.com*

