<!-- Filename: Help4.x:Users:_Options / Display title: Utenti: Opzioni -->

## Descrizione

La pagina *Utenti: Opzioni* viene utilizzata per impostare opzioni globali per tutti gli utenti, 
inclusi:

- Captcha,
- registrazione consentita e tipo di registrazione,
- gruppo utente predefinito per i nuovi utenti,
- reimpostazione del contatore di password o nome utente,
- notifica via email di nuova registrazione utente all'amministrazione e altro ancora.

## Come Accedere

* Seleziona **Sito → Utenti** dalla *Dashboard principale*. Oppure...
* Seleziona **Utenti → Gestisci** dal menu dell'Amministratore. Poi...
* Seleziona il pulsante **Opzioni** dalla barra degli strumenti

## Schermata

![opzioni utenti scheda opzioni utenti](../../../it/images/users/users-options-user-options-tab.png)

## Campi del modulo

### Scheda delle opzioni utente

- **Permetti registrazione utente**
  - *Sì* Gli utenti possono registrarsi dal frontend del sito utilizzando il link 
    *Crea un Account* presente nel modulo di accesso.
  - *No* Il link *Crea un Account* non sarà mostrato.
- **Nuovo gruppo di registrazione utenti** Il gruppo a cui gli utenti vengono assegnati
  di default quando si registrano sul sito. Predefinito su *Registrati*.
- **Gruppo utenti ospiti** Il gruppo a cui vengono assegnati i visitatori (Gli ospiti
  sono visitatori del sito che non sono loggati). È possibile
  creare contenuti sul sito visibili agli ospiti ma non visibili
  agli utenti registrati.
- **Invia password** Se impostato su *Sì*, la prima password dell'utente verrà
  inviata via email come parte della mail di registrazione.
- **Attivazione nuovo account utente**
  - *Nessuno* L'account dell'utente sarà attivo immediatamente senza azioni richieste.
  - *Self* L'utente riceverà un'e-mail con un link di attivazione. L'account sarà attivato 
    quando l'utente selezionerà il link di attivazione.
  - *Amministratore* L'utente riceverà un'e-mail con un link di attivazione.
    Quando l'utente selezionerà questo link, l'amministratore del sito sarà notificato 
    via email e gli sarà richiesto di attivare l'account dell'utente.
- **Invia email agli amministratori** Invia notifica via email agli
  amministratori con *Nuova attivazione account utente* impostato su *Nessuno* o *Self*.
- **Captcha** Il plugin Captcha per la registrazione dell'account utente, 
  il promemoria della password utente e il promemoria del nome utente.
- **Parametri utente frontend**
  - *Mostra* Gli utenti potranno modificare le impostazioni di base dal frontend del sito.
  - *Nascondi* Gli utenti non potranno modificare queste impostazioni.
- **Lingua frontend** Mostra o nascondi la lingua del sito...
- **Cambia nome utente** Permetti all'utente di cambiare il nome utente.

### Scheda delle opzioni del dominio email

![scheda opzioni utente domini email](../../../it/images/users/users-options-email-domain-options-tab.png)

- **Nome del dominio** Inserisci un elenco di domini email consentiti e non consentiti.
  Di default, tutti i domini sono consentiti. I caratteri jolly (\*) sono supportati. Per esempio:
  - \* (Asterisco): Consente o non consente tutti i domini
  - \*.com: Consente o non consente tutti i domini ‘.com’
  - \*.joomla.org: Consente o non consente tutti i sottodomini 'joomla.org'.
- **Regola** Seleziona se consentire o non consentire il dominio.

### Scheda delle opzioni della password

![scheda opzioni password](../../../it/images/users/users-options-password-options-tab.png)

- **Numero massimo di reset** Il numero massimo di reset della password consentiti
  nel periodo di tempo. Zero indica nessun limite.
- **Tempo di reset** Il periodo di tempo, in ore, per il contatore di reset.
- **Lunghezza minima** Imposta la lunghezza minima della password.
- **Interi minimi** Imposta il numero minimo di cifre che devono essere
  incluse in una password.
