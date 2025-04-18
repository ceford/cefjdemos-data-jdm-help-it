<!-- Filename: Help5.x:Scheduled_Tasks / Display title: Attività pianificate -->

## Descrizione

Le attività pianificate vengono utilizzate per eseguire routine di manutenzione del sito come alternativa ai cron job del server. Le attività sono definite nei plugin nel gruppo di attività. Un certo numero di plugin di attività sono forniti e possono essere utilizzati come esempi per creare altre attività specializzate.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri elenco](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni delle colonne dell'elenco](jdocmanual?article=help/common-elements/list-column-headers).
* [Paginazione dell'elenco](jdocmanual?article=help/common-elements/list-pagination).

## Come Accedere

A partire dal menu Amministratore:

- Seleziona **Sistema → Pannello di gestione → Attività pianificate**

L'elenco iniziale delle Attività Pianificate contiene tre elementi.

## Schermata

![scheduled tasks list](../../../it/images/maintenance/scheduled-tasks-list.png)

## Intestazioni di colonna

Colonne uniche per attività programmate:

- **Tipo di Attività** Le attività sono create da un elenco disponibile di tipi.
- **Data Ultima Esecuzione** La data e l'ora dell'ultima esecuzione dell'attività.
- **Data Prossima Esecuzione** La data e l'ora della prossima esecuzione dell'attività.
- **Test Attività** Un pulsante per eseguire l'attività manualmente.
- **Priorità Attività** La priorità può essere Bassa, Normale o Alta. Le attività ad alta priorità possono potenzialmente bloccare quelle a priorità più bassa.

## Cronologia dell'Esecuzione

Seleziona il pulsante nella barra degli strumenti per vedere un elenco di esecuzioni di singoli compiti.

![task execution history list](../../../it/images/maintenance/scheduled-tasks-logs.png)

## Compiti Disponibili

Lo screenshot seguente mostra un elenco di attività disponibili. Alcune sono dimostrazioni, altre sono utili.

![Scheduled Tasks Available](../../../it/images/maintenance/scheduled-tasks-types.png)

Ogni attività ha i propri parametri correlati che dovrebbero essere autoesplicativi. Ad esempio, l'attività **Sito Offline** ha senso solo se la **Modifica Attività → Campi di Base → Regola di Esecuzione** è impostata su **Esecuzione Manuale**.

## Opzioni delle attività programmate

Seleziona il pulsante Opzioni nella barra degli strumenti per configurare le attività pianificate.

### Configurare la scheda Attività

![task timeout setting](../../../it/images/maintenance/scheduled-tasks-options-configure-tasks.png)

- **Timeout dell'attività** Il valore predefinito è di 300 secondi.

### Scheda Programmatore Pigro

![lazy schedule setting](../../../it/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- I compiti **abilitati** vengono attivati dai visitatori del sito.
- I compiti **disabilitati** devono essere attivati da un cron job esterno.
- **Intervallo di richiesta** Il valore predefinito è 300 secondi.

### Tabella Cron Web

![web cron setting](../../../it/images/maintenance/scheduled-tasks-options-lazy-scheduler.png)

- **Web Cron** Disabilitato è l'impostazione predefinita. Abilitato richiede un hash per avviare il compito. Prima del primo salvataggio c'è un messaggio che indica che è necessaria una chiave. Dopo il salvataggio c'è un campo contenente un URL di collegamento Webcron da copiare.

*Tradotto da openai.com*

