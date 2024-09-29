<!-- Filename: Help4.x:Articles:_Options / Display title: Articoli: Opzioni -->

## Descrizione

La pagina *Articoli: Opzioni* viene utilizzata per impostare i valori predefiniti globali per gli articoli.
Questi vengono utilizzati quando l'opzione *Usa globale* è selezionata in un elemento di menu degli Articoli. Ad esempio, per mostrare la *Data di Creazione* di un articolo nei tuoi elementi di menu Articoli, imposta questa opzione su *Mostra* qui e sarà il valore predefinito.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Permessi](jdocmanual?article=help/common-elements/edit-permissions).

## Come Accedere

Seleziona il pulsante **Opzioni** nella barra degli strumenti di qualsiasi pagina dell'elenco degli *Articoli*.

## Screenshot

![Screenshot delle opzioni degli articoli](../../../it/images/articles/articles-options-articles-tab.png)

## Campi del Modulo

### Scheda Articoli

Queste impostazioni si applicano ai layout degli articoli a meno che non vengano modificate per un elemento del menu o articolo specifico.

- **Scegli un Layout** Seleziona il valore predefinito per gli elementi del menu Articolo Singolo.
- **Titolo** Mostra il titolo dell'articolo.
- **Titoli Collegati** Mostra il titolo come un link all'articolo.
- **Testo di Intro**
  - **Mostra** Il testo di introduzione dell'articolo verrà mostrato nell'articolo completo.
  - **Nascondi** Solo la parte dell'articolo dopo il tag Leggi Tutto verrà mostrata nell'articolo completo.
- **Posizione delle Informazioni sull'Articolo**
  - **Sopra** Posiziona il blocco delle informazioni sull'articolo sopra il testo.
  - **Sotto** Posiziona il blocco delle informazioni sull'articolo sotto il testo.
  - **Diviso** Divide il blocco delle informazioni sull'articolo in 2 blocchi separati. Uno viene posizionato sopra e l'altro sotto il testo.
- **Titolo delle Informazioni sull'Articolo** Mostra la parola *Dettagli* sopra il blocco delle informazioni sull'articolo.
- **Categoria** Mostra il titolo della categoria dell'articolo.
  - **Collega Categoria** Mostra il titolo come un link a quella Categoria. Nota: Questo può essere impostato come layout a blog o a lista con l'opzione *Scegli un Layout* nella scheda Categoria.
- **Categoria Padre** Mostra il titolo della categoria padre dell'articolo.
  - **Collega Categoria Padre** Mostra il titolo come un link a quella Categoria. Nota: Questo può essere impostato come layout a blog o a lista con l'opzione *Scegli un Layout* nella scheda Categoria.
- **Associazioni** Mostra le bandiere associate o il codice della lingua. Multilingue solo.
  - **Usa Bandiere Immagini** Mostra la scelta della lingua come bandiere immagini se Associazioni è impostato su *Mostra*.
- **Autore** Mostra l'autore dell'articolo.
  - **Collega alla Pagina di Contatto dell'Autore** Mostra come un link a un layout di Contatto per quell'autore. Nota: L'autore deve essere configurato come Contatto. Inoltre, un link non verrà mostrato se c'è un valore di Alias Autore per il contatto.
- **Data di Creazione** Mostra la data di creazione dell'articolo.
- **Data di Modifica** Mostra la data di modifica dell'articolo.
- **Data di Pubblicazione** Mostra la data di inizio pubblicazione dell'articolo.
- **Navigazione** Mostra un link di navigazione *Precedente* o *Successivo*.
- **Link "Leggi Tutto"** Mostra il link Leggi Tutto per collegare la parte dell'articolo prima della pausa Leggi Tutto al resto dell'articolo.
- **Leggi Tutto con Titolo**
  - **Mostra** Il titolo dell'articolo è parte del link Leggi Tutto. Il link sarà nel formato "Leggi Tutto: \[titolo dell'articolo\]".
  - **Nascondi** Il link sarà "Leggi tutto".
- **Limite "Leggi Tutto" (caratteri)** Il numero massimo di caratteri del titolo da includere. Nota: Questo può prevenire che il testo di Leggi Tutto diventi eccessivamente lungo se l'articolo ha un titolo molto lungo.
- **Tag** Mostra i tag per ogni articolo.
- **Registra Visualizzazioni** Registra il numero di volte che l'articolo è stato visualizzato.
- **Visualizzazioni** Mostra il numero di volte che l'articolo è stato visualizzato da un utente.
- **Link Non Autorizzati**
  - **Sì** Il testo di introduzione per gli articoli limitati verrà mostrato. Cliccando sul link Leggi tutto verrà richiesto agli utenti di effettuare l'accesso per visualizzare l'intero contenuto dell'articolo.
  - **No** Gli articoli che l'utente non è autorizzato a visualizzare (in base al livello di accesso per la visualizzazione dell'articolo) non verranno mostrati.