- **Simboli minimi** Imposta il numero minimo di simboli (come !@#\$
  richiesti in una password.
- **Lettere maiuscole minime** Imposta il numero minimo di caratteri alfabetici maiuscoli richiesti per una password.
- **Lettere minuscole minime** Imposta il numero minimo di caratteri alfabetici minuscoli richiesti per una password.

### Scheda dell'autenticazione multi-fattore

![scheda autenticazione multi-fattore](../../../it/images/users/users-options-multi-factor-authentication-tab.png)

- **Posizioni dei moduli frontend consentite** Quando si visualizza la pagina di autenticazione 
  multi-fattore del frontend tutti i moduli saranno nascosti eccetto quelli nelle posizioni 
  selezionate qui.
- **Mostra titolo nel frontend** Mostra un titolo nella pagina di verifica dell'autenticazione 
  multi-fattore del frontend? Si noti che il titolo è sempre mostrato nel backend. Se hai bisogno 
  di cambiare il titolo, sovrascrivi la chiave della lingua `COM_USERS_HEADING_MFA` utilizzando 
  la funzione Lingue: Sovrascritture.
- **Posizioni dei moduli backend consentite** Quando si visualizza la pagina di autenticazione 
  multi-fattore del backend tutti i moduli saranno nascosti eccetto quelli nelle posizioni 
  selezionate qui. Si noti che i moduli nella posizione `title` sono sempre mostrati: questo 
  è richiesto per mostrare l'icona e il titolo della pagina del backend.
- **Disabilita l'autenticazione multi-fattore** Qualsiasi utente che appartiene a *qualsiasi* 
  dei gruppi di utenti selezionati sarà esente dall'autenticazione multi-fattore. Anche se 
  hanno configurato i metodi di autenticazione multi-fattore, non verrà loro richiesto di 
  usarli durante l'accesso, né potranno visualizzarli, rimuoverli o modificarne la configurazione.
- **Forza l'autenticazione multi-fattore** Qualsiasi utente che appartiene a *qualsiasi* 
  dei gruppi di utenti selezionati sarà tenuto ad abilitare l'autenticazione multi-fattore 
  prima di poter usare il sito.
- **Stile del modello frontend** Scegli lo stile del modello frontend da utilizzare nella 
  pagina di autenticazione multi-fattore. Seleziona *Usa predefinito* per utilizzare lo stile del 
  modello predefinito del sito.
- **Autenticazione multi-fattore dopo login silenzioso** L'utente deve passare attraverso 
  l'autenticazione multi-fattore dopo un login silenzioso? I login silenziosi sono quelli che non 
  richiedono un nome utente e una password, per esempio la funzione Ricordami, WebAuthn ecc.
- **Tipi di risposta di autenticazione del login silenzioso (per esperti)** Per esperti. Un elenco 
  separato da virgole dei tipi di risposta di autenticazione di Joomla che sono considerati login 
  silenziosi. Il predefinito è `cookie` (la funzione Ricordami) e `passwordless` (WebAuthn).
- **Onboard nuovi utenti** Se l'utente non ha ancora configurato l'autenticazione multi-fattore e 
  questa opzione è abilitata verrà reindirizzato alla pagina di configurazione dell'autenticazione 
  multi-fattore o all'URL personalizzato che hai impostato sotto. Questo è pensato per essere un 
  modo semplice per far sapere agli utenti che l'autenticazione multi-fattore è un'opzione sul tuo sito.
- **URL di reindirizzamento personalizzato** Se non è vuoto, reindirizza a questo URL invece che alla 
  pagina di configurazione dell'autenticazione multi-fattore quando l'opzione sopra è abilitata. 
  Avviso: Questo deve essere un URL all'interno del tuo sito. Non puoi effettuare l'accesso a un link 
  esterno o a un sottodominio differente.

### Scheda della cronologia delle note utente

![scheda cronologia note utente](../../../it/images/users/users-options-user-notes-history-tab.png)

- **Abilita versioni** Salva la cronologia delle versioni per le note utente.
- **Numero massimo di versioni** Il numero massimo di versioni da memorizzare per una nota 
  utente. Se una nota utente viene salvata e il numero massimo di versioni è stato raggiunto, 
  la versione più vecchia verrà eliminata automaticamente. Se impostato a 0, le versioni non verranno 
  mai eliminate automaticamente.

### Scheda degli utenti Mail di massa

![scheda utenti mail di massa](../../../it/images/users/users-options-mass-mail-users-tab.png)

- **Prefisso oggetto** Inserisci un testo opzionale da inserire automaticamente prima 
  dell'oggetto dell'e-mail di massa.
- **Suffisso corpo email** Inserisci un testo opzionale da inserire automaticamente dopo 
  il corpo dell'email (per esempio, una firma).

### Scheda dell'integrazione

![scheda integrazione](../../../it/images/users/users-options-integration-tab.png)

- **Abilita campi personalizzati** Abilita la creazione di campi personalizzati.

## Consigli

Se sei un utente principiante, mantieni i valori predefiniti qui
finché non impari di più sull'uso delle opzioni globali.

*Tradotto da openai.com*

