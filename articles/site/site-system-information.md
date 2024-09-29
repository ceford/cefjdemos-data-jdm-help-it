<!-- Filename: Help4.x:Site_System_Information / Display title: Informazioni di Sistema -->

## Descrizione

La pagina *Informazioni di Sistema* fornisce informazioni sull'ambiente del server host. Ci sono cinque diverse schede: Informazioni di Sistema, Impostazioni PHP, File di Configurazione, Permessi Cartelle e Informazioni PHP. Ogni scheda fornisce informazioni dettagliate su quell'aspetto del sito. È utile per la risoluzione dei problemi di configurazione.

- Nota che nessuna di queste impostazioni può essere modificata da queste schede. 
  Questo deve essere fatto in diverse posizioni all'interno dell'installazione
  di Joomla!, a seconda dell'impostazione specifica.
- Alcune impostazioni possono essere modificate dalla pagina Configurazione Globale. 
  Altre dipendono dalla configurazione del server host e non possono essere 
  modificate dall'interno di Joomla!.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di Aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).

## Come accedere

- Seleziona **Sistema → Pannello Informazioni → Informazioni di Sistema**
  dal menu Amministratore.

## Screenshot

![dashboard principale](../../../it/images/site/system-information-tab.png)

## Schede del Modulo

### Scheda Informazioni di Sistema

- **PHP Built on** Fornisce dettagli sul sistema operativo principale
  su cui gira il server web che esegue Joomla.
- **Database Type** Fornisce il tipo di database utilizzato 
  dall'installazione di Joomla.
- **Database Version** Fornisce la versione corrente del database MySQL
  utilizzato dall'installazione di Joomla.
- **Database Collation** Come è strutturato il database MySQL per le
  informazioni usate da Joomla!.
- **Database Connection Collation** Il charset e la collation del
  database.
- **PHP Version** Fornisce la versione corrente dello script server side 
  PHP che viene utilizzato per questa installazione di Joomla.
- **Web Server** Fornisce il tipo corrente e la versione del server web
  su cui è in esecuzione l'installazione di Joomla!.
- **Web Server to PHP Interface** Lo script che permette l'interazione
  tra il server web (nella maggior parte dei casi, Apache) e il 
  linguaggio di scripting PHP.
- **Joomla! Version** Fornisce la versione corrente di Joomla!. È
  consigliato che sia sempre aggiornato e utilizzi l'ultima versione 
  stabile.
- **User Agent**Riassunto del sistema operativo locale dell'utente 
  corrente e delle informazioni del browser utilizzate per creare 
  un ID di sessione univoco per l'accesso e la funzionalità all'interno 
  del sito Joomla!.

### Scheda Impostazioni PHP

![home dashboard](../../../it/images/site/php-settings-tab.png)

Questa schermata mostra le informazioni sulle impostazioni PHP. Se 
alcuna di queste viene evidenziata come errata, è necessario correggerla.

- **Safe Mode** Impostazione consigliata: OFF
- **Open basedir** Impostazione consigliata: Dipende dal sito
- **Display Errors** Impostazione consigliata: OFF
- **Short Open Tags** Impostazione consigliata: ON
- **File Uploads** Impostazione consigliata: ON
- **Magic Quotes** Impostazione consigliata: OFF
- **Register Globals** Impostazione consigliata: OFF
- **Output Buffering** Impostazione consigliata: OFF
- **Session Save Path** Impostazione consigliata: Dipende dal sito
- **Session Auto Start** Impostazione consigliata: 0
- **XML Enabled** Impostazione consigliata: SÌ
- **Zlib Enabled** Impostazione consigliata: SÌ
- **Native ZIP Enabled** Impostazione consigliata: SÌ
- **Disabled Functions** Impostazione consigliata: Dipende dal sito
- **Multibyte String (mbstring) Enabled** Impostazione consigliata: SÌ
- **Iconv Available** Impostazione consigliata: SÌ
- **Maximum Input Variables** Impostazione consigliata: 2500

### Scheda File di Configurazione

![home dashboard](../../../it/images/site/configuration-file-tab.png)

Questa scheda mostra il contenuto del file *configuration.php* corrente di Joomla!
che è memorizzato nella directory `path-to-joomla-root`. Questo file è creato automaticamente
quando si installa Joomla! per la prima volta e dove vengono registrate la maggior parte delle
modifiche della sezione Configurazione Globale di Joomla!. Si noti che nessuna delle
impostazioni può essere modificata da questa pagina. Usa Configurazione Globale per
vedere ulteriori informazioni su queste impostazioni e per apportare modifiche.

### Scheda Permessi delle Cartelle

![home dashboard](../../../it/images/site/folder-permissions-tab.png)

Questa scheda mostra un elenco delle directory a cui il server web deve
avere accesso in scrittura. Si noti che tutte le directory elencate in questa
pagina dovrebbero riportare **Scrivibile**. Se così non fosse, potresti dover
modificare i permessi per poter installare e utilizzare Joomla! con successo.
Il file configuration.php è incluso e mostrato come **Non scrivibile**.

### Scheda Informazioni PHP

![home dashboard](../../../it/images/site/php-information-tab.png)

Questa scheda visualizza le impostazioni di configurazione del linguaggio di scripting PHP 
lato server che Joomla! utilizza, insieme a tutte le informazioni di sistema
associato alla creazione del server web. È il risultato di uno script php.info integrato
all'interno di Joomla!.

PHP è installato ed eseguito sul server (da qui il termine "lato server" sopra menzionato),
e quindi tutte le impostazioni vengono fatte sul server. Il visitatore
del sito web non ha bisogno di avere nulla di speciale in esecuzione sulla 
sua macchina locale per visualizzare o utilizzare qualsiasi funzionalità aggiuntiva
che PHP offre al sito web.

Tutte le impostazioni che potrebbero mai essere necessarie sono visualizzate qui.
Eventuali modifiche richieste saranno fatte all'interno del file *php.ini* 
e di altri file di configurazione sul server web.

Quanto controllo ha il proprietario di un sito web su queste informazioni dipende
dal fatto che possieda il server o se il fornitore di servizi del server sia 
flessibile nel loro approccio ai clienti.

È buona pratica conoscere i limiti di una particolare installazione del server.
L'output di questa schermata è utilizzato per trovare informazioni dettagliate 
su come PHP è implementato sul server.

Per dettagli completi sulle informazioni contenute nella scheda Info PHP
visita: [http://php.net/phpinfo](http://php.net/phpinfo).

## Suggerimenti

- Se stai avendo problemi con l'installazione delle estensioni, il caricamento dei file o con la modifica delle opzioni di configurazione, controlla la scheda delle Autorizzazioni delle Directory per assicurarti di avere il permesso di scrivere sui file del tuo server web. Lo *Stato* delle directory dovrebbe essere *Scrivibile*. In caso contrario, potresti non essere in grado di caricare o modificare i file in queste directory.
- Quando cerchi assistenza per problemi di configurazione, ad esempio in un forum web di Joomla!, è molto utile fornire informazioni specifiche sulla tua installazione Joomla!. Questa pagina è un modo semplice per trovare tutte queste informazioni in un unico posto. Ancora meglio - utilizza il **Forum Post Assistant** documentato in cima alle singole pagine del Forum di Joomla, come il forum delle [Domande Generali](https://forum.joomla.org/viewforum.php?f=834).

*Tradotto da openai.com*

