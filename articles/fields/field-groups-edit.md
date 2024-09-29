<!-- Filename: Help4.x:Component:_New_or_Edit_Field_Group / Display title: Componente: Modifica Gruppo di Campi -->

## Descrizione

I Gruppi di Campi vengono utilizzati per raggruppare i campi correlati sotto una scheda nominata in un modulo di inserimento dati. Il Componente: Modifica Gruppo di Campi è simile per tutti i componenti che implementano campi, ma il titolo della pagina cambia a seconda del contesto: Articoli: Modifica Gruppo di Campi, Contatti: Modifica Gruppo di Campi o Utenti: Modifica Gruppo di Campi.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di Assistenza separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda di Pubblicazione](jdocmanual?article=help/common-elements/edit-publishing).
* [La Scheda delle Autorizzazioni](jdocmanual?article=help/common-elements/edit-permissions).

## Come Accedere

* Seleziona **Contenuto → Gruppi di Campi** dal menu dell'Amministratore. Oppure...
* Seleziona **Contatto → Gruppi di Campi** dal menu dell'Amministratore. Oppure...
* Seleziona **Utenti → Gruppi di Campi** dal menu dell'Amministratore. Poi...
  * seleziona il pulsante **Nuovo** nella Barra degli Strumenti per creare un nuovo campo. Oppure...
  * seleziona un **Titolo** dall'elenco per modificare un campo esistente.

**Nota:** C'è un elenco a discesa che consente la creazione di Campi per una Categoria e Mail nel componente Contatto. Richiedono alcune competenze di programmazione per preparare adeguate sostituzioni di modelli.

## Screenshot

Questo esempio è una pagina *Articoli: Modifica Gruppo di Campi*. *Contatti: Modifica Gruppo di Campi* e *Utenti: Modifica Gruppo di Campi* sono simili.

![articoli modifica gruppo di campi](../../../it/images/fields/articles-edit-field-group.png)

## Campi del Modulo

- **Titolo** Il titolo per questo gruppo di campi.

### Generale

#### Pannello Sinistro

- **Descrizione** Testo che verrà visualizzato come suggerimento quando si passa
  con il mouse sopra la casella di testo durante la creazione di un articolo, un
  contatto o un componente di terze parti che supporta campi personalizzati. 
  Questo testo non è traducibile. Non vedrai questa descrizione nel Frontend.

#### Pannello Destro

- **Stato** Lo stato pubblicato di questo gruppo di campi.
  - *Pubblicato* Il gruppo di campi è visibile durante la modifica di un 
    articolo o un contatto. Ed è visibile nel Frontend.
  - *Non Pubblicato* Il gruppo di campi non sarà visibile agli utenti durante la
    modifica di un articolo o un contatto.
  - *Archiviato* Il gruppo di campi non verrà più mostrato durante la modifica
    di un articolo o un contatto. Puoi aprirlo nei Gruppi di Campi quando imposti
    il filtro su archiviato.
  - *Cancellato* Il gruppo di campi è stato eliminato ma è ancora nel database.
    Può essere eliminato definitivamente dal database nei Gruppi di Campi con la
    funzione Svuota Cestino.
- **Accesso** Seleziona il livello di accesso per la visualizzazione di questo
  gruppo di campi. I livelli di accesso dipendono da ciò che è stato impostato in
  Utenti: Livelli di Accesso.
- **Lingua** Seleziona la lingua per questo gruppo di campi. Se non stai 
  utilizzando la funzione multilingua di Joomla, mantieni il valore predefinito 
  *Tutte*.
- **Nota** Un campo opzionale per fare annotazioni personali per il gruppo di campi.

### Opzioni

- **Mostra Quando Sola Lettura** Se il gruppo di campi è solo in lettura
  (forse l'utente non ha il livello di accesso) il gruppo di campi dovrebbe 
  essere mostrato o nascosto.

*Tradotto da openai.com*