- **Posizionamento dei Link**
  - **Sopra** I link sono mostrati sopra il contenuto.
  - **Sotto** I link sono mostrati sotto il contenuto.

### Scheda Layout di Modifica

Queste opzioni controllano il layout della pagina di modifica dell'articolo.

![Opzioni articoli scheda layout di modifica](../../../it/images/articles/articles-options-editing-layout-tab.png)

- **Permetti Captcha all'invio** Seleziona il plugin captcha che verrà utilizzato nel modulo di invio dell'articolo. Se *Usa Globale* è selezionato, assicurati che un plugin captcha sia selezionato nelle Impostazioni Globali.
- **Opzioni di Pubblicazione** Nascondi la scheda Opzioni di Pubblicazione nel Backend quando modifichi gli Articoli. Questo significa che gli utenti del Backend non potranno modificare i campi in questa scheda. Questi campi saranno sempre impostati sui loro valori predefiniti.
- **Opzioni Articolo** Nascondi la scheda Opzioni Articolo nel Backend quando modifichi gli Articoli. Questo significa che gli utenti del Backend non potranno modificare i campi in questa scheda. Questi campi saranno sempre impostati sui loro valori predefiniti.
- **Opzioni Schermata di Modifica** Nascondi la scheda Configura Schermata di Modifica quando modifichi gli Articoli.
- **Permessi Articolo** Nascondi la scheda Permessi quando modifichi gli Articoli.
- **Associazioni Multilingua** Nascondi la scheda Associazioni quando modifichi gli Articoli.
- **Abilita Versioni** Salva la cronologia delle versioni per Articoli e Categorie.
- **Versioni Massime** Il numero massimo di versioni da memorizzare per un Articolo o una Categoria. Se un Articolo o una Categoria viene salvato e il numero massimo di versioni è stato raggiunto, la versione più vecchia sarà automaticamente eliminata. Se impostato su "0", le versioni non verranno mai eliminate automaticamente.
- **Immagini e Link Frontend** Nascondi la scheda Immagini e Link nell'editor articoli del Frontend.
- **Immagini e Link Amministratore** Nascondi la scheda Immagini e Link nel Backend quando modifichi gli Articoli.
- **URL A Finestre di Destinazione** Imposta il valore predefinito per l'obiettivo per il primo link nell'articolo. Le scelte sono:
  - *Apri nella finestra principale* Apre nel browser principale, sostituendo l'articolo Joomla corrente.
  - *Apri in una nuova finestra* Apre il link in una nuova finestra del browser.
  - *Apri in popup* Apre il link in una finestra popup del browser (senza controlli di navigazione completi).
  - *Modal* Apre il link in una finestra popup modale.
- **URL B Finestre di Destinazione** Imposta il valore predefinito per l'obiettivo per il secondo link nell'articolo. Stesse opzioni di URL A.
- **URL C Finestre di Destinazione** Imposta il valore predefinito per l'obiettivo per il terzo link nell'articolo. Stesse opzioni di URL A.
- **Classe Immagine Intro** Imposta l'attributo classe per un'Immagine Intro selezionata nel campo Immagine Intro.
- **Classe Immagine Testo Completo** Imposta l'attributo classe per un'Immagine Articolo Completo selezionata nel campo Immagine Articolo Completo.

### Scheda Categoria

Queste impostazioni si applicano alle Opzioni della Categoria degli Articoli a meno che non vengano modificate dalla categoria individuale o dalle impostazioni del menu.

![Opzioni articoli scheda categoria](../../../it/images/articles/articles-options-category-tab.png)

- **Scegli un Layout** Seleziona il layout predefinito da mostrare quando un link Categoria è selezionato.
- **Titolo Categoria** Mostra il titolo della categoria.
- **Descrizione Categoria** Mostra la descrizione della categoria.
- **Immagine Categoria** Mostra l'immagine della categoria.
- **Livelli di Sottocategorie** Controlla quanti livelli di sottocategorie mostrare.
- **Categorie Vuote** Mostra le categorie che non contengono articoli o sottocategorie.
- **Messaggio Nessun Articolo** Mostra un messaggio "Non ci sono articoli in questa categoria".
- **Intestazione Sottocategorie** Mostra le Sottocategorie come sottointestazione nella pagina.
- **Descrizioni Sottocategorie** Mostra le descrizioni per le sottocategorie.
- **\# Articoli nella Categoria** Mostra un conteggio del numero totale di articoli in ciascuna categoria.
- **Tag** Mostra i tag per la categoria.

