<!-- Filename: Help4.x:Extensions:_Discover / Display title: Estensioni: Scopri -->


## Descrizione

Questa pagina ti permette di scoprire le estensioni che non sono passate attraverso il normale processo di installazione. Ad esempio, alcune estensioni sono troppo grandi in termini di dimensione del file per essere caricate tramite l'interfaccia web a causa delle limitazioni dell'ambiente di hosting web. Utilizzando questa funzione, puoi caricare direttamente i file delle estensioni sul tuo server web utilizzando altri metodi come FTP o SFTP e posizionare quei file di estensione nella directory appropriata. Puoi poi utilizzare la funzione di scoperta per trovare la nuova estensione caricata e attivarla nella tua installazione di Joomla! Utilizzando l'operazione di scoperta, puoi anche scoprire e installare più estensioni contemporaneamente. Un'estensione può essere installata con la funzione di scoperta seguendo questi passaggi:

1. Carica i file dell'estensione non compressi nella directory appropriata della tua installazione di Joomla! Ad esempio, se vuoi caricare un'estensione di modello per il sito nella tua installazione di Joomla!, dovresti creare una directory per l'estensione del modello nella sottodirectory /templates della tua installazione di Joomla!. Quindi caricheresti i file dell'estensione del modello in quella directory.
2. Dopo aver caricato i file dell'estensione, torna alla pagina Scopri del Gestore Estensioni e seleziona il pulsante **Scopri** nella barra degli strumenti. Questo avvierà la funzione di ricerca che cercherà nelle directory delle estensioni di Joomla! le estensioni non installate.
3. Se l'estensione caricata è compatibile con la tua versione di Joomla! e non è già installata, apparirà nell'elenco delle estensioni scoperte in questa pagina.
4. Seleziona la casella di controllo a sinistra dell'estensione scoperta e poi seleziona il pulsante **Installa** nella barra degli strumenti. Questo installerà l'estensione nella tua installazione di Joomla!.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri elenco](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni di colonna dell'elenco](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordinamento degli elementi dell'elenco](jdocmanual?article=help/common-elements/list-ordering).
* [Paginazione elenco](jdocmanual?article=help/common-elements/list-pagination).

## Come Accedere

- Seleziona **Sistema → Pannello di Installazione → Scopri** dal menu Amministratore.

## Screenshot

![Scopri l'elenco delle estensioni](../../../it/images/extensions/discover-list.png)

## Intestazioni delle Colonne

- **Nome** Il nome dell'estensione.
- **Posizione** Indica se è un'estensione del sito o dell'amministratore.
- **Tipo** Il tipo di estensione – Modulo, Plugin, Template, Linguaggio.
- **Versione** Il numero di versione dell'estensione.
- **Data** La data di rilascio dell'estensione.
- **Autore** L'autore dell'estensione.
- **Directory** Se l'estensione è un plugin, questo mostra la sottodirectory all'interno della directory /plugins dell'installazione di Joomla! dove si trova l'estensione. Per impostazione predefinita, Joomla! ha le seguenti sottodirectory nella directory Plugins, ciascuna rappresentante diversi tipi di plugin definiti: authentication, content, editors, editors-xtd, extension, search, system, user.
- **ID** Il numero ID. Un numero di identificazione assegnato unicamente per questa voce. Viene assegnato automaticamente da Joomla! e viene utilizzato per l'identificazione interna della voce. Il numero non può essere modificato.

## Suggerimenti

- Se hai molte estensioni che vuoi installare, puoi caricarle tutte nelle directory appropriate della tua installazione di Joomla! e poi usare questa schermata per scoprirle tutte in un'unica operazione. Puoi quindi installare tutte le estensioni in un solo passaggio selezionandole tutte e cliccando sul pulsante **Installa** nella barra degli strumenti.

*Tradotto da openai.com*

