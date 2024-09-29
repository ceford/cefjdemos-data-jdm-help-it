<!-- Filename: Help4.x:Edit_Permissions / Display title: Modifica Permessi -->

## Scopo

Molte estensioni hanno schermate di modifica con una scheda Permessi che viene utilizzata per cambiare
i permessi assegnati ai Gruppi Utenti. Il numero di Gruppi Utenti può variare
poiché è possibile aggiungere Gruppi Utenti personalizzati per scopi speciali. Il
numero di Azioni che possono essere modificate varia anche in base all'estensione. Questo articolo
è una breve descrizione delle schermate permessi per tali scopi
speciali.

Immagina di avere un utente che si occupa dei Media (immagini e file) ma
a cui non sono consentite altre responsabilità. Un gruppo denominato Oddjob è stato
creato e assegnato al livello di accesso Speciale. Un utente denominato anche Oddjob è stato
creato e assegnato al gruppo Oddjob.

Per informazioni più dettagliate sui Gruppi Utenti, i Livelli di Accesso e i Permessi
c'è un tutorial separato sul [Controllo degli Accessi](jdocmanual?article=user/users/access-control).

## Autorizzazioni di Configurazione Globale

In questo esempio, agli utenti del gruppo Oddjob è stata assegnata
l'autorizzazione globale per accedere all'interfaccia Amministratore, ma nient'altro.

![Schermata delle Autorizzazioni](../../../it/images/common-elements/global-configuration-permissions-tab.png)

## Permessi di Configurazione del Componente

Per accedere a un componente specifico, i permessi devono essere impostati nelle opzioni del componente.
In questo esempio, le opzioni del componente Media.

![Screenshot dei Media](../../../it/images/common-elements/media-options-permissions-tab.png)

Noterai che questo componente ha meno Azioni disponibili e al gruppo Oddjob
sono concessi solo i permessi necessari per svolgere il lavoro.

Per modificare i permessi per questo componente:

* Seleziona il Gruppo cliccando sul suo titolo situato a sinistra.<br>
    Trova l'Azione desiderata.
    * Elimina. Gli utenti possono eliminare questo articolo.
    * Modifica. Gli utenti possono modificare questo articolo.
    * Modifica Stato. Gli utenti possono cambiare lo stato di pubblicazione e le informazioni correlate per questo articolo.
* Seleziona il permesso desiderato per l'azione che desideri modificare.
    * Ereditato. Ereditato per gli utenti di questo Gruppo dalla Configurazione Globale, Opzioni Articoli, o Categoria Articoli.
    * Consentito. Consentito per gli utenti di questo Gruppo. Nota: Se questa azione è Negata a uno dei livelli superiori, il permesso Consentito qui non avrà effetto. Un'impostazione Negata non può essere sostituita.
    * Negato. Negato per gli utenti di questo Gruppo.
* Clicca su Salva nella barra degli strumenti in alto. Quando lo schermo si aggiorna, la colonna Impostazione Calcolata mostrerà il permesso effettivo per questo Gruppo e Azione.

## L'Esperienza Utente

Dopo il login, un utente nel gruppo Oddjob vedrà i moduli del Cruscotto Home
che hanno accesso **Speciale** impostato e un link di voce di menu al componente Media.

![Cruscotto Home per Oddjob](../../../it/images/common-elements/home-dashboard-for-oddjob.png)

E la schermata Media per l'utente Oddjob è come previsto:

![Schermata Media per Oddjob](../../../it/images/common-elements/media-screen-for-oddjob.png)

*Tradotto da openai.com*

