<!-- Filename: Help4.x:Languages:_Edit_Override / Display title: Lingue: Modifica Sostituzione -->

## Descrizione

Nel codice di Joomla, le stringhe di testo che devono apparire
nell'interfaccia utente, sia nell'interfaccia del sito che
nell'interfaccia amministrativa, sono espresse come costanti di stringa. Ad esempio, la stringa *La tua sessione è scaduta. Effettua di nuovo l'accesso.* è espressa come `JLIB_ENVIRONMENT_SESSION_EXPIRED`. La stringa di testo può essere tradotta in qualsiasi lingua. La lingua predefinita è l'inglese britannico. Ci sono migliaia di queste stringhe in un'installazione di Joomla.

Se una stringa non si adatta al tuo sito, puoi utilizzare la funzione Sovrascrittura della lingua per sostituire l'originale. La pagina *Lingue: Sovrascritture* mostra un elenco di sovrascritture esistenti, quindi è vuota inizialmente.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).

## Come Accedere

- Seleziona **Sistema → Gestione Pannello → Sovrascritture Linguistiche**. Poi...
  - Seleziona una **Lingua e Cliente** dal menu a tendina. Poi...
    - Seleziona il pulsante **Nuovo** nella Barra degli Strumenti per creare una nuova sovrascrittura.
      Oppure...
    - Seleziona il link della costante nella colonna **Costante** per modificare una sovrascrittura esistente.

## Screenshot

![Modifica Sostituzione Lingue](../../../it/images/languages/languages-edit-override.png)

## Campi del Modulo

### Pannello di Destra: Cerca il testo che vuoi cambiare

- **Cerca** Comincia da qui! È più probabile che tu conosca il Valore
  (scaduto) piuttosto che la Costante (`_EXPIRED`). In entrambi i casi, la
  ricerca è senza distinzione tra maiuscole e minuscole per la stringa parziale.
- **Testo di Ricerca** Inserisci il testo da cercare e seleziona il pulsante *Cerca*.
- **Risultati della Ricerca** Un elenco di stringhe contenenti il termine di ricerca
  appare in un pannello Risultati separato sotto il pannello di Destra. Seleziona 
  quello che stai cercando. La costante e il testo verranno copiati nel 
  *pannello di sinistra* per essere aggiornati e salvati.

### Pannello di Sinistra: Crea una Nuova Sovrascrittura o Modifica questa Sovrascrittura

- **Lingua** e **Posizione** Questi sono stati selezionati prima di aprire questo
  modulo di modifica e non possono essere cambiati.
- **Costante di Linguaggio** Questa è la stringa utilizzata nel codice dal
  sviluppatore. Se il valore non esiste nel codice, la stringa non
  verrà mai usata.
- **Testo** Qui puoi sovrascrivere il termine predefinito con le tue
  versione.
- **Per Entrambe le Posizioni** Seleziona per applicare la sovrascrittura sia al front end che
  al back end.
- **File** Questo mostra dove si trova il file di sovrascrittura nel sistema 
  di file. Potresti aver bisogno di sapere questo per la risoluzione dei problemi.

*Tradotto da openai.com*

