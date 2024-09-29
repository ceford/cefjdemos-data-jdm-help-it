<!-- Filename: Help4.x:Help_screens_styleguide / Display title: Guida di Stile per le Schermate di Aiuto -->

<div class="alert alert-warning">
Questa guida di stile è per l'installazione di Joomla MediaWiki (docs.joomla.org).
</div>

Questo documento è in fase di sviluppo e dovrebbe essere utilizzato come linea guida per
creare schermate di aiuto per **Joomla 3.x**. Le schermate di aiuto presenti
sul Wiki di Joomla! Docs vengono consultate da ogni installazione di Joomla!
che utilizza il sistema di aiuto predefinito. Seguendo questa
guida di stile, il Progetto Joomla! può offrire coerenza in tutte le
schermate di aiuto, consentendo una navigazione più facile.

Se hai domande, pubblicale sulla pagina di discussione associata alla
schermata di aiuto cliccando sulla scheda ***Discussione*** nella parte superiore della
pagina della schermata di aiuto.

## Layout della Pagina di Aiuto

### Descrizione

Ogni schermata di aiuto dovrebbe avere una sezione "**Descrizione**". Questa sezione va più nel dettaglio su cosa fa la schermata ed è utilizzata nelle tabelle delle schermate di aiuto in tutto questo wiki. <a href="https://docs.joomla.org/Menu_Management#Menu_Management_Help_Screens" class="mw-redirect" title="Gestione dei Menu">Ecco un esempio d'uso</a>.

Non c'è un formato specifico per questa sezione perché la descrizione dovrebbe essere in correlazione diretta con lo scopo e la funzionalità della schermata. Possono esserci sottosezioni della descrizione che descrivono dettagli più specifici. Cerca di mantenere la descrizione breve e precisa; se la descrizione è lunga, valuta l'uso di elenchi puntati per riassumerla.

## Come Accedere

Ogni schermata di aiuto dovrebbe avere una sezione **Come Accedere** che fornisce i passaggi necessari per raggiungere la schermata descritta. Questo potrebbe essere ridondante perché un utente deve essere sulla schermata dell'amministratore per aver recuperato la schermata di aiuto. Ricorda, le schermate di aiuto possono essere recuperate in diversi modi. Ad esempio, qualcuno che utilizza un motore di ricerca per scoprire come fare qualcosa potrebbe imbattersi in una schermata di aiuto sul wiki senza mai aver accesso al sistema di aiuto.

#### Note:

- Se il modo per raggiungere la schermata è da un'altra schermata, allora il nome di quella schermata dovrebbe essere un link alla sua schermata di aiuto.
- Si "clicca" sui pulsanti, inclusi i pulsanti della barra degli strumenti, ma si "selezionano" le voci di menu. L'uso coerente di questa terminologia dovrebbe aiutare gli utenti.
- Per facilitare il rendering, la freccia destra (→), **Questo puntamento → a quello**.

### Screenshot

Screenshot che mostra l'aspetto generale della schermata.

#### Note:

- Le immagini degli screenshot possono avere qualsiasi larghezza, ma le immagini più grandi dovrebbero avere \|800px aggiunto nel sorgente.
- Il nome del file dovrebbe seguire le nostre
  <a href="https://docs.joomla.org/JDOC:Image_naming_convention"
  class="mw-redirect" title="JDOC:Image naming convention">convenzioni standard di denominazione</a> per le schermate di aiuto.
  **Help-3x-***\<menu
  system-path-in-lowercase-separated-by-dashes\>***-screen-en.png**.
  Ad esempio, uno screenshot della schermata Gestione Articoli sarebbe
  **\[\[File:Help-3x--content-article-manager-screen-en.png\]\]**.
- Il nome del file dovrebbe sempre includere un codice lingua alla fine del nome, per l'inglese -en viene aggiunto.
- Puoi usare file .png o .jpg.

## Campi del Modulo (per Scheda)

### Scheda Dettagli

Questa sezione dovrebbe essere inclusa solo nelle schermate di aiuto che descrivono schermi che includono un modulo. Questo include tutte le schermate di aggiunta/modifica, ma include anche schermate come Configurazione Globale del Sito e popup modali come <a href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options" title="Help4.x:Components Article Manager Options">Help4.x:Components Article Manager Options</a>.

### Altri Tipi di Schede