### Scheda Categorie

Queste impostazioni si applicano alle Opzioni delle Categorie degli Articoli, a meno che non vengano modificate dalla categoria individuale o dalle impostazioni del menu.

![Opzioni articoli scheda categorie](../../../it/images/articles/articles-options-categories-tab.png)

- **Descrizione Categoria di Livello Superiore** Mostra la descrizione per la categoria di livello superiore.
- **Livelli di Sottocategorie** Controlla quanti livelli di sottocategorie mostrare.
- **Categorie Vuote** Mostra le categorie che non contengono articoli o sottocategorie.
- **Descrizioni Sottocategorie** Mostra la descrizione per le sottocategorie.
- **\# Articoli nella Categoria** Mostra un conteggio del numero totale di articoli in ciascuna categoria.

### Scheda Layout Blog/In Evidenza

Queste impostazioni si applicano ai layout blog o in evidenza a meno che non siano modificate per un elemento del menu specifico.

![Opzioni articoli scheda layout blog e in evidenza](../../../it/images/articles/articles-options-blog-layouts-tab.png)

- **# Articoli Principali** Numero di Articoli da mostrare utilizzando l'intera larghezza dell'area di visualizzazione principale. "0" significa che nessun Articolo verrà mostrato utilizzando l'intera larghezza. Se un Articolo ha una pausa "Leggi di più...", verrà mostrata solo la parte del testo prima della pausa (il testo di introduzione).
- **Classe Articolo Principale** Aggiungi qualsiasi classe CSS per personalizzare il layout. Aggiungi un bordo in cima con la classe "boxed". Per la posizione dell'immagine usa per esempio "image-left", "image-right". Aggiungi "image-alternate" per l'ordinamento alternato delle immagini di introduzione.
- **# Articoli di Introduzione** Determina il numero di Articoli da visualizzare dopo l'Articolo principale. Questi Articoli verranno visualizzati nel numero di colonne impostato nel parametro Colonne qui sotto. Se un Articolo ha una pausa "Leggi di più...", verrà visualizzato solo il testo prima della pausa (testo di introduzione), seguito da un link "Leggi di più...". L'ordine con cui visualizzare gli articoli è determinato dai parametri Ordine Categoria e Ordine Articolo qui sotto.
- **Classe Articolo** Aggiungi qualsiasi classe CSS per lo stile personalizzato. Aggiungi un bordo in cima con la classe "boxed". Per la posizione dell'immagine usa per esempio "image-left", "image-right". Aggiungi "image-alternate" per l'ordinamento alternato delle immagini di introduzione.
- **# Colonne** Il numero di colonne da utilizzare nell'area Articoli di Introduzione. Normalmente è tra 1 e 3 (a seconda del template in uso). Se viene usato 1, gli Articoli di Introduzione verranno visualizzati utilizzando l'intera larghezza dell'area di visualizzazione, proprio come gli Articoli Principali.
- **Direzione Multi Colonna** Nei layout del blog multi-colonna, se ordinare gli articoli in giù per colonne o attraverso le colonne.
  - **Giù** Ordina gli articoli scendendo per la prima colonna e poi passando alla colonna successiva.
  - **Attraverso** Ordina gli articoli attraversando le colonne e poi ritornando alla prima colonna.
- **# Link** Il numero di link da visualizzare nell'area Link della pagina. Questi link consentono all'Utente di collegarsi a ulteriori Articoli, se ci sono più Articoli di quanti possano entrare nella prima pagina del Layout Blog.
- **Includi Sottocategorie**
  - **Nessuna** Verranno mostrati solo gli articoli della categoria corrente.
  - **Tutte** Verranno mostrati tutti gli articoli della categoria corrente e di tutte le sottocategorie.
  - **1-5** Verranno mostrati tutti gli articoli della categoria corrente e delle sottocategorie fino a quel livello incluso.
- **Immagine di Introduzione Collegata** Se Sì, un clic sull'immagine di introduzione mostra l'articolo.

### Scheda Layout Lista

Queste impostazioni si applicano alle Opzioni dei Layout Lista a meno che non vengano modificate per un elemento del menu o categoria specifica.

![Opzioni articoli scheda layout lista](../../../it/images/articles/articles-options-list-layouts-tab.png)

