<!-- Filename: Help4.x:Templates:_Customise / Display title: Template: Personalizza -->

## Descrizione

La pagina *Templates: Personalizza* viene utilizzata per modificare il codice sorgente di un template.
Puoi creare sovrascritture per i file php e creare file user.css e user.js da aggiungere
alle versioni di sistema. Puoi creare template figli per consentire la modifica
dei file master del template delle sovrascritture.

## Come Accedere

- Seleziona **Sistema → Pannello Template → Template del Sito** dal menu
  dell'Amministratore. Oppure...
- Seleziona **Sistema → Pannello Template → Template dell'Amministratore**
  dal menu dell'Amministratore. Poi...
  - Seleziona un nome di template dalla colonna **Template**.

## Schermata

Le schermate Amministratore e Modelli del Sito usano lo stesso layout. La schermata del Modello del Sito è illustrata qui.

![modelli personalizzare cassiopeia editor scheda](../../../it/images/templates/templates-customise-cassiopeia-editor-tab.png)

## Campi del Modulo

### Scheda Editor

- Seleziona un file da modificare. L'area di modifica mostra il testo con la sintassi evidenziata per la maggior parte dei tipi di file.

### Scheda Crea Overrides

![scheda crea overrides personalizza cassiopeia modelli](../../../it/images/templates/templates-customise-cassiopeia-create-overrides-tab.png)

- Seleziona un elemento da sovrascrivere. Elementi contrassegnati con un'icona di file solido si aprono per rivelare un elenco di elementi. Gli elementi contrassegnati con icone sovrapposte di pagina aperta e piena creano immediatamente un override senza richiesta di conferma. L'override viene posizionato nella posizione appropriata. C'è un messaggio di conferma, ad esempio:
  *Override creato in /templates/cassiopeia/html/mod_whosonline*.

### Scheda File Aggiornati

![scheda aggiornata personalizza cassiopeia template](../../../it/images/templates/templates-customise-cassiopeia-updated-files-tab.png)

Se non ci sono stati aggiornamenti al modello da quando sono stati creati gli overrides, questa scheda conterrà un semplice messaggio:

<div class="alert alert-success">
I file sovrascritti sono aggiornati. Nulla è stato cambiato nell'ultimo aggiornamento dell'estensione o di Joomla.
</div>

Se ci sono stati aggiornamenti, una tabella mostrerà un elenco di overrides che necessitano di essere rivisti.

### Scheda Descrizione Modello

![scheda descrizione modello personalizza cassiopeia](../../../it/images/templates/templates-customise-cassiopeia-template-description-tab.png)

- **Miniatura e Descrizione** Informazioni su questo modello.

## Barra degli strumenti

Nota che i pulsanti della barra degli strumenti cambiano quando viene selezionato un file per la modifica.

### Nessun file selezionato

In cima alla pagina vedrai la barra degli strumenti mostrata nello
screenshot sopra. Le funzioni sono:

- **Crea Template Figlio** Seleziona per creare un nuovo template figlio
  completo. Verrà richiesto di inserire un nuovo nome per il template figlio. È
  anche possibile chiudere senza creare un nuovo template figlio. Per rimuovere
  il nuovo template figlio: seleziona il pulsante **Chiudi**, seleziona il
  pulsante Stili nella barra degli strumenti dell'elenco dei Templates, seleziona
  la casella di controllo del template per il nuovo template figlio e seleziona
  Elimina nella barra degli strumenti.
- **Anteprima Template** Seleziona per aprire la vista predefinita del sito
  utilizzando questo template.
- **Gestisci Cartelle** Seleziona per creare una nuova cartella all'interno della
  gerarchia del template. Apparirà una finestra popup. **Importante:** seleziona la
  cartella in cui deve apparire la nuova cartella prima di crearla.
- **Nuovo File** Seleziona per creare un nuovo file o per caricare un file dal
  tuo computer nella gerarchia del template di Joomla! Apparirà una finestra popup.
  **Importante** Seleziona la cartella in cui deve apparire il nuovo file prima di
  crearlo.
- **Verifica Override** Attivato quando viene selezionato un Override nella
  scheda *Override*. Le opzioni sono:
  - Marca Verificato
  - Marca Non Verificato
  - Rimuovi Record
- **Chiudi** Chiude la schermata corrente e ritorna alla schermata precedente
  senza salvare le modifiche apportate. Questa icona della barra degli strumenti non
  viene mostrata se stai creando un nuovo elemento.
- **Aiuto** Apre questa schermata di aiuto.

### File selezionato

- **Salva** Salva l'elemento e rimane nella schermata corrente.
- **Salva e Chiudi** Salva l'elemento e chiude la schermata corrente.
- **Rinomina File** Seleziona un file da modificare. Seleziona il pulsante Rinomina
  per inserire un nuovo nome.
- **Elimina File** Verrà richiesto di Confermare o Annullare.
- **Verifica Override** Attivato quando viene selezionato un Override nella
  scheda *Override*.
- **Chiudi File** Chiude il file aperto e ritorna alla scheda Editor.
- **Aiuto** Apre questa schermata di aiuto.

## Suggerimenti

- Prima di modificare il file HTML e CSS del modello, è una buona idea fare un backup del file che stai modificando. Inoltre, puoi modificare questi file al di fuori di Joomla! utilizzando l'editor HTML o CSS di tua scelta.

*Tradotto da openai.com*

