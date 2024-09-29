<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_System_Group / Display title: Gruppo del Sistema -->

## Descrizione del Gruppo

### Sistema - Funzionalità Aggiuntive di Accessibilità

Questo plugin aggiunge una toolbar di accessibilità al tuo sito con opzioni di accessibilità aggiuntive.

![Modulo delle funzionalità di accessibilità aggiuntive del sistema](../../../en/images/plugins/plugin-group-system-additional-accessibility-features.png)

### Sistema - Debug

Questo plugin fornisce informazioni di debug. Il report viene mostrato sotto la schermata principale delle interfacce frontend e backend di un'installazione di Joomla!.

#### Tab Plugin

![Modulo debug del sistema tab plugin](../../../en/images/plugins/plugin-group-system-debug-plugin-tab.png)

- **Gruppi Permessi** Gruppi di utenti che vedranno le informazioni di debug quando abilitato.
- **Mostra Profiling** Se visualizzare o meno le informazioni sui waypoint di profiling.
- **Mostra Query** Se includere o meno il log delle query SQL nelle informazioni di debug.
- **Mostra Utilizzo Memoria** Se includere o meno i dati di utilizzo della memoria nelle informazioni di debug.

#### Tab Lingua

![Modulo debug del sistema tab lingua](../../../en/images/plugins/plugin-group-system-debug-language-tab.png)

- **Mostra errori durante l'analisi dei file di lingua** Se visualizzare o meno un elenco di file di lingua con errori dovuti alla non conformità con la specifica dei file di lingua di Joomla!.
- **Mostra File di Lingua** Se visualizzare o meno i file di lingua che sono stati caricati per generare la pagina.
- **Mostra Stringa di Lingua** Se includere o meno stringhe di lingua non definite nelle informazioni di debug.
- **Rimuovi Prima Parola** Se sempre rimuovere la prima parola nelle stringhe a più parole.
- **Rimuovi Dall'Inizio** Rimuove le parole specificate dall'inizio della stringa di lingua. Per più parole separare ogni parola con il carattere pipe ( | ) come segue: parola1|parola2
- **Rimuovi Dalla Fine** Rimuove le parole specificate dalla fine della stringa di lingua. Per più parole separare ogni parola con il carattere pipe ( | ) come segue: parola1|parola2

#### Tab Registrazione

![Modulo debug del sistema tab registrazione](../../../en/images/plugins/plugin-group-system-debug-logging-tab.png)

### Sistema - Campi

Il plugin dei campi di sistema richiesto per mostrare i campi personalizzati.

### Sistema - Intestazioni HTTP

Questo plugin può impostare le intestazioni di sicurezza HTTP. Si prega di consultare la documentazione sulla gestione delle intestazioni HTTP per maggiori dettagli su questo plugin.

![Modulo intestazioni HTTP del sistema](../../../en/images/plugins/plugin-group-system-http-headers.png)

### Sistema - Evidenzia

Plugin di sistema per evidenziare termini specificati.

### Sistema - Schedulatore di Lavori

Questo plugin cerca compiti dei plugin di lavoro da eseguire.

![Modulo schedulatore di lavoro del sistema](../../../en/images/plugins/plugin-group-system-job-scheduler.png)

- **Frequenza (in minuti)** Impostare a zero per eseguire ad ogni caricamento della pagina (per test).
- **Webcron** Imposta su Sì per chiamare come comando CLI. Per maggiori informazioni vedere Scrivere Un'Applicazione CLI.
- **Chiave di Attivazione** La chiave da passare in un comando Webcron.

### Sistema - Statistiche di Joomla!

![Modulo statistiche di Joomla! del sistema](../../../en/images/plugins/plugin-group-system-joomla-statistics.png)

- **ID Unico** Un identificatore che consente al progetto Joomla! di contare le installazioni uniche del plugin. Questo viene inviato con le statistiche al server.
- **Intervallo (ore)** Le statistiche verranno inviate ogni X ore. Il valore predefinito è 12.
- **Modalità** Seleziona il modo in cui vuoi che le statistiche siano inviate.

### Sistema - Notifica di Aggiornamento di Joomla!

![Modulo notifica di aggiornamento di Joomla! del sistema](../../../en/images/plugins/plugin-group-system-joomla-update-notification.png)

