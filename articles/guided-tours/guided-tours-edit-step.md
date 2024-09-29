<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Step / Display title: Tour Guidati: Modifica Step -->

## Descrizione

Questa pagina è utilizzata per aggiungere un nuovo Passaggio o modificare un Passaggio esistente di un tour.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda di Pubblicazione](jdocmanual?article=help/common-elements/edit-publishing).

## Come Accedere

- Seleziona **Sistema -> Gestisci -> Tour Guidati** dal menu dell'amministratore.
- Seleziona il pulsante **Passaggi** numerato per un tour per aprire la pagina dei passaggi del tour.
- Seleziona il pulsante della barra degli strumenti **Nuovo** per aggiungere un passaggio.
- Seleziona un **Titolo** dall'elenco per modificare un passaggio.

## Screenshot

![Modifica passaggio dei tour guidati](../../../it/images/guided-tours/guided-tours-edit-step.png)

## Campi del Modulo

- **Titolo** Il titolo per questo passaggio. Di solito è un invito all'azione, per
esempio `Inserisci un titolo` se il passaggio richiede l'interazione dell'utente. Se il titolo
è una chiave di lingua, verrà mostrato un campo aggiuntivo che rappresenta la traduzione
di quella chiave per la lingua dell'utente.

### Scheda Modifica Passaggio

#### Pannello Sinistro

- **Descrizione** Qui si inserisce la descrizione del passaggio, di solito
  una spiegazione dettagliata o un aiuto per il passaggio.
  La descrizione del passaggio può essere una chiave di lingua. In tal caso,
  un campo secondario presenta la descrizione tradotta di quella chiave per la
  lingua dell'utente.

#### Pannello Destro

- **Posizione** La posizione del passaggio rispetto alle informazioni a cui si riferisce.
  - **In basso** Il passaggio si mostra sotto il target.
  - **Centro** Il passaggio si mostra al centro dello schermo. Quando manca un target,
    questa è la posizione predefinita.
  - **Sinistra** Il passaggio si mostra alla sinistra del target.
  - **Destra** Il passaggio si mostra alla destra del target.
  - **In alto** Il passaggio si mostra sopra il target.
- **Target** L'elemento dello schermo a cui il passaggio fa riferimento. Utilizza la sintassi CSS.

  Per esempio, *.button-new* punterà al pulsante della pagina avente classe
  *button-new*.

  Se il target non è unico, verrà utilizzato il primo target trovato. Quando si creano
  passaggi interattivi, assicurarsi che il target sia focalizzabile per l'accessibilità. Si
  possono usare diversi selettori, separati da virgole. Il primo selettore valido diventerà
  il target (un selettore è valido se: trovato sulla pagina, non disabilitato, 
  non di sola lettura e non nascosto). Se è stato impostato un target ma non viene trovato o
  è invalido, il tour non si interromperà ma mostrerà il passaggio al centro dello schermo.
- **Tipo** Il tipo di passaggio.
  - **Successivo** L'utente che sta eseguendo il tour passerà al passaggio successivo.
  - **Reindirizzamento** Il passaggio sarà reindirizzato a un'altra pagina.
  - **Interattivo** Il passaggio richiede l'interazione dell'utente, come l'inserimento di dati.
- **URL** L'URL per il reindirizzamento di un passaggio di tipo *Reindirizzamento*.
  Per esempio, *administrator/index.php?option=com_users&view=user&layout=edit*
  reindirizzerà il passaggio alla schermata di modifica utente.
- **Tipo Interattivo** Il tipo di interazione per un passaggio interattivo.
  - **Invio Modulo** Il target è un pulsante che invia un modulo.
  - **Campo di Testo** Il target è un campo di testo. Se il campo è obbligatorio,
    la persona che esegue il tour non potrà continuare al passaggio successivo 
    finché non saranno inseriti i dati.
  - **Pulsante** Il target è un pulsante sullo schermo.
  - **Altro** Il target è qualsiasi altro elemento del modulo.

### Scheda Opzioni

![Opzioni della scheda modifica passaggio nei tour guidati](../../../it/images/guided-tours/guided-tours-edit-step-options-tab.png)

## Suggerimenti

- Usa **GUIDEDTOUR** nelle chiavi di linguaggio come convenzione ovunque
  siano utilizzate le chiavi di linguaggio (per titolo e descrizione).

*Tradotto da openai.com*

