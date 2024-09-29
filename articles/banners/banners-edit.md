<!-- Filename: Help4.x:Banners:_Edit / Display title: Banner: Modifica -->

## Descrizione

Usato per aggiungere o modificare banner che possono essere visualizzati sul tuo sito Joomla!
Ricorda di creare almeno un Cliente Banner e una Categoria Banner prima di creare qualsiasi Banner.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda di Pubblicazione](jdocmanual?article=help/common-elements/edit-publishing).
* [Il Popup Cronologia delle Versioni](jdocmanual?article=help/common-elements/edit-version-history).

## Come Accedere

Dal menu Amministratore:
- Seleziona **Componenti → Banners** per andare alla pagina di elenco dei Banner.
- Seleziona il pulsante **Nuovo** nella Toolbar per creare un nuovo Banner.
- Seleziona un **nome** del Banner dalla colonna *Nome* per modificare un Banner esistente.

## Screenshot

Un banner può essere un'immagine cliccabile o un codice personalizzato. Il Tipo Immagine è
mostrato nello screenshot qui sotto. Il tipo personalizzato ha la casella di selezione
dell'immagine sostituita con un'area di testo per il codice.

![Banners edit details tab](../../../it/images/banners/banners-edit-details-tab.png)

## Campi del modulo

- **Name** Il nome del Banner. Questo è il nome che verrà visualizzato
  nella colonna *Nome* della lista dei Banner.
- **Alias** Il nome interno dell'elemento. Normalmente, puoi lasciare questo
  campo vuoto e Joomla inserirà un valore predefinito derivato dal Nome ma
  in minuscolo e con trattini invece degli spazi.

## Scheda Dettagli

### Pannello Sinistro

- **Tipo** Il tipo di banner da visualizzare. Le opzioni sono un file immagine o
  codice HTML personalizzato.
  - **Immagine** File immagine da visualizzare per il banner. Clicca sul bottone *Seleziona*
    per sfogliare e selezionare il file immagine da utilizzare. Usa la pagina Media
    per caricare i file immagine del Banner nel tuo sito. Le immagini per i Banner
    devono essere nella directory /images/banners/.
    - **Larghezza** La larghezza fissa per ridimensionare l'immagine del banner. Lascia
      questo campo vuoto se vuoi usare la larghezza effettiva del file immagine del banner.
    - **Altezza** L'altezza fissa per ridimensionare l'immagine del banner. Lascia
      questo campo vuoto se vuoi usare l'altezza effettiva del file immagine del banner.
    - **Testo Alternativo** Testo da visualizzare al posto dell'immagine del banner
      nel caso in cui l'immagine non possa essere visualizzata.
    - **Testo Alternativo** Testo alternativo per l'immagine del Banner.
  - **Personalizzato** Seleziona Personalizzato se desideri inserire un codice personalizzato per
    il tuo banner.
    - **Codice Personalizzato** Usa {CLICKURL} e {NAME} per unire rispettivamente i valori 'Click URL'
      e 'Nome' nel tuo codice personalizzato. Ad esempio:<br>
      `<a href=`&#34;`{CLICKURL}"><img src=`&#34;`enter url to image" alt="{NAME}" title="{NAME}"></a>`.
      Un'altra opzione è inserire un codice HTML personalizzato. Ad esempio:<br>
      `<div class="yourclass"><a href=`&#34;`https://yourdomain.com"><img src=`&#34;`pathofyourimage"></a></div>`
- **Click URL** L'URL a cui navigare quando l'Utente clicca sul
  Banner.
- **Descrizione** Inserisci una descrizione per il Banner.

### Pannello Destro

- **Stato** Lo stato di pubblicazione dell'elemento.
- **Fissato** Indica se il Banner è *fissato*. Se uno
  o più Banner in una Categoria sono designati come *sticky*, avranno
  la precedenza rispetto ai Banner non sticky.
    - Ad esempio, se due Banner in una Categoria sono fissati e un terzo Banner
    non è fissato, il terzo Banner non verrà visualizzato se l'impostazione del modulo di visualizzazione dei Banner è *Pinned, Casuale* o *Pinned, Ordinamento*. Verranno visualizzati solo i
    due Banner fissati. Se i banner fissati hanno un numero fisso di impressioni, una volta esaurite tali impressioni, i banner fissati non verranno più visualizzati, e i banner non fissati inizieranno
    automaticamente a essere visualizzati.
- **Lingua** Lingua dell'elemento.
- **Nota Versione** Campo facoltativo per identificare questa versione dell'elemento
  nella finestra di cronologia delle versioni dell'elemento.

### Scheda Dettagli Banner

![Banners edit banner details tab](../../../it/images/banners/banners-edit-banner-details-tab.png)

- **Max. Impressioni** Il numero di Impressioni acquistate per questo
  Banner. Le impressioni sono il numero di volte che un Banner verrà visualizzato
  su una pagina. Seleziona la casella 'Illimitato' se è consentito un numero illimitato di
  Impressioni.
- **Totale Impressioni** Il numero di volte che questo Banner è stato
  visualizzato in una pagina web da un utente. Non è permesso alcun inserimento. Puoi reimpostare
  questo numero a 0 premendo il pulsante 'Reimposta impressioni'.
- **Totale Clic** Il numero di volte che questo Banner è stato cliccato. Non è
  permesso alcun inserimento. Puoi reimpostare questo numero a 0 premendo il
  pulsante *Reimposta clic*.
- **Cliente** Il Cliente di questo Banner. Seleziona uno dall'elenco a discesa
  dei Clienti esistenti.
- **Tipo di Acquisto:** Il tipo di acquisto del banner. Questo è utilizzato per
  indicare come il cliente del banner ha acquistato il tempo di visualizzazione per il
  banner.
- **Tracciare le Impressioni** Indica se tracciare o meno il numero di volte in cui il
  banner viene visualizzato ai visitatori del sito web.
- **Tracciare i Clic** Indica se tracciare o meno il numero di volte in cui il
  banner viene cliccato dai visitatori del sito web.

## Suggerimenti

- I banner sono posizionati su pagine specifiche aggiungendo Moduli di tipo *Banners* utilizzando la lista dei Moduli.
- Se hai una serie di banner che desideri visualizzare su una o più pagine in ordine casuale:
  1. Crea i banner che desideri includere, assicurandoti che abbiano lo stesso Cliente e Categoria.
  2. Crea un Modulo Banner per questo Cliente e Categoria, e nella Assegnazione al Menu seleziona le Voci di Menu per il modulo da visualizzare.
  3. Nel Modulo Banner, imposta il valore *Randomise* su *Sticky, Randomise*.

  Con queste impostazioni, i diversi banner per quel Cliente e Categoria verranno visualizzati sulle pagine selezionate in ordine casuale.

*Tradotto da openai.com*

