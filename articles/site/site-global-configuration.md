<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Configurazione Globale -->

## Descrizione

La schermata di Configurazione Globale consente di configurare il sito Joomla
con le tue impostazioni personali. Le impostazioni effettuate in questa schermata si applicano all'intero sito.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda delle Autorizzazioni](jdocmanual?article=help/common-elements/edit-permissions).

## Come accedere

- Seleziona **Pannello di sistema → Configurazione globale** dalla Dashboard principale. Oppure...
- Seleziona **Sistema → Pannello di configurazione → Configurazione globale** dal menu dell'Amministratore.

## Schermata

![scheda di configurazione globale del sito](../../../it/images/site/global-configuration-site-tab.png)

## Campi del modulo

### Scheda Sito

#### Pannello Sito

- **Nome del Sito** Inserisci il nome del sito web. Verrà utilizzato in
  varie posizioni (ad esempio nella barra del titolo del browser del Backend e nelle pagine
  di sito fuori linea).
- **Sito Offline** Seleziona se l'accesso al Frontend è disponibile.
- **Messaggio Offline**
    - *Nascondi*
    - *Usa messaggio personalizzato* Il messaggio utilizza il valore definito nel
      campo *Messaggio personalizzato*.
    - *Usa il messaggio predefinito della lingua del sito* Il messaggio utilizza il valore
      definito nel file ini della lingua del sito.
- **Immagine Offline** Seleziona un'immagine da visualizzare nella pagina offline.
    Assicurati che l'immagine sia larga meno di 400px.
- **Modifica Frontend** Seleziona la modifica di moduli e voci di menu.
- **Editor predefinito** Seleziona l'editor di testo predefinito. Gli utenti registrati
  potranno cambiare la loro preferenza nei loro dettagli personali.
- **Captcha predefinito** Seleziona il captcha predefinito per il tuo sito. Potrebbe essere
  necessario inserire le informazioni richieste nel plugin captcha.
- **Livello di accesso predefinito** Seleziona il livello di accesso predefinito per i nuovi
  elementi.
- **Limite elenco predefinito** Imposta la lunghezza predefinita degli elenchi nel
  Backend per tutti gli utenti.
- **Limite feed predefinito** Seleziona il numero di articoli da mostrare nei
  feed.
- **Indirizzo email feed** I feed RSS e Atom includono l'indirizzo email
  dell'autore.
  - *Email autore* Includi l'email dell'autore dell'articolo dal Profilo Utente
    nel feed delle notizie.
  - *Email del sito* Includi l'indirizzo *Da Email* del sito per ogni articolo.

#### Pannello Metadata

- **Descrizione Meta del Sito** Inserisci una descrizione generale del sito web
  che verrà utilizzata dai motori di ricerca.
- **Robot** Istruzioni per i robot.
  - *index, follow* Indica ai motori di ricerca di indicizzare questa pagina e di seguire i link presenti.
  - *noindex, follow* Indica ai motori di ricerca di non indicizzare questa pagina, ma di seguire comunque i link.
  - *index, nofollow* Indica ai motori di ricerca di indicizzare questa pagina, ma di non seguire i link.
  - *noindex, nofollow* Indica ai motori di ricerca di non indicizzare questa pagina e di non seguire i link.
- **Diritti sui contenuti** Descrivi i diritti che altri hanno di usare questi
  contenuti. Questo è trasmesso ai motori di ricerca utilizzando il meta
  tag `rights` nell'intestazione HTML.
- **Tag Meta Autore** Mostra il tag meta autore quando si visualizzano articoli.
- **Versione di Joomla** Controlla se il meta tag `generator` nell'intestazione
  del documento HTML nel Frontend e nei feed Atom include la versione
  esatta del sito Joomla. Si consiglia di nasconderlo per motivi di sicurezza.

#### Pannello SEO

- **URL amichevoli per i motori di ricerca** Seleziona se gli URL sono ottimizzati per
  i motori di ricerca.
- **Usa la Riscrittura degli URL**
  - *Apache e Litespeed* Rinomina `htaccess.txt` in `.htaccess`.
  - *IIS* Rinomina `web.config.txt` in `web.config`.
  - *NginX* devi configurare il tuo server.
  - *Altro* Se non sei sicuro, contatta il tuo hosting.
- **Aggiungi suffisso all'URL** Se selezionato, il sistema aggiungerà un suffisso all'URL
  basato sul tipo di documento.