- **Email Super Utente** Un elenco separato da virgola degli indirizzi email che riceveranno le email di notifica di aggiornamento. Gli indirizzi nella lista DEVONO appartenere a utenti esistenti del tuo sito che hanno il privilegio di Super Utente. Se nessuna delle email elencate appartiene ai Super Utenti, o se è lasciato vuoto, tutti i Super Utenti di questo sito riceveranno l'email di notifica di aggiornamento.
- **Lingua Email** Se scegli Auto (predefinito), l'email di notifica di aggiornamento ai Super Utenti sarà nella lingua del sito al momento in cui il plugin viene attivato. Selezionando una lingua qui stai forzando le email di notifica di aggiornamento a essere inviate in questa lingua specifica.

### Sistema - Codice Lingua

Fornisce la possibilità di cambiare il codice della lingua nel documento HTML generato per migliorare la SEO. I campi appariranno quando il plugin è abilitato e salvato. Maggiori informazioni su W3.org.

### Sistema - Filtro Lingua

![Modulo filtro lingua del sistema](../../../en/images/plugins/plugin-group-system-language-filter.png)

- **Selezione della Lingua per nuovi Visitatori** Se scegliere la lingua predefinita del sito o rilevare le impostazioni del browser automaticamente.
- **Cambio Automatico della Lingua** Questa opzione cambierà automaticamente la lingua del contenuto usata nel Frontend quando la lingua del sito dell'utente viene cambiata.
- **Associazioni** Consente l'associazione degli elementi quando si passa da una lingua all'altra.
- **Aggiungi Meta Tag Alternativi** Aggiungi meta tag alternativi per voci di menu con voci di menu associate in altre lingue.
- **Aggiungi Meta Tag x-default** Aggiungi meta tag x-default per migliorare la SEO.
- **Lingua x-default** Scegli la tua lingua x-default.
- **Rimuovi Codice Lingua URL** Se rimuovere o meno il Codice Lingua URL definito (es. your_domain_name/en) della tua Lingua di Contenuto che corrisponde alla lingua predefinita del sito quando l'URL SEF è impostato su *Sì*.
- **Durata Cookie** I cookie della lingua possono essere impostati per scadere alla fine della *Sessione* o dopo un *Anno*.

### Sistema - Rotazione dei Log

![Modulo rotazione dei log del sistema](../../../en/images/plugins/plugin-group-system-log-rotation.png)

- **Rotazione dei Log (in giorni)** Ogni quanto tempo devono essere ruotati i log.
- **Log Massimi** Il numero massimo di vecchi log da mantenere.

### Sistema - Logout

Il plugin di logout del sistema permette a Joomla di reindirizzare l'utente alla pagina principale se sceglie di disconnettersi mentre si trova su una pagina di accesso protetto.

### Sistema - Cache delle Pagine

Questo plugin abilita la cache delle pagine. La cache delle pagine permette al server web di salvare snapshot delle pagine e usarli quando si servono pagine web. Questo migliora le prestazioni del tuo sito web e riduce il carico di lavoro del server. Questo plugin ha le seguenti opzioni:

![Modulo cache delle pagine del sistema](../../../en/images/plugins/plugin-group-system-page-cache.png)

- **Usa Cache del Browser** Se usare o meno il meccanismo per memorizzare una cache della pagina nel browser locale. Il valore predefinito è *No*.
- **Escludi Voci di Menu** Seleziona quali voci di menu vuoi escludere dalla cache.

### Sistema - Consenso alla Privacy

Questo plugin permette di raccogliere il consenso dei tuoi utenti alla politica della privacy del sito e di gestire la scadenza del consenso.

![Modulo consenso alla privacy del sistema](../../../en/images/plugins/plugin-group-system-privacy-consent.png)

- **Breve Politica sulla Privacy** Ti consente di inserire un riassunto della tua politica sulla privacy o di mantenere quella esistente.
- **Tipo di Privacy** Scegli tra Articolo e Voce di Menu. A seconda della scelta, sarà presente uno dei due campi seguenti.
- **Articolo sulla Privacy** Seleziona o crea un articolo per la tua politica sulla privacy da collegare al modulo del tuo utente.
- **Voce di Menu sulla Privacy** Seleziona o crea una voce di menu collegata a un articolo contenente la tua politica sulla privacy.
    - *Nota:* Prestare particolare attenzione ai siti multilingua. Meglio assicurarsi che l'Articolo o la Voce di Menu siano presenti come Associazioni in tutte le lingue.
- **Messaggio di Reindirizzamento** Il messaggio che verrà mostrato sul reindirizzamento. Inserisci il tuo messaggio o mantieni quello esistente.

