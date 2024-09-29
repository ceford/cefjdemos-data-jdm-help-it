<!-- Filename: Help4.x:Permissions_for_Group / Display title: Permessi per il Gruppo -->

## Descrizione

La pagina *Autorizzazioni per Gruppo* mostra un report delle autorizzazioni indicando le autorizzazioni esatte per qualsiasi gruppo di utenti rispetto a tutte le risorse del sito. È utile per il debug dei problemi di accesso degli utenti.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri della Lista](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni delle Colonne della Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginazione della Lista](jdocmanual?article=help/common-elements/list-pagination).

## Come accedere

- Seleziona **Utenti → Gruppi** dal menu Amministratore. Poi...
  - Seleziona l'icona **Autorizzazioni** per un gruppo specifico dall'elenco
    dei gruppi utenti.

## Screenshot

![permessi utenti per gruppo](../../../it/images/users/users-permissions-for-group.png)

Sopra la tabella dei Permessi ci sono elementi selezionati che mostrano i permessi di accesso
usando icone per *Consentito*, *Non Consentito* e *Vietato*. La legenda delle icone è sotto
la tabella.

- **Login del Sito** Gli utenti del gruppo possono effettuare il login al Frontend del sito.
- **Login dell'Amministratore** Gli utenti del gruppo possono effettuare il login al Backend del sito.
- **Login ai Servizi Web** Gli utenti del gruppo possono accedere all'API dei Servizi Web di Joomla
  tramite un Token API di Super Utente.
- **Accesso Offline** Gli utenti del gruppo possono accedere al Frontend del sito quando è
  offline.
- **Super Utente** Gli utenti del gruppo possono eseguire qualsiasi azione su
  tutto il sito indipendentemente da qualsiasi altra impostazione di permesso.

### Intestazioni delle Colonne

Nella tabella contenente le risorse del sito sono mostrati i permessi per il gruppo selezionato.

- **Titolo della Risorsa** Il nome della risorsa in linguaggio semplice.
- **Nome della Risorsa** Il nome interno della risorsa.
- **Configurare Opzioni** Gli utenti del gruppo possono modificare le
  opzioni (eccetto i permessi) di questa risorsa.
- **Accedere all'Interfaccia di Amministrazione** Gli utenti del gruppo possono accedere
  all'interfaccia di amministrazione della risorsa.
- **Crea** Gli utenti del gruppo possono creare contenuti nella risorsa.
- **Elimina** Gli utenti del gruppo possono eliminare contenuti nella risorsa.
- **Modifica** Gli utenti del gruppo possono modificare contenuti nella risorsa.
- **Modifica Stato** Gli utenti del gruppo possono modificare lo stato della risorsa.
- **Modifica Proprie** Gli utenti del gruppo possono modificare qualsiasi contenuto di loro proprietà nella risorsa.
- **Modifica Valore Campo Personalizzato** Gli utenti del gruppo possono modificare qualsiasi
  valore del campo personalizzato nella risorsa.
- **LFT** I valori a sinistra e a destra nella gerarchia di nidificazione. Questo è usato
  per l'annidamento e l'ordinamento delle risorse.
- **ID** Questo è un numero identificativo unico per questo elemento assegnato
  automaticamente da Joomla. Viene utilizzato per identificare l'elemento internamente
  e non può essere modificato.

*Tradotto da openai.com*

