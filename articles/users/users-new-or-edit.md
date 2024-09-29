<!-- Filename: Help4.x:Users:_Edit_Profile / Display title: Utenti: Nuovo o Modifica -->

## Descrizione

La pagina *Utenti: Nuovo o Modifica* viene utilizzata per creare un nuovo utente o modificare un utente esistente.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).

## Come accedere

Per modificare un utente esistente:

- Seleziona **Utenti → Gestisci** dal menu dell'Amministratore. Poi...
  - Cerca l'utente richiesto e seleziona il link del nome nella
    colonna **Nome**.

Per creare un nuovo utente:

- Seleziona **Utenti → Gestisci** dal menu dell'Amministratore. Poi...
  - Seleziona il pulsante **Nuovo** nella Barra degli Strumenti.
- Oppure... Seleziona **Utenti → Gestisci → Icona Plus** dal
  menu dell'Amministratore.
- Oppure... Seleziona **Utenti → Icona Dashboard** dal menu
  dell'Amministratore. Poi...
  - Seleziona l'icona **Plus** dal pannello Utenti.
- Oppure... Seleziona **Dashboard Home → Pannello Sito → Icona Plus Utenti**
  a partire dal menu dell'Amministratore.

## Schermata

![modifica dettagli utente tab](../../../it/images/users/users-edit-account-details-tab.png)

## Campi del Modulo

### Dettagli Account

- **Nome** Inserisci il nome dell'utente.
- **Nome di Accesso** Inserisci il nome di accesso (Username) per l'utente.
- **Password** Compila una (nuova) password. Anche se questo campo non è obbligatorio, l'utente non potrà accedere se non viene impostata una password.
- **Conferma Password** Compila nuovamente la password dal campo sopra, per verificarla. Questo campo è obbligatorio quando si è compilato il campo Nuova password.
- **Email** Inserisci un indirizzo email per l'utente.
- **Data di Registrazione** Data di registrazione dell'utente.
- **Data Ultima Visita** Data dell'ultima visita dell'utente sul sito.
- **Data Ultimo Reset** Data e ora dell'ultimo reset della password.
- **Conteggio Reset Password** Numero di reset della password dall'ultima volta che è stata reimpostata.
- **Ricevere Email di Sistema** (*Sì*/*No*) Se impostato su sì, l'utente riceverà email di sistema.
- **Stato Utente** (*Bloccato*/*Abilitato*) Abilita o blocca questo utente.
- **Richiedi Reset Password** (*Sì*/*No*) Se impostato su sì, l'utente dovrà reimpostare la password la prossima volta che accederà al sito.
- **ID** Numero di registrazione nel database.

### Scheda Gruppi di Utenti Assegnati

![scheda gruppi di utenti assegnati](../../../it/images/users/users-edit-assigned-user-groups-tab.png)

Il predefinito è *Registrato* ma può essere modificato nella pagina *Utente: Opzioni*.

### Impostazioni di Base

![scheda impostazioni di base](../../../it/images/users/users-edit-basic-settings-tab.png)

- **Stile del Template Backend** Seleziona uno stile del template per l'interfaccia Backend dell'Amministratore. Questo influirà solo su questo utente.
- **Lingua del Backend** Seleziona la lingua per l'interfaccia Backend dell'Amministratore. Questo influirà solo su questo utente.
- **Lingua del Frontend** Seleziona la lingua per l'interfaccia frontend. Questo influirà solo su questo utente.
- **Editor** Seleziona un Editor per questo utente. Il predefinito è TinyMCE a meno che non sia stato modificato nelle Configurazioni Globali. 
- **Fuso Orario** C'è una lunga lista di fusi orari tra cui scegliere, organizzati per continente con l'Europa verso la fine. Il fuso orario predefinito del sito è impostato nelle Configurazioni Globali.

### Impostazioni di Accessibilità

![scheda impostazioni di accessibilità](../../../it/images/users/users-edit-accessibility-settings-tab.png)

- **Monocromo** Sì/No
- **Alto Contrasto** Sì/No
- **Evidenzia Link** Sì/No
- **Aumenta Dimensione Font** Sì/No

### Opzioni del Registro Azioni Utente

Questa scheda è disponibile solo per i Super Utenti!

- **Invia notifiche per il Registro Azioni Utente** Se impostato su sì, l'utente riceverà notifiche del registro azioni utente via email.
- **Seleziona eventi per cui essere notificato** Seleziona le notifiche del registro azioni utente che verranno inviate via email.

### Autenticazione Web W3C (WebAuthn) per Accesso

Questa scheda è presente solo quando il sito è accessibile tramite https. Per impostare l'accesso senza password, hai bisogno di un dispositivo hardware, disponibile su Amazon e simili per circa £15, o un dispositivo con riconoscimento delle impronte digitali o riconoscimento facciale o software biometrico simile. Puoi aggiungere più di un autenticatore. Una volta impostato, puoi fare login cliccando sul pulsante Autenticazione Web nel modulo di accesso e poi premere il pulsante sul dispositivo quando richiesto.

Questa scheda è presente ma non può essere utilizzata nel modulo di modifica dell'utente perché l'accesso senza password può essere impostato solo dall'utente individuale tramite il modulo Modifica Profilo.

### Token API Joomla

Questa scheda viene utilizzata per gestire i token di sicurezza utilizzati per autenticarsi all'applicazione API Joomla (accesso remoto al tuo sito). Se non sei sicuro di cosa faccia, probabilmente non ne hai bisogno e puoi ignorare queste impostazioni in sicurezza.

Il token è visibile solo per il proprio account.

### Autenticazione Multi-fattore

![scheda autenticazione multi-fattore](../../../it/images/users/users-edit-multi-factor-authentication-tab.png)

Questa scheda consente di impostare uno o più metodi per consentire l'accesso al proprio account dopo aver effettuato il login con Username e Password. È presente solo quando si modifica il proprio profilo. Sono disponibili diversi metodi. Se si perde l'accesso a un metodo per qualsiasi motivo, è possibile scegliere un altro metodo dalla schermata di verifica post-login. I metodi alternativi devono essere stati impostati in anticipo!

#### Codici di Backup

Questo metodo genera un set di numeri che puoi salvare o stampare. Ogni numero può essere utilizzato solo una volta, quindi ricordati di aggiornare la lista dopo l'uso.

#### Codice di Verifica

Un modulo aggiuntivo da compilare con metodi alternativi per impostare il codice. Dare un'occhiata e cliccare sul pulsante Annulla se si decide di non procedere.

#### Chiave Yubi

Questo è per un altro tipo di chiave hardware che fornisce un codice su un display. Dare un'occhiata e selezionare Annulla se si decide di non procedere.

#### Autenticazione Web

Per un dispositivo hardware con un pulsante da premere. Dare un'occhiata e selezionare Annulla se si decide di non procedere. Nota che questo metodo sarà bypassato se si utilizza il metodo di Login WebAuthn separato.

#### Codice via Email

Con questo metodo un codice viene inviato al tuo indirizzo email. Ti verrà chiesto di inserire quel codice per accedere al sito. È un codice una tantum. Un nuovo codice viene inviato per ogni accesso. Dare un'occhiata e selezionare Annulla se si decide di non procedere.

## Suggerimenti

- Nome, Nome di accesso ed Email sono obbligatori.
- Se non hai compilato una particolare lingua, editor, sito di supporto e/o
  fuso orario, vengono utilizzate le impostazioni predefinite dalla Configurazione globale,
  Gestore delle lingue e/o Gestore dei modelli.

*Tradotto da openai.com*

