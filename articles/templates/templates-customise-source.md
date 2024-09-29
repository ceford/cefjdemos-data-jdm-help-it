<!-- Filename: Help4.x:Templates:_Customise_Source / Display title: Modelli: Personalizzare la Sorgente -->

<div class="alert alert-warning">
Questa pagina appare nell'indice delle pagine di aiuto, ma non viene utilizzata tramite un pulsante di aiuto.
Questo è un bug che probabilmente verrà corretto.
</div>

## Descrizione

La pagina *Templates: Personalizza Sorgente* è il luogo in cui viene modificato il codice sorgente dei file del modello. Fornisce un'interfaccia in testo semplice per modificare i file del modello. La sintassi di programmazione HTML e PHP viene evidenziata per rendere i file del codice sorgente più facili da leggere. Nella barra del titolo, la parola *Sorgente* appare come nome del modello, ad esempio *(Cassiopeia)*.

## Come Accedere

- Seleziona **Sistema → Pannello Modelli → Modelli Sito** dal menu
  dell'Amministratore. Oppure...
- Seleziona **Sistema → Pannello Modelli → Modelli Amministratore**
  dal menu dell'Amministratore. Poi...
  - Seleziona un nome di modello dalla colonna **Modelli**. Poi...
    - Seleziona un file da modificare dalla scheda Editor.

## Schermata

![Personalizzazione dei template tab dell'editor di cassiopeia](../../../it/images/templates/templates-customise-cassiopeia-edit-component-editor-tab.png)

## Campi del Modulo

### Scheda Editor

- Seleziona un file da modificare. L'area di modifica mostra il testo con evidenziazione della sintassi per
  la maggior parte dei tipi di file.

### Scheda Crea Sovrascritture

- Seleziona un elemento da sovrascrivere. Se viene selezionata una cartella, questa viene espansa per visualizzare
  un elenco di file. Se viene selezionato un file, viene immediatamente copiato nella cartella html 
  senza chiedere conferma. La sovrascrittura viene posizionata nel 
  luogo appropriato. Viene visualizzato un messaggio di conferma, ad esempio: 
  *Sovrascrittura creata in /templates/cassiopeia/html/mod_whosonline*.

### Scheda File Aggiornati

Se non ci sono stati aggiornamenti al template da quando sono state create le sovrascritture,
questa scheda conterrà un messaggio semplice:

- **Avviso** I file sovrascritti sono aggiornati. Nulla è stato cambiato
  nell'ultimo aggiornamento dell'estensione o di Joomla.

Se ci sono stati aggiornamenti, una tabella mostrerà un elenco delle sovrascritture che
devono essere riviste.

### Scheda Descrizione del Template

- **Anteprima e Descrizione** Informazioni su questo template.

## Barra degli strumenti

Le icone della Barra degli strumenti cambiano in base all'azione che si sta eseguendo. Potresti vedere:

- **Salva** Salva l'elemento e rimane nella schermata corrente.
- **Salva e Chiudi** Salva l'elemento e chiude la schermata corrente.
- **Copia Modello** Copia il modello corrente. Verrà visualizzata una finestra di dialogo per l'inserimento del nuovo nome.
- **Anteprima Modello** Seleziona per aprire il Sito in una nuova scheda del browser.
- **Gestisci Cartelle** Consente di creare ed eliminare cartelle di modelli utilizzando una finestra di dialogo.
- **Nuovo File** Consente di caricare un file dal tuo computer nella gerarchia dei file del modello utilizzando una finestra di dialogo.
- **Rinomina File** Seleziona un file da modificare. Seleziona il pulsante Rinomina per inserire un nuovo nome.
- **Elimina File** Verrà richiesto di Confermare o Annullare.
- **Chiudi File** Chiude il file aperto e ritorna alla Scheda Editor.
- **Aiuto** Apre questa schermata di aiuto.

## Suggerimenti

- Importante: Non eliminare i file template predefiniti utilizzando FTP perché
  ciò genera un errore sia nel frontend che nel backend.
- Prima di modificare i file HTML e CSS del template, è una buona
  idea fare un backup del file che si sta modificando. Inoltre, puoi modificare
  questi file al di fuori di Joomla! utilizzando l'editor HTML o CSS di tua scelta.

*Tradotto da openai.com*

