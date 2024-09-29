<!-- Filename: Help4.x:Extensions:_Install / Display title: Estensioni: Installa -->

## Descrizione

Le estensioni vengono utilizzate per aggiungere funzionalità a Joomla! che non sono
presenti nell'installazione standard. Centinaia di estensioni sono disponibili per Joomla!,
e ne vengono sviluppate continuamente altre.

Le estensioni sono classificate in cinque tipi, come segue:

- Un *Componente* è una mini-applicazione che rende il corpo principale della
  pagina. Esempi di Componenti sono Contatti, la Prima Pagina e Feed di Notizie.
- Un *Modulo* è un' Estensione più piccola tipicamente utilizzata per visualizzare un piccolo
  elemento che appare su più pagine. Esempi di Moduli
  includono Menù e Articoli Correlati.
- Un *Plugin* è una sezione di codice che viene eseguita quando si verifica un evento
  predefinito all'interno di Joomla!. Ad esempio, gli editor sono Plugin che vengono eseguiti quando
  viene aperta una sessione di modifica.
- L'Estensione *Lingua* consente di presentare il Front-end e il Back-end di
  Joomla! in qualsiasi lingua per la quale esiste un'Estensione Lingua. In questo modo, Joomla! può essere rilasciato in una nuova lingua senza modifiche al programma di base.
- Un *Template* controlla il modo in cui viene visualizzato il contenuto di un sito web,
  inclusa la posizione e il layout degli elementi, i colori, i caratteri e così
  via. I Template consentono di separare l'aspetto del sito web dal suo contenuto.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).

## Come Accedere

- Seleziona **Sistema → Pannello di Installazione → Estensioni** dal menu
  dell'Amministratore.

Sono disponibili quattro metodi di installazione. Se **Installa dal Web** è stato
messo per primo nella lista o è stato l'ultimo metodo selezionato, ci sarà un
breve ritardo mentre Joomla scarica una selezione iniziale di dati delle Estensioni
dalla Directory delle Estensioni di Joomla.

L'ordine normale delle schede per i metodi di installazione è il seguente:

* Carica File Pacchetto
* Installa da Cartella
* Installa da URL
* Installa dal Web

È necessario solo un metodo per installare una determinata Estensione. La procedura
normale per installare un'Estensione di Joomla! è la seguente:

1.  Scarica uno o più file archivio (normalmente in formato ".zip" o "tar.gz")
    dal sito web del fornitore dell'Estensione a una directory locale
    sul tuo computer. Nota che alcune Estensioni sono installate come un
    unico file (ad esempio, un Componente o un Modulo) mentre altre Estensioni
    potrebbero avere due o più file (ad esempio, un Componente e un
    Modulo). Se ci sono due o più parti, ciascuna può avere il proprio
    file archivio. Oppure le parti possono essere combinate in un file pacchetto.
2.  Scegli uno dei metodi descritti per installare l'estensione.
3.  Quando è terminato, lo schermo mostrerà un messaggio di **Successo** o **Errore**.
4.  A seconda dell'Estensione, potrebbe essere necessario abilitare
    l'Estensione (ad esempio, nelle liste dei Moduli o dei Plugin).

## Scheda Carica File Pacchetto

![Scheda di installazione estensione carica file pacchetto](../../../it/images/extensions/install-upload-package-file.png)

- Trascina e rilascia o sfoglia fino alla posizione in cui hai scaricato
  il file di archivio dell'Estensione.

Il caricamento inizia automaticamente. Nota la **Dimensione massima di caricamento: 32.00MB**
definita per la tua installazione. Se non puoi aumentare questo valore, puoi utilizzare
*Installa dalla Cartella*.

## Installazione dalla Scheda Cartella

![Installazione estensione dalla scheda cartella](../../../it/images/extensions/install-from-folder.png)

1.  Crea una directory temporanea sul tuo disco rigido locale e decomprimi l'archivio dell'Extension in questa directory temporanea.
2.  Utilizzando un FTP, carica il contenuto di questa directory (inclusi file e sottodirectory) in una directory sul tuo server.
3.  Nel campo *Installa Directory* specifica la directory del server in cui hai caricato i file e le sottodirectory del pacchetto.
4.  Clicca sul pulsante *Verifica e Installa* e Joomla! installerà il contenuto della directory indicata.

Nota che è pratica comune inserire la cartella che contiene la tua estensione decompressa nella cartella tmp del tuo sito Joomla.

## Installazione dalla scheda URL

![Estensione installazione dalla scheda URL](../../../it/images/extensions/install-from-url.png)

Invece di scaricare il file archivio sul tuo computer locale, basta
specificare l’URL del file archivio desiderato. Poi clicca sul pulsante
"Controlla e Installa" e Joomla! lo installa automaticamente direttamente
da questo URL. *Nota che, con questo metodo, non avrai una copia del
file archivio sul tuo computer locale.*

## Installazione dalla Scheda Web

Per installare un'estensione direttamente dalla Directory delle Estensioni Joomla (JED), puoi selezionare le estensioni da elencare per Categoria o puoi cercarle per nome parziale.

![Installazione estensione dalla scheda web](../../../it/images/extensions/install-from-web.png)

## Consigli

- Sono disponibili quattro metodi alternativi di installazione, come indicato sopra.
  Il più comune è il metodo "Carica file del pacchetto".
- Se desideri installare un Modulo o Plugin di terze parti che appartiene a
  un Componente, in genere sarà necessario installare anche il Componente oltre
  al Modulo o Plugin per utilizzare il Modulo o Plugin. Questo è
  normalmente documentato nelle istruzioni di installazione dell'Estensione sul
  sito web dell'autore.
- Allo stesso modo, se disinstalli un Componente di terze parti che ha anche i suoi
  Moduli o Plugin, questi Moduli e Plugin non potranno più essere
  usati. Quindi è normalmente consigliato disinstallare anche questi Moduli e
  Plugin dipendenti.
- Alcuni Componenti sviluppati da sviluppatori di terze parti possono avere i loro
  propri Moduli o Plugin inclusi nell'installer. In questo caso, assicurati che le
  directory del Modulo o Plugin siano scrivibili. Altrimenti l'Estensione non
  funzionerà correttamente.
- **AVVERTENZA DI SICUREZZA:** Si consiglia di utilizzare solo quelle
  Estensioni di terze parti sul tuo sito di cui hai realmente bisogno. Non utilizzare
  il tuo sito live per scopi di test perché potrebbe compromettere il tuo
  sito e server. Prova le nuove estensioni su un sito di test locale prima
  di distribuirle sul tuo sito live.
- Non installare Estensioni Joomla! scaricate da
  siti [Warez](https://en.wikipedia.org/wiki/Warez) perché
  potrebbero essere infettate da virus o malware che causano danni al
  server e possono contaminare il computer dei tuoi visitatori!
- Installare da un URL remoto può essere pericoloso. Per questo motivo, è
  generalmente consigliato utilizzare le opzioni "Installa da Web", "Carica
  file del pacchetto" o "Installa da cartella" quando si installano nuove
  Estensioni.

*Tradotto da openai.com*

