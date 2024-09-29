<!-- Filename: Help4.x:Articles:_Edit / Display title: Articoli: Modifica -->

## Descrizione

Questa pagina viene utilizzata per aggiungere un nuovo articolo o modificare un articolo esistente, solitamente utilizzando un editor Wysiwyg. L'editor predefinito è TinyMCE, ma se sono installati altri editor, l'editor predefinito può essere impostato su qualcos'altro per l'intero sito o per singoli utenti.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Schema](jdocmanual?article=help/common-elements/edit-schema).
* [La Scheda Pubblicazione](jdocmanual?article=help/common-elements/edit-publishing).
* [La Scheda Associazioni](jdocmanual?article=help/common-elements/edit-associations).
* [La Scheda Permessi](jdocmanual?article=help/common-elements/edit-permissions).
* [Il Popup Cronologia delle Versioni](jdocmanual?article=help/common-elements/edit-version-history).

Oppure in articoli per gli Utenti:

* [Aggiungere un'Immagine a un Articolo](jdocmanual?article=user/articles/adding-an-image-to-an-article)

## Come Accedere

* Seleziona **Contenuto → Articoli** dal menu Amministratore. Oppure...
* Seleziona **Articoli** dalla Dashboard Principale. Poi...
    * Seleziona il **Titolo** di un articolo esistente nella lista per modificarlo. Oppure...
    * Seleziona il pulsante **Nuovo** nella Barra degli Strumenti per creare un nuovo articolo.
Puoi anche creare un nuovo articolo selezionando l'icona **+** nel Menu o nella Dashboard Principale.

## Schermata

![Schermata di modifica degli articoli](../../../it/images/articles/articles-edit-content-tab.png)

## Campi del Modulo

- **Titolo** Il titolo di questo articolo.
- **Alias** Il nome interno di questo articolo. Normalmente, puoi lasciare
  questo campo vuoto e Joomla inserirà un valore predefinito basato sul Titolo ma
  in minuscolo e con trattini al posto degli spazi.

### Scheda Contenuto

#### Pannello Sinistro

- **Testo dell'Articolo** Qui puoi inserire il contenuto dell'articolo.
  Joomla include 3 editor, l'Editor predefinito - TinyMCE
  è mostrato sopra.

  Il menu a tendina CMS Content consente di accedere a link verso un Articolo,
  Contatto, Campo, Immagine Media, Menu, Modulo, Interruzione di Pagina o Interruzione Continua.

  Il simbolo dell'ellissi (<span class="icon-ellipsis-h"></span>) alterna la visibilità
  degli strumenti extra.
- **Attiva/Disattiva Editor** Il pulsante sotto la finestra di modifica consente di alternare
  tra l'editor TinyMCE e nessun editor. Questo consente di vedere e
  talvolta correggere il codice HTML.

#### Pannello Destro

- **Stato** Lo stato di pubblicazione di questo articolo.
  - *Pubblicato* L'articolo è visibile nel Frontend del sito.
  - *Non Pubblicato* L'articolo non sarà visibile agli ospiti nel
    Frontend del sito. Potrebbe essere visibile agli utenti loggati con
    permesso di modifica dello stato dell'articolo.
  - *Archiviato* L'articolo non verrà più mostrato nei menu o nell'Elenco Categorie.
  - *Eliminato* L'articolo è cancellato dal sito ma ancora nel database.
- **Categoria** Seleziona la Categoria per questo articolo.
- **In Evidenza** Seleziona Sì se l'articolo verrà mostrato nel menu In Evidenza.
- **Accesso** Seleziona il livello di visualizzazione per questo articolo. I
  livelli di accesso dipendono da ciò che è stato configurato in Utenti: Livelli di Accesso.
- **Lingua** Seleziona la lingua per questo articolo. Mantieni il valore predefinito
  di 'Tutti' se non usi la funzione multilingua.
- **Tag** Assegna tag a questo articolo. Puoi selezionare un tag da una
  lista predefinita o
  inserire un nuovo tag digitando il nome nel campo e premendo invio.
- **Nota** Questo campo è normalmente per l'uso dell'amministratore (ad esempio,
  per documentare informazioni su questo articolo) e non viene mostrato nel
  Frontend.
- **Nota Versione** Campo opzionale per identificare la versione di questo
  articolo nella Storia delle Versioni dell'articolo.

### Scheda Immagini e Link

**Nota:** Questa scheda può essere nascosta in *Articolo: Opzioni* da un utente con
permessi Admin. Consente la visualizzazione di immagini e link negli articoli utilizzando
layout standardizzati.

![Scheda per modificare le immagini e link degli articoli](../../../it/images/articles/articles-edit-images-tab.png)

#### Immagine Introduttiva

- **Immagine Introduttiva** Fai clic sul pulsante Seleziona per selezionare un'immagine da
  visualizzare in una posizione fissa nel Testo Introduttivo di questo articolo. Questo
  aprirà una finestra che consente la selezione di un'immagine dalla cartella immagini.
- **Descrizione Immagine (Alt Text)** Imposta l'attributo alt per questa
  immagine. Un paio di parole descrittive per i lettori di schermo.
- **Nessuna Descrizione** Seleziona questa opzione nel raro caso di un'immagine puramente decorativa.
  Nota che se la Descrizione Immagine è vuota e l'opzione Nessuna Descrizione è deselezionata,
  l'immagine non soddisferà i criteri di accessibilità. Se è presente una descrizione dell'immagine,
  questa opzione non ha effetto.
- **Classe Immagine** Aggiungi qualsiasi classe CSS per uno stile personalizzato.
  Ad esempio, per il posizionamento dell'immagine utilizza float-start o float-end.
- **Didascalia** Crea una didascalia per questa immagine.

#### Immagine Articolo Completo

- **Immagine Articolo Completo** Fai clic sul pulsante Seleziona per selezionare un'immagine da
  visualizzare in una posizione fissa nel Testo Completo di questo articolo.
  Questo aprirà una finestra che consente la selezione di un'immagine dalla
  cartella immagini.
- **Descrizione Immagine (Alt Text)** Imposta l'attributo alt per questa
  immagine. Un paio di parole descrittive per i lettori di schermo.
- **Nessuna Descrizione** Seleziona questa opzione nel raro caso di un'immagine puramente decorativa.
  Nota che se la Descrizione Immagine è vuota e l'opzione Nessuna Descrizione è deselezionata,
  l'immagine non soddisferà i criteri di accessibilità. Se è presente una descrizione dell'immagine,
  questa opzione non ha effetto.
- **Classe Immagine** Aggiungi qualsiasi classe CSS per uno stile personalizzato.
  Ad esempio, per il posizionamento dell'immagine utilizza float-start o float-end.
- **Didascalia** Inserisci una didascalia opzionale per questa immagine.

#### Link A

- **Link A** L'URL per il primo link da visualizzare in una posizione fissa
  nel testo dell'articolo. Deve essere un URL completo, non relativo.
  Ad esempio, normalmente inizierà con `https:`.
- **Testo Link A** Il testo utilizzato per il Link A. Se vuoto, verrà
  visualizzato l'URL.
- **Finestra di Destinazione URL** Imposta il valore predefinito per la destinazione
  del primo Link in questo articolo. Le scelte sono:
  - *Apri nella finestra principale* Apre il link nella finestra del browser principale,
    sostituendo l'articolo Joomla corrente.
  - *Apri in una nuova finestra* Apre il link in una nuova finestra del browser.
  - *Apri in popup* Apre il link in una finestra del browser pop-up (senza
    controlli di navigazione completi).
  - *Modale* Apre il link in una finestra modale pop-up.

#### Link B, Link C

- Le stesse opzioni di Link A.

### Scheda Opzioni

**Nota**: Questa scheda può essere nascosta da un utente con permessi Admin in
Articolo: Opzioni. È un insieme di opzioni utilizzate per controllare come
l'articolo verrà mostrato nel Frontend.

![Scheda Opzioni](../../../it/images/articles/articles-edit-options-tab.png)

#### Layout

- **Layout** Usa un layout dalla vista articolo fornita o sovrascrivi nei template.
- **Titolo** Mostra il Titolo dell'Articolo.
- **Titoli Collegati** Mostra il titolo come un link all'articolo.
- **Tag** Inserisci tag per questo articolo. Seleziona i tag esistenti digitando
  le prime lettere o crea nuovi tag inserendoli qui.
- **Testo Introduttivo**
  - *Mostra* Il Testo Introduttivo dell'articolo verrà mostrato in una pagina che visualizza
    l'articolo completo.
  - *Nascondi* Solo la parte dell'articolo dopo l'interruzione Continua verrà
    mostrata in una pagina che visualizza l'articolo completo.
- **Posizione delle Informazioni dell'Articolo**
  - *Sopra* Aggiunge il blocco delle informazioni dell'articolo sopra il testo.
  - *Sotto* Aggiunge il blocco delle informazioni dell'articolo sotto il testo.
  - *Diviso* Divide il blocco delle informazioni dell'articolo in 2 blocchi separati.
    Un blocco è sopra e l'altro è sotto il testo.
- **Titolo delle Informazioni dell'Articolo** Visualizza 'Dettagli' in cima al blocco
  delle informazioni dell'articolo.

#### Categoria

- **Categoria** Mostra il Titolo della Categoria dell'Articolo.
- **Categoria Collegate** Mostra il titolo come un link a quella Categoria.
- **Categoria Genitore** Mostra il Titolo della Categoria Genitore dell'Articolo.
- **Categoria Genitore Collegate** Mostra il titolo come un link a quella Categoria.

#### Associazioni

- **Associazioni** Mostra le bandiere o il Codice della Lingua associata.
  Solo multilingua.

#### Autore

- **Autore** Mostra l'autore dell'Articolo.
- **Link alla Pagina di Contatto dell'Autore** Mostra come un link a un layout
  di Contatto per quell'autore. Nota: L'autore deve essere impostato come Contatto.

#### Data

- **Data di Creazione** Mostra la data di creazione dell'Articolo.
- **Data di Modifica** Mostra la data di modifica dell'Articolo.
- **Data di Pubblicazione** Mostra la data di inizio pubblicazione dell'Articolo.

#### Opzioni

- **Navigazione** Mostra i link di navigazione, *Prec* e/o *Succ*, quando
  visualizzi una pagina contenente l'articolo completo.
- **Visualizzazioni** Mostra il numero di volte l'articolo è stato visualizzato da un utente.
- **Link Non Autorizzati** Se Sì, verrà mostrato il Testo Introduttivo per gli articoli
  limitati. Cliccando sul link Continua, verrà richiesto agli utenti di accedere
  per visualizzare il contenuto completo dell'articolo.
- **Posizionamento dei Link**
  - *Sopra* I link vengono mostrati sopra il contenuto.
  - *Sotto* I link vengono mostrati sotto il contenuto.
- **Testo Continua** Personalizza il testo che viene mostrato per il testo predefinito
  'Continua'.
- **Titolo Pagina del Browser** Testo per il titolo della pagina del browser da utilizzare
  quando l'articolo viene visualizzato con un elemento di menu non articolo. Se vuoto,
  viene utilizzato il titolo dell'articolo.

### Scheda Campi

Questa sezione mostra i campi personalizzati che sono definiti per questo articolo. Questi
sono campi che non sono assegnati a un Gruppo di Campi. Ogni Gruppo di Campi, se definito,
apparirà come una scheda separata.

![Scheda Campi](../../../it/images/articles/articles-edit-fields-tab.png)

### Scheda Configura Schermata di Modifica

**Nota:** Questa può essere nascosta da un utente con permessi Admin nelle
Articolo: Opzioni.

![Scheda Configura schermata di modifica](../../../it/images/articles/articles-edit-editor-tab.png)

- **Opzioni di Pubblicazione** Se Nascondi, la scheda Opzioni di Pubblicazione
  non verrà mostrata nel Backend. Questo significa che gli utenti del Backend non
  potranno modificare i campi in questa scheda. Questi campi saranno sempre
  impostati ai loro valori predefiniti.
- **Opzioni dell'Articolo** Se Nascondi, la scheda Opzioni dell'Articolo
  non verrà mostrata nel Backend. Questo significa che gli utenti del Backend non
  potranno modificare i campi in questa scheda. Questi campi saranno sempre
  impostati ai loro valori predefiniti.
- **Immagini e Link Amministratore** Se Sì, verrà mostrata la scheda Immagini e Link.
- **Immagini e Link Frontend** Se Sì, la scheda Immagini e Link verrà
  mostrata nella schermata di modifica dell'articolo nel Frontend.

## Suggerimenti

- Ci sono 2 metodi per inserire un'immagine nell'articolo utilizzando l'editor TinyMCE.
  1. L'elenco a discesa *CMS Content* fornisce accesso alla schermata Media.
  2. L'elenco a discesa *Inserisci* è un semplice modulo che richiede l'URL dell'immagine.
    Viene utilizzato per immagini esterne.
- Un inserimento *Leggi di più* risparmia spazio in qualsiasi pagina di layout In Evidenza o Blog mostrando solo la prima parte di un Articolo. Gli inserimenti *Interruzione di pagina* forniscono la navigazione a più pagine per articoli lunghi. Entrambi possono essere utilizzati in un singolo articolo se desiderato. Ad esempio, una rottura *Leggi di più* potrebbe essere posizionata dopo il primo paragrafo e rotture *Interruzione di pagina* potrebbero essere posizionate dopo gruppi successivi di paragrafi per creare un articolo a più pagine. Nessuna navigazione delle pagine verrebbe visualizzata nella pagina In Evidenza o Blog fino a quando l'Utente non seleziona il link Leggi di più. In quel momento, il sommario dell'Articolo verrebbe visualizzato mostrando link a ogni pagina.

*Tradotto da openai.com*