![Modulo consenso alla privacy del sistema scheda scadenza](../../../en/images/plugins/plugin-group-system-privacy-consent-expiration.png)

- **Abilita** (Sì/No) La scadenza è disabilitata per impostazione predefinita. Abilitala se vuoi eseguire controlli per la scadenza dei consensi alla privacy.
- **Controllo periodico (giorni)** (0 a 120 giorni) Predefinito 30 giorni. Se la scadenza è abilitata, definisci il numero di giorni per effettuare il controllo.
- **Scadenza** (180 a 720 giorni) Predefinito 360 giorni. Se la scadenza è abilitata, definisci il numero di giorni dopo i quali il consenso alla privacy scade.
- **Promemoria** (0 a 120 giorni) Predefinito 30 giorni. Se la scadenza è abilitata, definisci il numero di giorni dopo i quali deve essere inviato un promemoria prima della scadenza del consenso alla privacy.

### Sistema - Reindirizzamento

![Modulo di reindirizzamento del sistema](../../../en/images/plugins/plugin-group-system-redirect.png)

- **Raccogli URLs** Questa opzione controlla la raccolta degli URL. Questo è utile per evitare un carico inutile sul database.
- **Includi Nome Dominio negli URL Scaduti** Salva l'URL scaduto come assoluto (includendo il dominio) o relativo (escludendo il dominio).
- **Escludi URLs** Definisci espressioni regolari o termini che dovrebbero essere esclusi nel salvataggio.

### Sistema - Ricordami

Questo plugin fornisce la funzionalità *Ricordami*. Questo permette al sito web di *ricordare* il tuo nome utente e password in modo che tu possa essere automaticamente collegato quando torni al sito. Questo plugin non ha opzioni.

### Sistema - SEF

Questo plugin aggiunge il supporto SEF ai collegamenti nel documento. Opera direttamente sull'HTML e non richiede un tag speciale. Ha le seguenti opzioni:

![Modulo SEF del sistema](../../../en/images/plugins/plugin-group-system-sef.png)

- **Dominio del Sito** Se il tuo sito è accessibile tramite più di un dominio, inserisci qui il dominio preferito (a volte indicato come canonico). Nota: https://example.com e https://www.example.com sono domini diversi.

### Sistema - Pulizia dei Dati di Sessione

![Modulo pulizia dei dati di sessione del sistema](../../../en/images/plugins/plugin-group-system-session-data-purge.png)

- **Abilita Pulizia Dati di Sessione** Quando abilitato, questo plugin tenterà di eliminare i dati scaduti basati sulla frequenza calcolata dalla probabilità e divisore.
- **Abilita Pulizia Metadata di Sessione** Quando abilitato, questo plugin pulirà i metadata opzionali della sessione dal database. Nota che questa operazione non verrà eseguita quando è in uso il gestore del database poiché quei dati vengono cancellati come parte dell'operazione di Pulizia dei Dati di Sessione.
- **Probabilità** In combinazione con il campo divisore, questi due campi sono usati per determinare la frequenza dell'operazione di pulizia dei dati della sessione che viene attivata su una richiesta.
- **Divisore** In combinazione con il campo probabilità, questi due campi sono usati per determinare la frequenza dell'operazione di pulizia dei dati della sessione che viene attivata su una richiesta. La probabilità viene calcolata usando probabilità/divisore, es. 1/100 significa che c'è una probabilità dell'1% che il processo venga eseguito su ogni richiesta.

### Sistema - Salta alla Navigazione

Il plugin crea un menu a discesa costituito dai link ai luoghi importanti su una determinata pagina web. Questo rende più facile per gli utenti del tastiera e dei lettori di schermo saltare rapidamente alla posizione desiderata scegliendola dall'elenco delle opzioni.

![Modulo salta alla navigazione del sistema](../../../en/images/plugins/plugin-group-system-skip-to-navigation.png)

### Sistema - Registro delle Azioni degli Utenti

![Modulo registro delle azioni degli utenti del sistema](../../../en/images/plugins/plugin-group-system-user-actions-log.png)

- **Giorni per eliminare i log dopo** Inserisci quanti giorni i log devono essere mantenuti prima di essere eliminati. Inserisci 0 se non vuoi eliminare i log.

### Sistema - Registro Utenti

![Modulo registro utenti del sistema](../../../en/images/plugins/plugin-group-system-user-log.png)

- **Registra Nomi Utente** Questa opzione registrerà il nome utente utilizzato quando un'autenticazione fallisce.

*Tradotto da openai.com*


