<!-- Filename: Help4.x:Smart_Search:_Content_Maps / Display title: Ricerca Intelligente: Mappe dei Contenuti  -->

## Descrizione

La pagina *Smart Search: Content Maps* mostra le mappe dei contenuti attualmente indicizzate
in Smart Search. Le mappe dei contenuti consentono di fare riferimento incrociato ai
contenuti indicizzati (articoli, ecc.) con le informazioni meta-correlate, come la categoria
in cui risiedono. Ogni elemento di contenuto indicizzato da Smart Search viene
aggiunto a una o più mappe di contenuto che possono essere utilizzate come filtri durante
la ricerca nell'indice.

Le mappe dei contenuti sono suddivise in due parti:

- Gruppo di Mappe: Questi sono super-contenitori per un tipo particolare di
  informazione. Ad esempio, un Gruppo di Mappe potrebbe essere *Tipo*, *Categoria*,
  *Evento*, *Lingua* o *Autore*.
- Mappa di Contenuto: Le mappe di contenuto sono i valori effettivi delle
  informazioni meta in un particolare Gruppo di Mappe. Le Mappe di Contenuto sono, per
  esempio, i nomi delle categorie o degli autori.

Questi Gruppi di Mappe e Mappe di Contenuto sono ciò che compone il pannello di ricerca
avanzata disponibile nel front-end. Per ciascun Gruppo di Mappe può esserci un elenco
a discesa e le Mappe di Contenuto vengono aggiunte come valori all'elenco
rispettivo. Gli sviluppatori di siti più avanzati possono sovrascrivere i layout predefiniti
e utilizzare elenchi multi-selezione o caselle di controllo invece.

È importante notare che i Gruppi di Mappe e le Mappe di Contenuto di diversi
tipi di contenuto vengono uniti in un unico elenco. Un articolo di Joomla in una
categoria chiamata *News* e un feed di notizie o un contatto in una categoria con lo
stesso nome sono mappati alla stessa Mappa di Contenuto nel medesimo Gruppo di Mappe.
Questo è un pò come etichettare tipi diversi di contenuto con la stessa etichetta.
L'effetto è che il visitatore del tuo sito non deve sapere come i tuoi
contenuti sono classificati per impostare i filtri corretti per trovarli.

La schermata delle mappe dei contenuti mostra tutti i Gruppi di Mappe all'interno dell'indice
di Smart Search insieme con un numero che indica il numero di Mappe di Contenuto
all'interno di quel Gruppo di Mappe e gli elementi all'interno di una Mappa di Contenuto.
Cliccando su un numero di Gruppo di Mappe puoi vedere la Mappa di Contenuto all'interno
di quel Gruppo di Mappe insieme al numero di elementi di contenuto che
appartengono a quella Mappa di Contenuto. Un elemento di contenuto può appartenere
a più Mappe di Contenuto all'interno di un Gruppo di Mappe così come a più Gruppi di Mappe.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri Elenco](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni delle Colonne dell'Elenco](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordinamento degli Elementi dell'Elenco](jdocmanual?article=help/common-elements/list-ordering).
* [Paginazione dell'Elenco](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Se sei nuovo in Smart Search, dovresti leggere la [guida introduttiva
  di Smart Search](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Come accedere

- Seleziona **Componenti → Ricerca Avanzata → Mappe di Contenuti** dal 
  menu dell'Amministratore.

## Screenshot

![mappa dei contenuti di ricerca intelligente](../../../it/images/smart-search/smart-search-content-maps.png)

## Intestazioni della Colonna

- **Stato** Lo stato dell'elemento di contenuto all'interno di Smart Search. Modificare lo stato influisce solo sulla disponibilità dell'elemento di contenuto nei risultati di ricerca e non sull'elemento di contenuto stesso.
- **Titolo** Il titolo del Gruppo di Mappe o della Mappa di Contenuti.
- **Mappe** Il numero di mappe all'interno del Gruppo di Mappe. Selezionare il numero mostrerà le mappe all'interno del Gruppo di Mappe.
- **Contenuti Indicizzati Pubblicati** Il numero di elementi di contenuti pubblicati nel Gruppo di Mappe. Selezionare il numero mostrerà gli elementi di contenuto pubblicati all'interno del Gruppo di Mappe.
- **Contenuti Indicizzati Non Pubblicati** Il numero di elementi di contenuti non pubblicati nel Gruppo di Mappe. Selezionare il numero mostrerà gli elementi di contenuto non pubblicati all'interno del Gruppo di Mappe.

## Barra degli strumenti

- **Azioni** Rivela un elenco di azioni per gli oggetti selezionati. Seleziona
  uno o più oggetti per attivare l'elenco.
  - **Pubblica**. Rende i Gruppi di Mappe o le Mappe di Contenuti selezionati disponibili
    ai visitatori del tuo sito web.
  - **Depubblica**. Rende i Gruppi di Mappe o le Mappe di Contenuti selezionati
    non disponibili ai visitatori del tuo sito web. Un Gruppo di Mappe depubblicato
    non verrà visualizzato come un elenco selezionabile nel front-end. Una Mappa di Contenuti depubblicata non apparirà nell'elenco selezionabile per il Gruppo di Mappe in cui si trova. La reindicizzazione non cambia lo stato di pubblicazione
    dei Gruppi di Mappe o delle Mappe di Contenuti.
- **Elimina** Elimina i Gruppi di Mappe o le Mappe di Contenuti selezionati. Funziona
  con uno o più Gruppi di Mappe o Mappe di Contenuti selezionati. Puoi
  recuperare i Gruppi di Mappe o le Mappe di Contenuti eliminati eseguendo nuovamente l'indicizzatore Smart Search.
- **Statistiche** Mostra alcune statistiche di base su Smart Search.

*Tradotto da openai.com*

