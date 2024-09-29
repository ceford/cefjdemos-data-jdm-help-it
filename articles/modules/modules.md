<!-- Filename: Help6.x:Modules / Display title: Moduli -->

## Descrizione

I moduli sono estensioni leggere e flessibili utilizzate per visualizzare frammenti di informazioni in riquadri disposti attorno a un componente su una pagina. Un esempio ben noto è il modulo *Login*. I moduli sono assegnati per voce di menu, quindi puoi decidere di mostrare o nascondere un modulo a seconda della pagina che l'utente sta visualizzando.

Alcuni moduli sono collegati a componenti. Ad esempio, il modulo *Ultime Notizie* è collegato al componente di contenuto per visualizzare i link agli articoli più recenti. I moduli non devono essere necessariamente collegati a componenti. Non hanno nemmeno bisogno di essere collegati a niente e possono essere semplicemente HTML statico o testo.

Possono esserci più istanze dello stesso modulo. Ad esempio, puoi utilizzare un'istanza del modulo *Immagine Casuale* per alcune pagine e un'altra istanza per altre pagine, ciascuna utilizzando una diversa cartella di immagini da cui selezionare le immagini.

Gli elenchi *Moduli (Sito)* e *Moduli (Amministratore)* mostrano i moduli attualmente installati in ciascuna interfaccia e forniscono accesso per aggiungere nuovi moduli o modificare quelli esistenti.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di Aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri Lista](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni delle Colonne della Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordinamento degli Elementi della Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginazione della Lista](jdocmanual?article=help/common-elements/list-pagination).
* [Processo Batch della Lista](jdocmanual?article=help/common-elements/list-batch-process).

Per vedere gli elenchi dei moduli installati e dei moduli disponibili, seleziona uno dei seguenti:

* [Moduli del sito](jdocmanual?article=help/modules-site/site-modules-site)
* [Moduli dell'amministratore](jdocmanual?article=help/modules-admin/admin-modules-administrator)

## Come accedere

- Seleziona **Contenuti → Moduli del sito** dal menu Amministratore. Oppure...
- Seleziona **Contenuti → Moduli dell'amministratore** dal menu Amministratore.

## Filtri Elenco

* **Sito o Amministratore** Seleziona moduli Sito o Amministratore.

## Intestazioni delle Colonne

Questa è una breve lista delle intestazioni uniche per le liste di moduli.

- **Posizione** La posizione nella pagina in cui viene visualizzato questo modulo.
- **Tipo** Il nome di sistema del Modulo.
- **Pagine** Gli Elementi del Menu in cui questo Modulo verrà visualizzato. Questo elemento non è presente nelle liste dei moduli Amministratore.
  - *Tutte* Visualizzato su tutte le pagine
  - *Nessuna* Visualizzato su nessuna pagina
  - *Selezionate* Visualizzato solo sulle pagine selezionate
  - *Tutte tranne selezionate* Visualizzato su tutte le pagine tranne quelle selezionate
- **Accesso** Il livello di accesso per la visualizzazione di questo modulo.
- **Lingua** La lingua dei Moduli, il valore predefinito è *Tutte*. Questo elemento non è presente nelle liste dei moduli Amministratore.

### Posizioni del Modulo

Per visualizzare le posizioni dei moduli in un sito live, vai a **Sistema → Template** e seleziona il pulsante **Opzioni** nella barra degli strumenti. Imposta *Anteprima Posizioni Moduli* su abilitato e *Salva*. Questa impostazione è valida sia per i template del sito che per quelli dell'amministratore. Poi aggiungi `?tp=1` alla fine di un URL che non contiene già una stringa di query oppure `&tp=1` alla fine di un URL che già contiene una stringa di query. La pagina mostrerà tutte le posizioni dei moduli disponibili, anche quelle a cui non sono stati assegnati moduli. Le posizioni sono mostrate anche nel modulo di modifica dei moduli.

## Suggerimenti

- I siti Joomla richiedono almeno un modulo menu.
- Altri tipi di moduli (ad esempio Banner) sono opzionali.
- Alcuni moduli sono collegati a componenti. Ad esempio, ogni modulo menu
  è correlato a un menu.
- Altri moduli (ad esempio Breadcrumbs) non dipendono da nessun altro contenuto.
- Sono consentite e comuni più occorrenze di un modulo.

*Tradotto da openai.com*