- **Mostra Selezione** Mostra il controllo Seleziona \# che consente all'utente di selezionare il numero di articoli da mostrare.
- **Campo Filtro** Mostra un campo di testo nel Frontend dove un utente può filtrare gli articoli. Opzioni nel menu di Backend.
  - **Nascondi** Non mostrare un campo filtro.
  - **Titolo** Filtra per titolo dell'articolo.
  - **Autore** Filtra per nome dell'autore.
  - **Visualizzazioni** Filtra per numero di visualizzazioni dell'articolo.
  - **Tag** Filtra per i tag dell'articolo.
  - **Mese (pubblicato)** Filtra per mese degli articoli pubblicati.
- **Intestazioni Tabella** Mostra un'intestazione nella lista degli articoli nel Frontend.
- **Data** Mostra una data nella lista.
  - **Nascondi** Non mostrare nessuna data.
  - **Creata** Mostra la data di creazione.
  - **Modificata** Mostra la data dell'ultima modifica.
  - **Pubblicata** Mostra la data di inizio pubblicazione.
- **Visualizzazioni** Mostra il numero di visualizzazioni per gli articoli.
- **Autore** Mostra il nome dell'autore.
- **\# Articoli da Elencare** Numero di articoli mostrati nell'elenco.

### Scheda Condivisi

Queste impostazioni si applicano alle Opzioni Condivise nei layout Lista, Blog e In Evidenza a meno che non vengano modificate dalle impostazioni del menu.

![Opzioni articoli scheda condivisi](../../../it/images/articles/articles-options-shared-tab.png)

- **Ordine delle Categorie**
  - **Nessun Ordine** Gli articoli sono ordinati solo per Ordine Articolo, senza riguardo per la Categoria.
  - **Titolo Alfabetico** Le categorie sono visualizzate in ordine alfabetico (A-Z).
  - **Titolo Alfabetico Inverso** Le categorie sono visualizzate in ordine alfabetico inverso (Z-A).
  - **Ordine Categoria** Le categorie sono ordinate secondo la colonna Ordine inserita in Articoli: Categorie.
- **Ordine degli Articoli**
  - **Più Recenti Prime** Gli articoli sono visualizzati iniziando con i più recenti e finendo con i più vecchi.
  - **Più Vecchi Prime** Gli articoli sono visualizzati iniziando con i più vecchi e finendo con i più recenti.
  - **Titolo Alfabetico** Gli articoli sono visualizzati per Titolo in ordine alfabetico (A-Z).
  - **Titolo Alfabetico Inverso** Gli articoli sono visualizzati per Titolo in ordine alfabetico inverso (Z-A).
  - **Autore Alfabetico** Gli articoli sono visualizzati per Autore in ordine alfabetico (A-Z).
  - **Autore Alfabetico Inverso** Gli articoli sono visualizzati per Autore in ordine alfabetico inverso (Z-A).
  - **Più Visualizzazioni** Gli articoli sono visualizzati in base al numero di visualizzazioni, iniziando con quello con più visualizzazioni e finendo con quello con meno visualizzazioni.
  - **Meno Visualizzazioni** Gli articoli sono visualizzati in base al numero di visualizzazioni, iniziando con quello con meno visualizzazioni e finendo con quello con più visualizzazioni.
  - **Ordinamento** Gli articoli sono ordinati secondo la colonna Ordine inserita in Articoli.
  - **Ordinamento Inverso** Gli articoli sono ordinati al contrario secondo la colonna Ordine inserita in Articoli.
- **Data per Ordinamento** La data utilizzata quando gli articoli sono ordinati per data.
  - **Creata** Usa la data di creazione dell'articolo.
  - **Modificata** Usa la data di modifica dell'articolo.
  - **Pubblicata** Usa la data di inizio pubblicazione dell'articolo.
- **Paginazione** La paginazione fornisce link alle pagine in fondo alla pagina che consentono all'Utente di navigare alle pagine aggiuntive. Necessaria se gli Articoli non entrano in una sola pagina.
  - **Nascondi** Link di paginazione non mostrati. Nota: Gli utenti non potranno navigare alle pagine aggiuntive.
  - **Mostra** Link di paginazione mostrati se necessario.
  - **Auto** Link di paginazione mostrati se necessario.
- **Riepilogo della Paginazione** Mostra il numero della pagina corrente e il totale delle pagine (es.: "Pagina 1 di 2") in fondo a ogni pagina.
- **Articoli In Evidenza**
  - **Mostra** Visualizza artic

## Suggerimenti

- Gli utenti principianti possono mantenere i valori predefiniti qui.
- Gli utenti esperti possono risparmiare tempo creando valori predefiniti appropriati qui. I nuovi elementi di menu e articoli potranno quindi utilizzare i valori predefiniti per la maggior parte delle opzioni.
- Tutti i valori impostati qui possono essere sovrascritti a livello di elemento di menu, categoria o articolo.

*Tradotto da openai.com*
