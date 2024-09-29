<!-- Filename: Help4.x:Contacts:_New_or_Edit / Display title: Contatti: Modifica -->

## Descrizione

Il *Modulo di modifica dei contatti* viene utilizzato per aggiungere un nuovo contatto o modificare un contatto esistente.

**Attenzione:** Se un contatto ha un elemento di menu, le Impostazioni del Menu Contatti
sostituiscono alcune delle impostazioni disponibili qui. Fare attenzione a
non divulgare informazioni personali per errore!

### Elementi comuni

Alcuni aspetti di questa pagina sono trattati in articoli della Guida separati:

* [Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La scheda Schema](jdocmanual?article=help/common-elements/edit-schema).
* [La scheda Pubblicazione](jdocmanual?article=help/common-elements/edit-publishing).
* [La scheda Associazioni](jdocmanual?article=help/common-elements/edit-associations).
* [Popup Cronologia delle Versioni](jdocmanual?article=help/common-elements/edit-version-history).

## Come Accedere

- Seleziona **Componenti → Contatti → Contatti** nel menu Amministratore.
- Per **Aggiungere** un nuovo contatto:
  - Seleziona il pulsante **Nuovo** nella barra degli strumenti.
- Per **Modificare** un contatto esistente:
  - Seleziona un titolo di contatto nella colonna **Titolo**.

## Schermata

![Modifica contatto di Contatti](../../../it/images/contacts/contacts-edit-contact-tab.png)

## Campi del Modulo

In questa sezione, puoi inserire informazioni sul Contatto, come nome, indirizzo, e-mail, e così via. Le opzioni ti permettono di controllare le impostazioni come quali informazioni vengono visualizzate per ciascun Contatto.

- **Nome** Il nome completo del Contatto.
- **Alias** Il nome interno dell'elemento. Normalmente, puoi lasciare questo campo vuoto e Joomla riempirà un valore predefinito nel Titolo in minuscolo e con trattini al posto degli spazi.

### Scheda Modifica Contatto

Qui inserisci le informazioni di base sul contatto.

- **Utente Collegato** Se questo Contatto è collegato a un utente, seleziona l'icona *Seleziona Utente* per rivelare un modulo popup da cui selezionare uno degli utenti registrati. Un utente collegato può essere rimosso con il pulsante *- Nessun utente -* nel modulo popup Seleziona Utente.
- **Immagine** Immagine da visualizzare per questo Contatto. Seleziona un file immagine dall'elenco a discesa. Questo elenca le immagini nella cartella 'images/stories'. Le immagini possono essere caricate utilizzando il componente Media.
- **Posizione:** La posizione attuale del Contatto.
- **E-mail** L'indirizzo e-mail del Contatto. Nota che gli indirizzi e-mail in Joomla! possono essere protetti dallo "spambot" abilitando il Plugin "Content-Email Cloaking". Questo è abilitato per default.
- **Indirizzo** L'indirizzo stradale del Contatto.
- **Città o Quartiere** La città o il quartiere del Contatto.
- **Stato o Provincia** Lo stato o la provincia del Contatto.
- **Codice Postale / CAP** Il codice postale del Contatto.
- **Paese** Il paese del Contatto.
- **Telefono** Il numero di telefono del Contatto.
- **Cellulare** Il numero di cellulare del Contatto.
- **Fax** Il numero di fax del Contatto.
- **Sito Web** L'indirizzo del sito web del Contatto.
- **Campi di Ordinamento** Per abilitare i campi di ordinamento per gli elenchi di Categoria, vai alla schermata **Contatti → Opzioni** e imposta **Layout Elenchi → Ordina per** a **Ordina Nome**. Quindi devi usare parole reali per l'ordinamento. Ad esempio, imposta il Primo Campo di Ordinamento a **Doe**, il secondo campo a **John** per il primo contatto; poi il Primo Campo di Ordinamento a **Doe**, il secondo campo a **Jane** per il secondo contatto. Il terzo campo non è utilizzato in questo caso. I campi di ordinamento sono campi di carattere, quindi se vuoi ordinare per età devi inserire 0x per età sotto i 10 anni, ad esempio 08.
  - **Primo Campo di Ordinamento** Il nome da utilizzare come primo campo di ordinamento.
  - **Secondo Campo di Ordinamento** Il nome da utilizzare come secondo campo di ordinamento.
  - **Terzo Campo di Ordinamento** Il nome da utilizzare come terzo campo di ordinamento.
