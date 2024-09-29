<!-- Filename: Help4.x:Templates:_Edit_Style / Display title: Modelli: Modifica Stile -->

## Descrizione

La pagina *Template: Modifica Stile* viene utilizzata per modificare gli stili dei template. Quando un template viene installato per la prima volta, viene creato uno stile predefinito per esso. Lo stile predefinito per il template avrà lo stesso nome del template con il suffisso *- Predefinito*. Per creare una variazione diversa dello stile predefinito del template, seleziona la casella di controllo dello stile predefinito e premi l'icona *Duplica* nella barra degli strumenti. Poi modifica il duplicato.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).

## Come Accedere

- Seleziona **Sistema → Pannello Template → Stili Template Sito**
  dal menu Amministratore. Oppure...
- Seleziona **Sistema → Pannello Template → Stili Template Amministratore**
  dal menu Amministratore. Poi...
  - Seleziona il nome dello Stile Template da modificare nella colonna Stile.

## Screenshot

![templates cassiopeia modifica scheda editor stile](../../../it/images/templates/templates-site-edit-style-details-tab.png)

## Campi del Modulo

- **Nome dello Stile** Il nome dello stile. Questo è il nome che verrà
  visualizzato nella colonna Stile della schermata *Template: Stili*.

### Scheda Dettagli

- **Informazioni** Il nome del template, indicatore di Sito o Amministratore
  e una breve descrizione.

### Scheda Avanzato

![templates cassiopeia edit style editor tab](../../../it/images/templates/templates-site-edit-style-advanced-tab.png)

Questa sezione potrebbe non essere presente per tutti gli stili. Se un template
da cui è derivato uno stile ha opzioni configurabili, queste saranno presenti
qui. Sono queste opzioni configurabili aggiuntive che ti permettono di avere
diversi stili di template con variazioni di queste opzioni. Le opzioni disponibili
varieranno in base a ciò che ha reso disponibile lo sviluppatore del template.

### Impostazioni Colore Atum

Il template di default dell'Amministratore ti permette di sperimentare con variazioni
di colore. Salva e guarda!

### Impostazioni Immagine Atum

Puoi selezionare un'immagine per sostituire il **Logo di Login** nel modulo di login
dell'Amministratore, e il **Logo del Brand** nella barra del titolo dell'Amministratore
in modalità estesa e compatta. I predefiniti sono i loghi del Brand Joomla. Nella barra
del titolo, la parola Joomla! è presente nella versione **Brand Large** e omessa nella
versione **Brand Small**. Seleziona **Toggle Menu** per vedere il cambiamento.

Se fornisci il tuo Brand Small devi anche fornire un override dello stile per la larghezza.
Per farlo, crea un file user.css nella root del template e inserisci il seguente codice,
sostituendo 3rem con una larghezza adatta per la tua immagine:

       .header .logo.small {
           width: 3rem;
       }

### Scheda Assegnazione Menù

![templates cassiopeia edit style editor tab](../../../it/images/templates/templates-site-edit-style-menu-assignment-tab.png)

Questa sezione contiene tutti gli elementi di menu configurati nel tuo sito Joomla!
Per applicare lo stile corrente alla pagina web corrispondente a un elemento di menu,
seleziona la casella di controllo accanto all'elemento del menu. Puoi premere il pulsante
*Toggle Selection* per invertire le selezioni degli elementi del menu.

**Nota** Se una casella di controllo è grigia e non può essere selezionata, potrebbe
essere perché l'elemento del menu è in uso da un altro utente. Puoi verificare se questo
è il caso andando alla schermata del gestore dei menu per il menu in questione. Se c'è
un simbolo a forma di lucchetto accanto all'elemento del menu, allora è attualmente in
uso da un altro utente.

*Tradotto da openai.com*