- **Alias Unicode** Scegli tra traslitterazione e alias unicode. La traslitterazione è l'opzione predefinita.
- **Nome del sito nei titoli delle pagine** Inizia o termina tutti i titoli delle pagine con il
  nome del sito (ad esempio, *Il Mio Nome Sito - Il Mio Nome Articolo*).

#### Pannello Cookie

- **Dominio Cookie** Dominio da utilizzare quando si impostano i cookie di sessione. Precede
  il dominio con '.' se il cookie deve essere valido per tutti i sotto-domini.
- **Percorso Cookie** Percorso per cui il cookie sarà valido.

### Scheda Sistema

![scheda di configurazione globale del sistema](../../../it/images/site/global-configuration-system-tab.png)

#### Pannello Debug

- **Debug Sistema** Se attivato, visualizzerà le informazioni diagnostiche, la
  traduzione delle lingue e gli errori SQL (se presenti). Le informazioni
  saranno visualizzate al fondo di ogni pagina visualizzata nel Backend e nel
  Frontend di Joomla. Non è consigliabile lasciare la modalità debug attivata
  quando si gestisce un sito live.
- **Debug Linguaggio** Abilita per vedere gli indicatori di debug `**...**`
  o `??...??` nell'output della pagina dove i file di lingua di Joomla sono utilizzati per tradurre
  le chiavi di stringa nei loro valori tradotti. Il primo formato indica che la stringa
  è stata tradotta con successo. Il secondo indica che il testo è stato
  inserito in linguaggio semplice e non può essere tradotto.
  - **Visualizzazione Lingua** Seleziona se mostrare il costante della lingua
  o il valore della lingua durante il debug delle stringhe delle lingue.

#### Pannello Cache

- **Cache del Sistema** Abilita la cache e imposta il livello della cache.
  - *Livello conservativo* cache del sistema più piccola.
  - *Livello progressivo* cache del sistema più veloce e più grande, include la
    cache dei moduli renderers. Non appropriato per siti estremamente grandi.
  - **Gestore Cache**
    - *File* Il meccanismo di cache nativo è basato su file. Assicurati che le
      cartelle di cache siano scrivibili.
  - **Caching specifico per piattaforma** Abilita quando l'output HTML sui dispositivi mobili
    differisce dagli altri dispositivi.
  - **Tempo di cache (minuti)** La durata massima in minuti per
    cui un file della cache viene memorizzato prima di essere aggiornato.
  - **Percorso alla cartella di Cache** Specifica una cartella scrivibile per memorizzare i
    file di cache se non desideri utilizzare la cartella predefinita.

#### Pannello Sessione

- **Gestore della sessione** Il meccanismo con cui Joomla identifica un Utente
  una volta connesso al sito utilizzando i cookie non persistenti.
  - *Database* Il gestore di sessione del database è il gestore predefinito
    perché è l'unico che Joomla può configurare e controllare completamente da solo.
  - *File system* Il gestore del file system sarà leggermente più performante
    rispetto a quello del database, ma richiede che PHP sia configurato
    correttamente altrimenti si bloccherà e Joomla sarà totalmente inutilizzabile.
    - *Percorso di salvataggio della sessione* Inserisci un percorso completo del file system. Assicura che
      il percorso abbia le autorizzazioni appropriate affinché PHP possa leggere e scrivere file,
      e, se `session garbage collection` è abilitato, per eliminare file
      da esso. Se questo percorso non è impostato, Joomla si affiderà alla configurazione
      PHP `session.save_path INI` o al fallback della directory temporanea del sistema
      (come definito dalla funzione PHP sys_get_temp_dir()). Se nessuno di questi percorsi è
      configurato o le autorizzazioni sono errate, tutto sarà bloccato. Per recuperare, modifica il
      file configuration.php e imposta `$session_handler = 'database'`.
  - *Altri gestori* APCu, Memcached, Redis e WinCache si affidano tutti a
    estensioni PHP opzionali e possono essere disponibili se il tuo sistema li supporta.
    APCu o WinCache potrebbero non essere migliori dell'opzione *plain* file system.
    I gestori Memcached e Redis sono eccessivi per Joomla in un ambiente di hosting condiviso
    tipico. Questi tipi di gestori riescono se stai distribuendo Joomla in un ambiente di bilanciamento
    del carico dove sono coinvolti più server e hai bisogno che i dati della sessione
    siano disponibili su tutti i server.