- **Stato**: Lo stato di pubblicazione dell'elemento. I valori possibili sono:
  - *Pubblicato*: L'elemento è pubblicato. Questo è l'unico stato che permetterà agli utenti regolari del sito web di vedere questo elemento.
  - *Non Pubblicato*: L'elemento non è pubblicato.
  - *Archiviato*: L'elemento è stato archiviato.
  - *Cestinato*: L'elemento è stato inviato al Cestino.
- **Categoria** La Categoria a cui appartiene questo elemento.
- **In Primo Piano** Se l'elemento verrà o meno visualizzato in vista in primo piano.
- **Accesso** Il livello di accesso di visualizzazione per questo elemento.
- **Lingua** La lingua dell'elemento.
- **Tag** Inserisci uno o più tag opzionali per questo elemento. Puoi selezionare tag esistenti inserendo le prime lettere. Puoi anche creare nuovi tag inserendoli qui. I tag ti permettono di vedere elenchi di elementi correlati attraverso tipi di contenuti (ad esempio, articoli, contatti e categorie).
- **Nota di Versione** Campo opzionale per identificare questa versione dell'elemento nella finestra della Cronologia delle Versioni dell'elemento.

### Scheda Informazioni Varie

![Scheda modifica contatto contatti](../../../it/images/contacts/contacts-edit-miscellaneous-tab.png)

Altre informazioni su questo Contatto possono essere inserite utilizzando l'editor.

### Scheda Visualizzazione

![Scheda modifica contatto contatti](../../../it/images/contacts/contacts-edit-display-tab.png)

- **Mostra Categoria** Mostra o nasconde la categoria del Contatto.
- **Mostra Elenco Contatti** Mostra o nasconde l'elenco dei Contatti.
- **Formato di Visualizzazione** Determina lo stile utilizzato per visualizzare le sezioni del modulo contatti.
- **Tag** Se nascondere o mostrare i tag per questo elemento.
- **Informazioni del Contatto** Mostra o nasconde le informazioni del Contatto.
- **Informazioni Varie** Mostra o nasconde le informazioni varie.
- **vCard** Mostra o nasconde il link vCard per questo Contatto.
- **Mostra Articoli Utente** Se questo contatto è mappato a un utente, e se questo è impostato su Mostra, verrà visualizzato un elenco di articoli creati da questo utente.
- **\# Articoli da Elencare** Numero di articoli da elencare.
- **Profilo Utente** Se questo contatto è mappato a un utente, e se questo è impostato su Mostra, verrà visualizzato il profilo di questo utente.
- **Mostra Gruppi di Campi Personalizzati Utente** Mostra i campi personalizzati utente che appartengono a tutti o solo a determinati gruppi di campi.
- **Link del Contatto** Mostra o nasconde i link del contatto.
- **Etichetta Link A** Etichetta per un link aggiuntivo per questo contatto.
- **URL Link A** L'URL del link aggiuntivo per questo contatto.
- **Etichetta Link B** Etichetta per un link aggiuntivo per questo contatto.
- **URL Link B** L'URL del link aggiuntivo per questo contatto.
- **Etichetta Link C** Etichetta per un link aggiuntivo per questo contatto.
- **URL Link C** L'URL del link aggiuntivo per questo contatto.
- **Etichetta Link D** Etichetta per un link aggiuntivo per questo contatto.
- **URL Link D** L'URL del link aggiuntivo per questo contatto.
- **Etichetta Link E** Etichetta per un link aggiuntivo per questo contatto.
- **URL Link E** L'URL del link aggiuntivo per questo contatto.
- **Layout** Utilizza un layout diverso da quello fornito dalla vista del componente o dalle sostituzioni nei template.

### Scheda Modulo

![Scheda modifica contatto contatti](../../../it/images/contacts/contacts-edit-form-tab.png)

- **Modulo Contatti** Mostra o nasconde il modulo e-mail. Se selezionato su Mostra, viene visualizzato un modulo che consente all'utente di inviare un'e-mail al Contatto dal sito web.
- **Invia Copia al Mittente** Mostra o nasconde la casella di controllo: *Invia una copia di questo messaggio al tuo indirizzo*.
- **Verifica Sessione** Verifica l'esistenza del cookie di sessione. Questo significa che gli utenti senza cookie abilitati non potranno inviare e-mail.
- **Risposta Personalizzata** Disattiva la risposta automatica, consentendo ai Plugin di gestire l'integrazione con altri sistemi.
- **Reindirizzamento Contatto** Inserisci un URL alternativo, dove l'utente sarà reindirizzato dopo l'invio della mail.

*Tradotto da openai.com*

