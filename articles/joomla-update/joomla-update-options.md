<!--
{
    "source": "https://docs.joomla.org/Help4.x:Joomla_Update:_Options",
    "title": "Aggiornamento di Joomla: opzioni",
    "description": " ",
    "author": ""
}
-->

## Descrizione

La pagina Aggiornamento di Joomla: opzioni viene utilizzata per impostare i parametri che controllano il processo di aggiornamento del 
core di Joomla.

### Elementi comuni

Alcuni aspetti di questa pagina sono trattati in articoli della Guida separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars)

## Come accedere

- Seleziona **Sistema → Pannello di aggiornamento → Joomla** dal menu Amministratore. Quindi...
  - Seleziona il pulsante **Opzioni** nella barra degli strumenti.

## Schermata

![Origine dell'aggiornamento nelle opzioni di aggiornamento di Joomla](../../../it/images/joomla-update/joomla-update-options/01-update-source.png)

## Campi del modulo

### Scheda Origine dell'aggiornamento

- **Canale di aggiornamento**
  - **Predefinito** Questa impostazione fa sì che Joomla visualizzi una notifica quando è disponibile una nuova versione 
  minor o patch per la versione principale corrente. 
  - **Joomla Next** Questa impostazione fa sì che Joomla visualizzi una notifica quando è disponibile una 
  nuova versione principale stabile e tutte le versioni minor e le estensioni esistenti sono aggiornate.
  - **URL personalizzato** Per gli sviluppatori di Joomla. Verranno visualizzati altri campi.
- **Stabilità minima** Il livello minimo di stabilità degli aggiornamenti delle estensioni che desideri visualizzare. Development è il livello meno stabile, mentre Stable è di qualità di produzione. Se un'estensione non specifica un livello, viene considerata Stable.
  - **Development** Per i siti degli sviluppatori di Joomla.
  - **Alpha** Per i siti di test Alpha.
  - **Beta** Per i siti di test Beta.
  - **Release Candidate** Per i siti di test Release Candidate.
  - **Stable** Per i siti di produzione.
- **URL personalizzato** Se nel Canale di aggiornamento è stato selezionato un URL personalizzato, qui viene visualizzato un campo per inserire l'URL.
- **Casella di controllo delle estensioni potenzialmente incompatibili** Mostra la casella di controllo nel 
  controllo preliminare all'aggiornamento se una delle estensioni installate sul sito è 
  potenzialmente incompatibile con la versione di Joomla a cui stai effettuando l'aggiornamento. 
  *Nota:* la casella di controllo viene visualizzata quando si esegue l'aggiornamento a una nuova famiglia di versioni di Joomla (versione minor o principale).
- **Casella di controllo Conferma backup** Mostra la casella di controllo per confermare che hai eseguito 
  un backup e che sei pronto per l'aggiornamento nell'ultimo passaggio prima che l'aggiornamento venga 
  effettivamente applicato. 

### Scheda Aggiornamenti automatici

*Gli aggiornamenti automatici sono disponibili a partire da Joomla 5.4 per i siti pubblicamente accessibili su Internet. Se il sito si trova dietro un firewall o non è pubblicamente accessibile, ad esempio in un ambiente di test locale, dovrai eseguire l'aggiornamento manualmente.*

![Origine dell'aggiornamento nelle opzioni di aggiornamento di Joomla](../../../it/images/joomla-update/joomla-update-options/02-automated-updates.png)

- **Aggiornamento automatico** Se impostato su *Sì*, il sito verrà aggiornato automaticamente all'ultima versione minor o patch (incluse le patch di sicurezza) non appena sarà disponibile. Le versioni principali non sono incluse.
- **Token di aggiornamento** È un token che identifica questo sito. Viene creato dal server remoto degli aggiornamenti di Joomla e non può essere modificato dall'utente.
- **Ultimo controllo** La data più recente in cui il sito ha contattato il server degli aggiornamenti.
- **Invia email ai gruppi di utenti** Tutti gli utenti dei gruppi selezionati riceveranno email sugli aggiornamenti automatici completati o non riusciti. Se non vengono trovati utenti, le email vengono inviate a tutti i Super User. I destinatari devono avere abilitata l'opzione Ricevi email di sistema.

Per maggiori dettagli, usa il pulsante *Attiva/disattiva guida in linea*.

*Tradotto da openai.com*