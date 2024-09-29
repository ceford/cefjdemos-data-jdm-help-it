<!-- Filename: Help4.x:Users:_Groups / Display title: Utenti: Gruppi -->

## Descrizione

I Gruppi di Utenti controllano quali azioni un utente può eseguire su un sito. Le azioni includono cose come visualizzare un articolo, creare un articolo, cambiare opzioni per un componente o accedere. L'amministratore del sito assegna le autorizzazioni per varie azioni a ciascun gruppo. Le autorizzazioni per le azioni possono essere assegnate in diverse posizioni nella gerarchia dei componenti, ad esempio nella Configurazione Globale, nelle opzioni del componente o nelle opzioni del modulo. Se un gruppo di utenti non ha l'autorizzazione per una determinata azione, l'utente in quel gruppo non può eseguire quell'azione.

Il controllo dell'accesso alla visualizzazione è implementato tramite l'uso dei **Livelli di Accesso**, ai quali sono assegnati uno o più gruppi di utenti. Risorse come articoli, voci di menu o moduli sono assegnate a un livello di accesso. Un utente che è membro di un gruppo assegnato a un livello di accesso specifico può visualizzare qualsiasi risorsa assegnata a quel livello di accesso.

I gruppi di utenti possono essere organizzati in una gerarchia in cui tutti i gruppi figli ereditano le autorizzazioni per le azioni e i livelli di accesso di un gruppo genitore. Se usata con saggezza, questa funzione può risparmiare molto tempo evitando duplicazioni nella configurazione di un sistema di sicurezza del sito.

La pagina *Utenti: Gruppi* elenca i Gruppi di Utenti attuali in gerarchia. Può essere utilizzata per creare nuovi gruppi di utenti e eliminare gruppi che non sono più necessari. Non eliminare nessuno dei gruppi di utenti predefiniti!

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di Aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri Lista](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni delle Colonne della Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginazione della Lista](jdocmanual?article=help/common-elements/list-pagination).

## Come accedere

- Seleziona **Utenti → Gruppi** dal menu dell'Amministratore.

## Screenshot

![gruppi di utenti](../../../it/images/users/users-groups-list.png)

## Suggerimenti

- Seleziona il nome di un gruppo per modificare le proprietà del gruppo.
- Seleziona l'icona delle autorizzazioni per esaminare le autorizzazioni del gruppo per l'accesso a ciascuna risorsa. Questo è spesso usato per eseguire il debug dei problemi di autorizzazione di accesso.
- Seleziona il numero di utenti abilitati per vedere un elenco di utenti abilitati in quel gruppo.
- Seleziona il numero di utenti bloccati per vedere un elenco di utenti bloccati in quel gruppo.

*Tradotto da openai.com*

