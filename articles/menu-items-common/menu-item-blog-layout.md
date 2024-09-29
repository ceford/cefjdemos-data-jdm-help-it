<!-- Filename: Help6.x:Menu_Item_Blog_Layout / Display title: Layout del Blog Voce di Menu -->

## Descrizione

Tutti gli elementi del menu hanno un layout simile, ma alcuni campi del modulo e alcune schede cambiano a seconda del tipo. Questa pagina descrive la scheda **Layout del blog** utilizzata per i layout degli articoli.

## Come Accedere

* Seleziona qualsiasi **Menu del sito** dal menu dell'amministratore.
* Seleziona il pulsante **Nuovo** dalla barra degli strumenti.
* Seleziona qualsiasi tipo di voce di menu del componente che ha una scheda *Layout blog*.
* Seleziona la scheda **Layout blog**.

## Schermata

![Scheda Layout Blog Voce di Menu](../../../it/images/menu-items-common/articles-category-blog-blog-layout-tab.png)

## Campi del Modulo

### Scheda Layout Blog

- **\# Articoli Principali** Numero di articoli da mostrare utilizzando tutta la larghezza dell'area di visualizzazione principale. `0` significa che nessun articolo verrà mostrato utilizzando tutta la larghezza. Se un articolo ha un'interruzione *Leggi di più...*, verrà visualizzata solo la parte del testo prima dell'interruzione (il testo introduttivo).
- **Classe Articolo Principale** Puoi aggiungere qualsiasi classe CSS per le tue idee di stile. Aggiungi un bordo in alto con la classe boxed. Per la posizione dell'immagine, usa ad esempio image-start, image-end. Aggiungi image-alternate per l'ordinamento alternato delle immagini introduttive.
- **\# Articoli Introduttivi** Determina il numero di articoli da visualizzare dopo l'articolo principale. Questi articoli verranno visualizzati nel numero di colonne impostato nel parametro Colonne qui sotto. Se un articolo ha un'interruzione *Leggi di più...*, verrà visualizzato solo il testo prima dell'interruzione (testo introduttivo), seguito dal link *Leggi di più...*. L'ordine di visualizzazione degli articoli è determinato dai parametri Ordine Categoria e Ordine Articolo qui sotto.
- **Classe Articolo** Puoi aggiungere qualsiasi classe CSS per le tue idee di stile. Aggiungi un bordo in alto con la classe boxed. Per la posizione dell'immagine, usa ad esempio image-start, image-end. Aggiungi image-alternate per l'ordinamento alternato delle immagini introduttive.
- **\# Colonne** Il numero di colonne da utilizzare nell'area degli articoli introduttivi. Questo è normalmente compreso tra 1 e 3 (a seconda del modello che si sta utilizzando). Se viene utilizzato 1, gli articoli introduttivi verranno visualizzati utilizzando tutta la larghezza dell'area di visualizzazione, proprio come gli articoli principali.
- **Direzione Multi Colonna** Nei layout del blog a più colonne, se ordinare gli articoli verso il basso nelle colonne o attraverso le colonne.
  - *Verso il basso* Ordina gli articoli verso il basso nella prima colonna e poi passa alla colonna successiva.
  - *Attraverso* Ordina gli articoli attraverso le colonne e poi torna alla prima colonna.
- **\# Link** Il numero di link da visualizzare nell'area link della pagina. Questi link consentono all'utente di collegarsi ad articoli aggiuntivi, se ci sono più articoli di quanti possano entrare nella prima pagina del layout del blog.
- **Articoli in Evidenza**
  - *Mostra* Mostra articoli in evidenza e non in evidenza.
  - *Nascondi* Mostra solo articoli non in evidenza.
  - *Solo* Mostra solo articoli in evidenza.
- **Immagine Introduttiva Collegata** Se Sì, un clic sull'immagine introduttiva mostrerà l'articolo.
- **Includi Sottocategorie**
  - *Nessuna* Verranno mostrati solo articoli della categoria corrente.
  - *Tutte* Verranno mostrati tutti gli articoli della categoria corrente e di tutte le sottocategorie.
  - *1-5* Verranno mostrati tutti gli articoli della categoria corrente e delle sottocategorie fino a e includendo quel livello.
- **Ordine delle Categorie**
  - *Nessun Ordine* Gli articoli sono ordinati solo dall'ordine degli articoli, senza riguardo alla categoria.
  - *Titolo Alfabetico* Le categorie sono visualizzate in ordine alfabetico (A a Z).
  - *Titolo Ordine Alfabetico Inverso* Le categorie sono visualizzate in ordine alfabetico inverso (Z a A).
  - *Ordine Categoria* Le categorie sono ordinate secondo la colonna Ordine inserita in *Articoli: Categorie*.
- **Ordine Articolo**
  - *Ordine Articoli in Evidenza* Gli articoli sono ordinati in base alla colonna Ordine inserita in *Articoli: In Evidenza*.
  - *Più Recenti per Primi* Gli articoli sono visualizzati iniziando dal più recente e terminando con il più vecchio.
  - *Più Vecchi per Primi* Gli articoli sono visualizzati iniziando dal più vecchio e terminando con il più recente.
  - *Titolo Alfabetico* Gli articoli sono visualizzati per titolo in ordine alfabetico (A a Z).
  - *Titolo Ordine Alfabetico Inverso* Gli articoli sono visualizzati per titolo in ordine alfabetico inverso (Z a A).
  - *Autore Alfabetico* Gli articoli sono visualizzati per autore in ordine alfabetico (A a Z).
  - *Autore Ordine Alfabetico Inverso* Gli articoli sono visualizzati per autore in ordine alfabetico inverso (Z a A).
  - *Più Viste* Gli articoli sono visualizzati in base al numero di visualizzazioni, iniziando con quello con più visualizzazioni e terminando con quello con meno visualizzazioni.
  - *Meno Viste* Gli articoli sono visualizzati in base al numero di visualizzazioni, iniziando con quello con meno visualizzazioni e terminando con quello con più visualizzazioni.
  - *Ordine Casuale* Gli articoli sono visualizzati in ordine casuale.
  - *Ordine Articolo* Gli articoli sono ordinati in base alla colonna Ordine inserita in Articoli.
  - *Ordine Articolo Inverso* Gli articoli sono ordinati inversamente rispetto alla colonna Ordine inserita in Articoli.
- **Data per Ordinamento** La data utilizzata quando gli articoli vengono ordinati per data.
  - *Creato* Usa la data di creazione dell'articolo.
  - *Modificato* Usa la data di modifica dell'articolo.
  - *Pubblicato* Usa la data di inizio pubblicazione dell'articolo.
  - *Non Pubblicato* Usa la data di non pubblicazione dell'articolo.
- **Paginazione** La paginazione fornisce link alle pagine in fondo alla pagina che consentono all'utente di navigare verso pagine aggiuntive. Questi sono necessari se gli articoli non entrano in una sola pagina.
  - *Nascondi* Link di paginazione non mostrati. *Nota* Gli utenti non potranno navigare verso pagine aggiuntive.
  - *Mostra* Link di paginazione mostrati se necessario.
  - *Automatico* Link di paginazione mostrati se necessario.
- **Riepilogo Paginazione** Mostra il numero di pagina corrente e il numero totale di pagine (ad esempio, *Pagina 1 di 2*) in fondo a ciascuna pagina.

*Tradotto da openai.com*

