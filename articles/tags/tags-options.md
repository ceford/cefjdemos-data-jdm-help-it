<!-- Filename: Help4.x:Tags:_Options / Display title: Tag: Opzioni -->

## Descrizione

La pagina *Tag: Opzioni* viene utilizzata per impostare i valori predefiniti globali per gli elementi del menu che mostrano i tag. Questi valori predefiniti verranno utilizzati quando *Usa Globale* è selezionato per un'opzione in un elemento del menu Tag. Ad esempio, per mostrare il *Nome del Tag* per un *Elenco degli Articoli Taggati* nei tuoi elementi del menu *Tag*, imposta quell'opzione su *Mostra* qui e sarà il valore predefinito. Non è necessario impostare nessuna di queste opzioni. Il tuo sito Joomla funzionerà con le impostazioni predefinite.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Autorizzazioni](jdocmanual?article=help/common-elements/edit-permissions).

## Come Accedere

- Seleziona **Componenti → Tag** dal menu dell'Amministratore. Poi...
  - Seleziona il pulsante **Opzioni** nella barra degli strumenti.

## Schermata

![opzioni dei tag elementi etichettati scheda](../../../it/images/tags/tags-options-tagged-items-tab.png)

## Campi del Modulo

### Tab Elementi Taggati

- **Layout Predefinito degli Elementi Taggati** Scegli un layout predefinito per gli elementi
  taggati. Questo layout verrà utilizzato quando un utente seleziona un tag che
  non ha un elemento di menu definito.
- **Abilita Versioni** Se salvare o meno la cronologia delle versioni
  per questo componente. 
- **Numero Massimo di Versioni** Il numero massimo di versioni da memorizzare per un
  elemento. Se un elemento viene salvato e il numero massimo di versioni è stato
  raggiunto, la versione più vecchia verrà eliminata automaticamente. Se impostato a
  0, le versioni non verranno mai eliminate automaticamente. Inoltre, specifiche
  versioni possono essere contrassegnate come *Mantieni per Sempre* e non verranno
  eliminate automaticamente. Nota che le versioni possono essere eliminate manualmente utilizzando il
  pulsante Elimina nella schermata Cronologia Versioni.
- **Mostra Nome del Tag** Per un layout con un solo tag, mostra il nome del tag.
- **Immagine del Tag** Per un layout con un solo tag, mostra l'immagine del tag.
- **Descrizione del Tag** Mostra o nasconde una descrizione per il tag (usato solo
  quando viene selezionato un singolo tag).
- **Immagine** Mostra l'immagine del tag (immagine completa).
- **Ordine** Ordine in cui gli elementi verranno visualizzati.
- **Direzione** Ordine di ordinamento. Decrescente è dal più alto al più basso. Crescente
  è dal più basso al più alto.
- **Intestazioni della Tabella** Mostra o nasconde le intestazioni nei layout a elenco.
- **Mostra Data** Se mostrare o meno una colonna data nell'elenco degli articoli.
  Seleziona Nascondi per nascondere la data, oppure seleziona quale data desideri mostrare.
- **Immagini degli Elementi** Mostra la prima immagine per ogni elemento nell'elenco.
- **Descrizione dell'Elemento** Se mostrare o nascondere la descrizione per ogni
  elemento nell'elenco. La lunghezza può essere limitata utilizzando l'opzione Numero Massimo
  di Caratteri.
- **Numero Massimo di Caratteri** Il numero massimo di caratteri da mostrare
  dalla descrizione in ogni tag.

### Tab Selezione Elementi

![opzioni tag tab elementi taggati](../../../it/images/tags/tags-options-item-selection-tab.png)

- **Lunghezza Minima di Ricerca** Questa impostazione controlla la lunghezza minima dei caratteri
  per la ricerca e l'aggiunta di tag utilizzando la modalità Ajax del campo tag.
- **Tipo di Corrispondenza** Tutti restituiranno elementi che hanno tutti i tag. Qualsiasi
  restituirà elementi che hanno almeno uno dei tag.
- **Tag Figli** Includi o escludi i tag figli dall'elenco dei risultati per
  un tag.
- **Numero Massimo di Elementi** Il numero massimo di risultati da restituire.
- **Filtro della Lingua** Filtra opzionalmente l'elenco dei tag in base alla
  lingua.

### Tab Elenco di Tutti i Tag

![opzioni tag tab elenco di tutti i tag](../../../it/images/tags/tags-options-list-all-tags-tab.png)

- **Layout Predefinito dell'Elenco di Tutti i Tag** Scegli un layout predefinito per l'Elenco di
  tutti i tag.
- **Ordine** Ordine in cui gli elementi verranno visualizzati.
- **Direzione** Ordine di ordinamento. Decrescente è dal più alto al più basso. Crescente
  è dal più basso al più alto.
- **Immagini degli Elementi** Mostra la prima immagine per ogni elemento nell'elenco.
- **Descrizione del Tag** Mostra o nasconde la descrizione per ogni tag
  elencato.
- **Numero Massimo di Caratteri** Il numero massimo di caratteri da mostrare
  dalla descrizione in ogni tag.
- **Hit** Mostra il numero di hit.

### Tab Layout Condiviso

![opzioni tag tab layout condiviso](../../../it/images/tags/tags-options-shared-layout-tab.png)

- **Campo Filtro** Se mostrare un campo Filtro per l'elenco. Seleziona
  Nascondi per nascondere il campo filtro.
- **Selezione Display** Se mostrare o nascondere la casella a discesa
  di Selezione Display.
- **Paginazione** Mostra o nasconde il supporto alla Paginazione. La paginazione fornisce
  dei link di pagina nella parte inferiore della pagina che permettono all'Utente di navigare
  verso pagine aggiuntive. Questi sono necessari se le Informazioni non possono essere
  contenute sulla pagina.
- **Risultati della Paginazione** Mostra o nasconde le informazioni dei risultati della paginazione,
  per esempio, *Pagina 1 di 4*.

### Tab Inserimento Dati

![opzioni tag tab inserimento dati](../../../it/images/tags/tags-options-data-entry-tab.png)

- **Modalità di Inserimento Tag** La modalità Ajax cerca i tag mentre si digita e consente di
  creare tag al volo. I tag nidificati ti mostrano una vista nidificata con tutti
  i tag disponibili.

### Tab Integrazione

![opzioni tag tab elementi taggati](../../../it/images/tags/tags-options-integration-tab.png)

- **Mostra Link al Feed** Mostra o nascondi un Link al Feed RSS. (Un Link al Feed apparirà
  come un'icona del feed nella barra degli indirizzi della maggior parte dei browser moderni).

## Suggerimenti

- Se sei un utente principiante, mantieni i valori predefiniti qui
  finché non avrai imparato di più sull'uso delle opzioni globali.
- Se sei un utente avanzato, risparmia tempo creando buoni
  valori predefiniti qui. Quando imposti gli elementi del menu e crei i tag,
  sarai in grado di accettare i valori predefiniti per la maggior parte delle opzioni.

*Tradotto da openai.com*