- **Durata della sessione (minuti)** Disconnette automaticamente un Utente dopo che è stato
  inattivo per il numero di minuti inserito. Non impostare un valore troppo alto.
- **Sessioni condivise** Quando abilitato, la sessione di un utente è condivisa tra
  le sezioni Frontend e Backend del sito. Nota che cambiare questo
  valore invaliderà tutte le sessioni esistenti sul sito. Questo non è
  disponibile quando l'opzione [Forza HTTPS](#forcehttps) è impostata su
  *Solo Amministratore*.
- **Traccia metadati sessione**
  - *Sì* Metadati aggiuntivi sulla sessione di un utente (compresi il loro
    nome utente, ID utente e l'applicazione a cui sono connessi) saranno
    registrati nella tabella del database delle sessioni.
  - *No* Le funzioni dipendenti da questi dati non saranno disponibili.

### Scheda Server

![scheda di configurazione globale del server](../../../it/images/site/global-configuration-server-tab.png)

#### Pannello Server

- **Percorso alla cartella temporanea** Specifica una cartella scrivibile per memorizzare
  file temporanei.
- **Compressione delle pagine Gzip**
  - *Sì* Comprimi automaticamente le pagine HTML generate con Gzip,
    rendendole più piccole e aumentando il punteggio di velocità del tuo sito.
  - *No* Se il tuo server lo fa già per te o se ci sono conflitti
    con le estensioni di terze parti.
- **Segnalazione errori** Questo parametro imposta il livello di segnalazione errori
  da utilizzare su PHP sul sito Joomla.
  - *Predefinito del sistema* Lascia il livello di segnalazione errori impostato
    nel server.
  - *Nessuno* Disattiva la segnalazione errori.
  - *Semplice* Sovrascrive l'impostazione del server per fornire un livello base di segnalazione.
  - *Massimo* Sovrascrive l'impostazione del server per consentire la segnalazione di tutti
    gli errori. Se il tuo sito Joomla non funziona a tal punto che non è
    possibile utilizzare la pagina dell'amministratore per attivare la segnalazione errori,
    puoi attivare la segnalazione errori completa modificando il
    file `configuration.php`. Impostare `$error_reporting = 'maximum' è l'equivalente di
    impostare *Segnalazione errori* su *Massimo*.
- **Forza HTTPS** Forza l'accesso al sito nelle aree selezionate a utilizzare solo
  HTTPS (connessioni HTTP crittografate con il prefisso https://) e impone anche l'uso di cookie sicuri. Nota, è necessario avere
  HTTPS abilitato sul server per utilizzare questa opzione.

#### Pannello Posizione

- **Fuso orario del sito web** Scegli una città dall'elenco per configurare la data
  e l'ora da visualizzare.

#### Pannello Servizi web

- **Abilita CORS** Cross-Origin Resource Sharing o
  [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) 
  consente agli script che girano nel browser di interagire con risorse di una 
  diversa origine.
  - **Access-Control-Allow-Origin** Specifica l'origine consentita
    per accedere ai servizi web su questo sito, inviato in risposta a una
    richiesta preliminare. Predefinito: `*` (=tutti).
  - **Access-Control-Allow-Headers** Specifica l'intestazione(i) inviate in risposta
    a una richiesta preliminare. Predefinito: `Content-Type,X-Joomla-Token`.
  - **Access-Control-Allow-Methods** Specifica il metodo/i del servizio web
    consentito per l'accesso su questo sito, inviato in risposta a una
    richiesta preliminare. Predefinito: tutti i metodi disponibili per la rotta richiesta.

#### Pannello Proxy

- **Dietro bilanciatore di carico** Se il tuo sito è dietro un bilanciatore di carico o
  proxy inverso, abilita questa impostazione affinché gli indirizzi IP e altre
  configurazioni all'interno di Joomla ne tengano automaticamente conto.
- **Abilita proxy in uscita** Alcuni host non consentono alcun accesso alla rete
  dal tuo sito al mondo esterno per impostazione predefinita e richiedono di
  configurare manualmente un proxy in uscita.
  - **Host proxy in uscita** Nome host (dominio) o indirizzo IP.
  - **Porta proxy in uscita**
  - **Nome utente proxy in uscita** Lascia vuoto se il tuo proxy in uscita non
    richiede autenticazione.
  - **Password proxy in uscita**

#### Pannello Database

- **Tipo di database** Il tipo di database in uso, selezionato durante il
  processo di installazione. Non modificare questo campo se non strettamente
  necessario (ad esempio il trasferimento del database a un nuovo provider di hosting).
- **Host** Il nome host per il tuo database inserito durante il
  processo di installazione. Non modificare questo campo se non strettamente
  necessario (ad esempio il trasferimento del database a un nuovo provider di hosting).
- **Nome utente del database** Il nome utente per l'accesso al tuo database
  inserito durante il processo di installazione. Non modificare questo campo se non strettamente
  necessario (ad esempio il trasferimento del database a un nuovo provider di hosting).
- **Password del database** La password da utilizzare per accedere al
  database. Non modificare questo campo se non strettamente necessario (ad esempio
  il trasferimento del database a un nuovo provider di hosting).
- **Nome del database** Il nome per il tuo database inserito durante il
  processo di installazione. Non modificare questo campo se non strettamente
  necessario (ad esempio il trasferimento del database a un nuovo provider di hosting).
- **Prefisso delle tabelle del database** Il prefisso utilizzato per le tue tabelle del
  database, creato durante il processo di installazione. Non modificare questo campo se non strettamente
  necessario (ad esempio il trasferimento del database a un nuovo provider di hosting).
- **Crittografia della connessione**
  - Predefinito (controllato dal server)
  - Autenticazione a senso unico
    - **Verifica certificato del server**
      - **Percorso verso il file CA** Percorso del file system.
  - Autenticazione a doppio senso
    - **Percorso verso il file della chiave privata** Posizione del file system.
    - **Percorso verso il file del certificato** Posizione del file system.
    - **Verifica certificato del server**
      - **Percorso verso il file CA** Percorso del file system.
    - **Suite di cifratura supportata (opzionale)** Nessuna voce richiesta (solo
      consigliata per utenti esperti). Per maggiori dettagli, consulta la
      documentazione del tuo database.

#### Pannello Mail

- **Invia Mail**
  - *Sì* Abilita l'invio di mail.
  - *No* Disabilita l'invio di mail. Si consiglia di mettere il sito offline
    quando si disabilita la funzione mail.
- **Disabilita Mass Mail**
  - *Sì* Disabilita la funzione Mass Mail Utenti.
  - *No* Rendi attiva la funzione Mass Mail Utenti.
- **Da Email** L'indirizzo email che verrà utilizzato per inviare le email del sito.
- **Da Nome** Testo visualizzato nel campo intestazione *Da:* quando si inviano
  email del sito. Di solito il nome del sito.
- **Rispondi a Email** L'indirizzo email che verrà utilizzato per ricevere le risposte
  degli utenti finali.
- **Rispondi a Nome** Testo visualizzato nel campo intestazione *A:* quando
  gli utenti finali rispondono alle email ricevute.
- **Mailer** Seleziona quale mailer per la consegna delle email del sito.

### Scheda Registri

![scheda di configurazione globale dei registri](../../../it/images/site/global-configuration-logging-tab.png)

#### Pannello Registri

- **Percorso alla cartella di registrazione** Joomla può, facoltativamente, mantenere un file di registro delle sue
  operazioni e delle estensioni di terze parti. Fornisci il percorso assoluto
  a una cartella che è scrivibile da PHP; se manca o non è
  scrivibile Joomla non si avvierà affatto. Per motivi di sicurezza non devi
  usare una cartella con accesso a livello di sistema come `/tmp`.
- **Registra quasi tutto** Registra tutto, esclusi le API deprecate.
- **Registra API deprecate** Registra le API deprecate.

#### Pannello registrazione personalizzata

- **Priorità di registrazione** Può essere utilizzato per gestire la registrazione personalizzata. Seleziona gli
  eventi che desideri vedere nel file di registro. Il predefinito è *Tutti*. Gli elementi
  possono essere selezionati o deselezionati cliccando sulla lista a discesa.
- **Categorie di registrazione** Una lista separata

## Consigli

- La maggior parte di queste impostazioni può essere configurata una volta sola e poi lasciata invariata.
- Se devono essere apportate importanti modifiche, considera di mettere il sito offline per testarlo e assicurarti che tutto funzioni correttamente.
- Le impostazioni sono salvate nel file `configuration.php` nella directory principale del sito. Le autorizzazioni di questo file sono impostate su sola lettura (444) dopo aver effettuato modifiche tramite la pagina di Configurazione Globale e devono essere modificate a permessi di scrittura per il proprietario (644) prima di modificarlo con un editor di testo.

*Tradotto da openai.com*

