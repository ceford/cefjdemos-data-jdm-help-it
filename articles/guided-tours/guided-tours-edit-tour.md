<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Tour / Display title: Tour Guidati: Modifica Tour -->

Feel free to ask if you need any further assistance!

## Descrizione

Questa pagina è utilizzata per aggiungere un nuovo Tour o modificare un Tour esistente. Un tour deve 
includere almeno una tappa. Una volta creato un nuovo tour, vai alla lista dei Tour 
e seleziona il pulsante con l'etichetta *0* dalla colonna Tappe. La prima 
tappa del tour è creata automaticamente dal titolo e dalla descrizione del tour.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di Aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Pubblicazione](jdocmanual?article=help/common-elements/edit-publishing).

## Come Accedere

- Seleziona **Sistema -> Gestisci -> Tour Guidati** dal menu Amministratore.
- Seleziona il pulsante nella barra degli strumenti **Nuovo** per aggiungere un tour.
- Seleziona un **Titolo** dall'elenco per modificare un tour.

## Screenshot

![Tour Guidati Modifica Tour](../../../it/images/guided-tours/guided-tours-edit-tour.png)

## Campi del Modulo

- **Titolo** Il titolo per questo tour. Se il titolo è una chiave di lingua, viene mostrato un campo aggiuntivo, che rappresenta la traduzione di quella chiave per la lingua dell'utente.
- **Identificatore del Tour** Un identificativo univoco per il tour. Al momento del *Salva* o *Salva come Copia*, viene fornito un valore di default. Un formato suggerito potrebbe essere *nomeautore-nometour*, *nomeazienda-nometour* o *dominio-nometour*. Questo identificativo ha molteplici scopi: avviare un tour da qualsiasi luogo (non solo dal modulo Guided Tours), differenziare i tour provenienti da diverse origini e, nei siti multilingue, determina la struttura dei nomi dei file di lingua.

### Scheda Modifica Tour

#### Pannello Sinistro

- **URL Relativo** Il percorso relativo obbligatorio da cui inizia il tour. Ad esempio, per iniziare un tour dalla pagina del tour, inserisci `administrator/index.php?option=com_guidedtours&view=tours`.
- **Descrizione** Qui inserisci la descrizione del tour. La descrizione del tour può essere una chiave di lingua. Quando è così, un campo secondario presenta la descrizione tradotta di quella chiave per la lingua dell'utente.

#### Pannello Destro

- **Selettore di Componenti** Il tour sarà visibile prioritariamente nelle pagine delle estensioni selezionate. Usa *Tutto* per mostrare il tour in tutte le pagine. Quando è impostato su *Tutto*, il tour è posizionato per ultimo nella lista dei tour contestuali nel menu a discesa del modulo. Questo è un campo obbligatorio.
- **Avvio Automatico** Consente al tour di avviarsi automaticamente quando un utente raggiunge il contesto in cui il tour dovrebbe essere visualizzato.

## Suggerimenti

- Ci sono 2 metodi per inserire un'immagine nella descrizione del tour utilizzando l'editor
  TinyMCE.
  1. L'elenco a discesa **Contenuto CMS** fornisce l'accesso alla schermata **Media**
     che ti permette di sfogliare i file delle immagini e caricare immagini.
  2. L'elenco a discesa *Inserisci* è un modulo semplice per il quale devi conoscere
     l'URL dell'immagine. Viene utilizzato per immagini esterne.
- Ci sono 2 modi per creare i tour in ambienti multilingue:
  1. Creare un tour per ogni lingua supportata.
  2. Creare un solo tour per tutte le lingue e utilizzare le chiavi di lingua per il titolo
     e la descrizione.
- Usa **GUIDEDTOUR** nelle chiavi di lingua come convenzione ovunque vengano utilizzate
  le chiavi di lingua (per il titolo e la descrizione).