Se i campi sono raggruppati in gruppi di campi o schede, raggruppare i campi sotto sotto-heading.

### Intestazioni delle Colonne

Questa sezione dovrebbe essere inclusa solo nelle schermate di aiuto che descrivono schermate di gestione back-end; cioè, dove viene mostrato un elenco di elementi. Questa sezione dovrebbe descrivere ciascuna delle colonne dell'elenco.

### Filtri dell'Elenco

Questa sezione dovrebbe essere inclusa solo nelle schermate di aiuto che descrivono schermate di gestione back-end; cioè, dove viene mostrato un elenco di elementi. Questa sezione dovrebbe descrivere come utilizzare i filtri dell'elenco per filtrare i contenuti dello schermo. Vedi <a href="https://docs.joomla.org/Screen.content.15#List_Filters" title="Screen.content.15">Screen.content.15#List_Filters</a> per esempio dalla 1.5.

### Opzioni

Questa sezione dovrebbe essere inclusa solo nelle schermate di aiuto dove la schermata ha un pulsante della barra degli strumenti Opzioni che apre una sottoschermata modale delle opzioni. Se ci sono molte opzioni e la schermata di aiuto diventerebbe eccessivamente lunga se venissero descritte qui, allora collegare a una schermata di aiuto separata con un suffisso "\_Options". Per esempio, vedere <a href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options" title="Help4.x:Components Article Manager Options">Components Article Manager Options</a>.

Poiché la schermata modale Opzioni è di solito tabulata, dovresti aggiungere una sottosezione sotto questa sezione per ogni scheda. Per esempio, se c'è una scheda etichettata "Layout di Modifica", dovresti aggiungere un'intestazione di terzo livello con quel nome e in quella sottosezione dovresti descrivere ciascuno dei campi disponibili. Dovresti iniziare ogni sottosezione con uno screenshot del pannello Opzioni appropriato.

### Barra degli Strumenti

Ovviamente, questa sezione dovrebbe essere inclusa solo nelle schermate di aiuto dove è presente una barra degli strumenti.

Descrive i pulsanti disponibili e le loro funzioni associate. Utilizza **chunks** qui perché molti saranno gli stessi per diversi schermi. Meglio fornire un'immagine della barra degli strumenti.

La prima parola dovrebbe sempre essere un verbo e, a meno che non sia un verbo irregolare, dovrebbe anche terminare con la lettera "s". Ciò significa che dovresti strutturare la descrizione come se stessi usando la parola "questo" come soggetto, ma lasciare il soggetto fuori dalla frase. Questo renderà la frase in realtà un frammento di frase. Per esempio:

- Invece di "Per trovare tesori sepolti, clicca su questo pulsante."
  - Dì, "Trova tesori sepolti."
- Invece di "Puoi cliccare su questo pulsante per inserire un'immagine di John Stamos nel documento corrente."
  - Dì, "Inserisce un'immagine di John Stamos."
- Invece di "Informati che un'immagine di John Stamos è la stessa cosa di un tesoro sepolto."
  - Dì, "Informa che un'immagine di John Stamos è la stessa cosa di un tesoro sepolto."

Poiché molte barre degli strumenti sono le stesse su più schermate, la convenzione di denominazione dei file di immagini della barra degli strumenti mira a rendere facile il riutilizzo delle immagini della barra degli strumenti ovunque possibile. Le immagini della barra degli strumenti dovrebbero seguire questa convenzione di denominazione: Help\<versione\>-Toolbar-\<listaicone\>.png dove \<listaicone\> è un elenco separato da '-' delle legende della barra degli strumenti. Ogni parola dovrebbe essere capitalizzata, spazi e '&' rimossi. Per esempio: Help30-Toolbar-New-Edit-Delete-Options-Help.png

### Processo Batch

Questa sezione dovrebbe essere inclusa solo nelle schermate di aiuto dove la schermata ha una funzione di processo batch. Per esempio, vedere <a href="https://docs.joomla.org/Help4.x:Components_Banners_Categories" title="Help4.x:Components Banners Categories">Help4.x:Components Banners Categories</a>.

### Suggerimenti

Come suggerisce il nome, questa sezione dovrebbe includere consigli, suggerimenti, suggerimenti che possono aiutare un utente nell'esecuzione di compiti che coinvolgono lo schermo.

*Tradotto da openai.com*

