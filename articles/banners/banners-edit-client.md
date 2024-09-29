<!-- Filename: Help4.x:Banners:_New_or_Edit_Client / Display title: Banner: Modifica Cliente -->

## Descrizione

Il modulo di Modifica Cliente dei Banner viene utilizzato per inserire o modificare i dati del Cliente del Banner.
È necessario avere almeno un Cliente del Banner prima di poter creare un Banner.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli della Guida separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Il popup della Cronologia delle Versioni](jdocmanual?article=help/common-elements/edit-version-history).

## Come Accedere

- Seleziona **Componenti → Banner → Clienti** nel menu dell'Amministratore.
  - Per creare un nuovo Cliente, seleziona il pulsante **Nuovo** nella Barra degli Strumenti.
  - Per modificare un Cliente esistente, seleziona il **nome** nella colonna Clienti.

## Screenshot

![Modifica banner cliente](../../../it/images/banners/banners-edit-client-details-tab.png)

## Campi del Modulo

- **Nome** Il nome di questo cliente.

### Scheda Dettagli

- **Nome Contatto** Il nome della persona di contatto per questo cliente.
- **E-mail Contatto** L'indirizzo e-mail del cliente del banner.
- **Tipo di Acquisto** Il tipo di acquisto del banner. Questo viene utilizzato per 
  indicare come il cliente del banner ha acquistato il tempo di esposizione del 
  banner - mensilmente, annualmente, ecc...
- **Traccia Impression** Se tracciare o meno il numero di volte in cui il
  banner viene visualizzato dai visitatori del sito web.
- **Traccia Click** Se tracciare o meno il numero di volte in cui il
  banner viene cliccato dai visitatori del sito web.
- **Informazioni Aggiuntive** Inserisci tutte le informazioni extra che vuoi
  salvare per questo cliente.
- **Stato** Stato di pubblicazione dell'elemento. I valori possibili sono:
  - *Pubblicato*: L'elemento è pubblicato. Questo è l'unico stato che 
    permetterà agli utenti regolari del sito web di visualizzare questo elemento.
  - *Non Pubblicato*: L'elemento non è pubblicato.
  - *Archiviato*: L'elemento è stato archiviato.
  - *Nel Cestino*: L'elemento è stato inviato nel Cestino.
- **Nota di Versione** Campo facoltativo per identificare questa versione dell'elemento
  nella finestra di Cronologia delle Versioni dell'elemento.

### Scheda Metadata

![Scheda metadata modifica cliente banner](../../../it/images/banners/banners-edit-client-metadata-tab.png)

- **Parole Chiave** Inserimento facoltativo per parole chiave. Devono essere inserite separate
  da virgole (per esempio, "gatti, cani, animali domestici") e possono essere inserite 
  in maiuscolo o minuscolo. (Per esempio, "GATTI" corrisponderà a "gatti" o 
  "Gatti"). Le parole chiave possono essere utilizzate in diversi modi:
  1.  Per aiutare i motori di ricerca e altri sistemi a classificare il contenuto 
      dell'Articolo.
  2.  In combinazione con i tag del Banner, per visualizzare banner specifici in base 
      al contenuto dell'Articolo. Ad esempio, supponiamo di avere un banner con 
      un annuncio per prodotti per cani e un altro banner per prodotti per gatti. 
      Puoi far visualizzare il tuo banner per cani quando un utente sta visualizzando 
      un articolo correlato ai cani e il tuo banner per gatti per un articolo correlato 
      ai gatti. Per fare questo, dovresti:
      - Aggiungere le parole chiave "cane" e "gatto" agli articoli appropriati.
      - Aggiungere i tag "cane" e "gatto" ai banner appropriati in 
        Banners: Modifica.
      - Impostare il parametro del modulo Banner 'Ricerca per Tag' su "Sì" nella lista 
        dei Moduli del Sito: Banners.
  3.  Solo per articoli, in combinazione con il modulo Articoli - Correlati,
      per visualizzare articoli che condividono almeno una parola chiave in comune. Ad 
      esempio, se l'articolo corrente visualizzato ha le parole chiave "gatti, 
      cani, scimmie", qualsiasi altro articolo con almeno una di queste parole chiave
      verrà mostrato nel modulo 'Articoli - Correlati'.
- **Usa Prefisso Proprio** Se utilizzare o meno il prefisso del banner o quello 
  del cliente. Seleziona *No* se desideri utilizzare il prefisso del cliente del banner.
- **Prefisso Meta Keyword** Quando si abbinano meta keyword, cercare solo 
  meta keyword con questi prefissi opzionali. Questo migliora le prestazioni.

*Tradotto da openai.com*

