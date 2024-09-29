<!-- Filename: Help6.x:Menu_Item_List_Layouts / Display title: Layout dell'elenco delle voci di menu -->

## Descrizione

Tutti gli elementi del menu hanno una disposizione simile, ma alcuni campi del modulo e alcune delle schede cambiano da tipo a tipo. Questa pagina descrive la scheda **List Layouts** utilizzata per i layout dell'elenco delle categorie.

## Come Accedere

* Seleziona qualsiasi **Menu del Sito** dal menu dell'Amministratore.
* Seleziona il pulsante **Nuovo** dalla Barra degli Strumenti.
* Seleziona qualsiasi elemento del menu del Componente che ha una scheda *Layouts Elenco*.
* Seleziona la scheda **Layouts Elenco**.

I parametri del layout dell'elenco variano da componente a componente. I seguenti esempi illustrano cosa aspettarsi:

### Layout Elenco Categoria Articoli

![Tipo di Elemento del Menu Categoria Elenco - scheda layouts elenco](../../../it/images/menu-items/articles-category-list-list-layouts-tab.png)

- **Visualizzazione Seleziona** Mostra o nascondi il controllo Visualizza # che consente all'utente di selezionare il numero di articoli da mostrare.
- **Campo Filtro** Mostra o nascondi un campo di testo nel Frontend dove un utente può filtrare gli articoli.
  - *Nascondi* Non mostrare il campo filtro.
  - *Titolo* Filtra per titolo dell'articolo.
  - *Autore* Filtra per nome dell'autore.
  - *Visualizzazioni* Filtra per numero di visualizzazioni dell'articolo.
  - *Tag* Filtra per tag dell'articolo.
  - *Mese (pubblicato)* Filtra per mese di pubblicazione degli articoli.
- **Intestazioni Tabella** Mostra o nascondi l'intestazione nell'elenco degli articoli nel Frontend.
- **Data** Mostra una data nell'elenco.
  - *Nascondi* Non mostrare alcuna data.
  - *Creato* Mostra la data di creazione.
  - *Modificato* Mostra la data dell'ultima modifica.
  - *Pubblicato* Mostra la data di inizio della pubblicazione.
- **Formato Data** Stringa opzionale per controllare il formato della data.
- **Visualizzazioni** Mostra o nascondi il numero di visualizzazioni degli articoli.
- **Autore** Mostra o nascondi il nome dell'autore.
- **Ordine Categoria**
  - *Nessun Ordine* Gli articoli sono ordinati solo per Ordine Articolo, senza considerare la Categoria.
  - *Titolo Alfabetico* Le categorie sono visualizzate in ordine alfabetico (A-Z).
  - *Titolo Alfabetico Inverso* Le categorie sono visualizzate in ordine alfabetico inverso (Z-A).
  - *Ordine Categoria* Le categorie sono ordinate secondo la colonna Ordine indicata in Articoli: Categorie.
- **Ordine Articolo**
  - *Ordine Articoli In Evidenza* Gli articoli sono ordinati secondo la colonna Ordine indicata in Articoli: In Evidenza.
  - *Più Recenti Prima* Gli articoli sono visualizzati a partire dal più recente fino al più vecchio.
  - *Più Vecchi Prima* Gli articoli sono visualizzati a partire dal più vecchio fino al più recente.
  - *Titolo Alfabetico* Gli articoli sono visualizzati in ordine alfabetico per Titolo (A-Z).
  - *Titolo Alfabetico Inverso* Gli articoli sono visualizzati in ordine alfabetico inverso per Titolo (Z-A).
  - *Autore Alfabetico* Gli articoli sono visualizzati in ordine alfabetico per Autore (A-Z).
  - *Autore Alfabetico Inverso* Gli articoli sono visualizzati in ordine alfabetico inverso per Autore (Z-A).
  - *Più Visualizzazioni* Gli articoli sono visualizzati per numero di visualizzazioni, iniziando dal più visualizzato fino al meno visualizzato.
  - *Meno Visualizzazioni* Gli articoli sono visualizzati per numero di visualizzazioni, iniziando dal meno visualizzato fino al più visualizzato.
  - *Ordine Casuale* Gli articoli sono visualizzati in ordine casuale.
  - *Ordine Articolo* Gli articoli sono ordinati secondo la colonna Ordine indicata in Articoli.
  - *Ordine Articolo Inverso* Gli articoli sono ordinati inversamente rispetto alla colonna Ordine indicata in Articoli.
- **Data per Ordinamento** La data utilizzata quando gli articoli sono ordinati per data.
  - *Creato* Utilizza la data di creazione dell'articolo.
  - *Modificato* Utilizza la data di modifica dell'articolo.
  - *Pubblicato* Utilizza la data di inizio della pubblicazione dell'articolo.
- **Paginazione** La paginazione fornisce link alle pagine in fondo alla pagina che permettono all'Utente di navigare tra le pagine aggiuntive. Questi sono necessari se gli Articoli non possono essere visualizzati tutti in una sola pagina.
  - *Nascondi* Link di paginazione non mostrati. *Nota:* Gli utenti non saranno in grado di navigare verso le pagine aggiuntive.
  - *Mostra* Link di paginazione mostrati se necessario.
  - *Automatico* Link di paginazione mostrati se necessario.
- **Sommario Paginazione** Mostra o nascondi il numero della pagina attuale e il totale delle pagine (ad es., "Pagina 1 di 2") in fondo a ogni pagina.
- **# Articoli da Elencare** Numero di articoli mostrati nell'elenco.
- **Articoli in Evidenza**
  - *Mostra* Visualizza articoli in evidenza e articoli non in evidenza.
  - *Nascondi* Visualizza solo articoli non in evidenza.
  - *Solo* Visualizza solo articoli in evidenza.

### Layout Elenco Contatti in Evidenza

![Elemento del Menu Contatti in Evidenza scheda layouts elenco](../../../it/images/menu-items/contacts-featured-contacts-list-layouts-tab.png)

- **Campo Filtro** Mostra o nascondi il filtro dell'elenco.
- **Visualizzazione Seleziona** Mostra o nascondi il numero di elementi da mostrare nell'elenco.
  - Se ci sono più elementi di questo numero, puoi usare i pulsanti di navigazione delle pagine (Inizio, Prec, Succ, Fine e numeri delle pagine) per navigare tra le pagine. Nota che se hai un gran numero di elementi, può essere utile utilizzare le opzioni Filtro, situate sopra le intestazioni delle colonne, per limitare quali elementi vengono visualizzati.
- **Intestazioni Tabella** Mostra o nascondi le intestazioni della tabella nell'elenco.
- **Posizione** Mostra o nascondi una colonna Posizione nell'elenco dei Contatti.
- **Email** Mostra o nascondi il display dell'Email.
- **Telefono** Mostra o nascondi il display del Telefono.
- **Mobile** Mostra o nascondi il display del Mobile.
- **Fax** Mostra o nascondi il display del Fax.
- **Città o Suburbio** Mostra o nascondi il display della Città o del Suburbio.
- **Stato o Contea** Mostra o nascondi il display dello Stato o della Contea.
- **Paese** Mostra o nascondi il display del Paese.
- **Paginazione** Mostra o nascondi il supporto di Paginazione. La paginazione fornisce link alle pagine in fondo alla pagina che permettono all'Utente di navigare tra le pagine aggiuntive. Questi sono necessari se gli elementi elencati non possono essere visualizzati tutti in una sola pagina.
  - *Usa Globale* Usa il valore predefinito dalla schermata delle opzioni del componente.
  - *Automatico* Link di paginazione mostrati se necessario.
  - *Mostra* Link di paginazione mostrati se necessario.
  - *Nascondi* Link di paginazione non mostrati. Nota: In questo caso, gli Utenti non saranno in grado di navigare verso le pagine aggiuntive.
- **Sommario Paginazione** Mostra o nascondi il numero della pagina attuale e il totale delle pagine (ad es., "Pagina 1 di 2") in fondo a ogni pagina. Usa Globale utilizzerà il valore predefinito dalla schermata delle opzioni del componente.

### Layout Elenco Feed di Notizie

![Elemento del Menu elenco tutte le Categorie dei Feed di Notizie scheda layouts](../../../it/images/menu-items/news-feeds-list-all-categories-tree-list-layouts-tab.png)

- **Campo Filtro** Mostra o nascondi un campo filtro per l'elenco.
- **Visualizzazione Seleziona** Mostra o nascondi il controllo Visualizza # che consente all'utente di selezionare il numero di elementi da mostrare nell'elenco.
- **Intestazioni Tabella** Mostra o nascondi le intestazioni della tabella sopra un elenco.
- **# Articoli** Mostra o nascondi il numero di Articoli in ciascun Feed di Notizie. Questo valore può essere sovrascritto in ciascun Feed di Notizie individualmente.
- **Link Feed** Mostra o nascondi gli URL dei link del feed.
- **Paginazione** Nascondi o mostra il supporto di Paginazione. La paginazione fornisce link alle pagine in fondo alla pagina che permettono all'Utente di navigare tra le pagine aggiuntive. Questi sono necessari se gli elementi elencati non possono essere visualizzati tutti in una sola pagina.
  - *Usa Globale:* Usa il valore predefinito dalla schermata delle opzioni del componente.
  - *Automatico:* Link di paginazione mostrati se necessario.
  - *Mostra:* Link di paginazione mostrati se necessario.
  - *Nascondi:* Link di paginazione non mostrati. Nota: In questo caso, gli Utenti non saranno in grado di navigare verso le pagine aggiuntive.
- **Risultati Paginazione** Mostra o nascondi il numero della pagina attuale e il numero totale di pagine (ad esempio *Pagina 1 di 2*) in fondo a ciascuna pagina. Usa Globale utilizzerà il valore predefinito dalla schermata delle opzioni del componente.

### Layout Elenco Tag

![Elenco compatto degli elementi con tag scheda dettagli](../../../it/images/menu-items/tags-compact-list-of-tagged-items-list-layouts-tab.png)

- **Immagine Elemento** Mostra o nascondi l'immagine per ciascun elemento.
- **Descrizione Elemento** Mostra o nascondi la descrizione per ciascun elemento nell'elenco. La lunghezza può essere limitata utilizzando l'opzione Massimo Caratteri.
- **Caratteri Massimi** Il numero massimo di caratteri da visualizzare nella descrizione di ciascun tag.
- **Campo Filtro** Mostra o nascondi il Campo Filtro, un campo di testo dove un utente può inserire un campo da utilizzare per filtrare gli articoli visualizzati nell'elenco.
- **Intestazioni Tabella** Mostra o nascondi le Intestazioni Tabella.
- **Visualizzazione Seleziona** Mostra o nascondi il controllo che consente all'utente di selezionare il numero di elementi da mostrare nell'elenco.
- **# Elementi da Elencare** Il numero di elementi con tag da elencare su una pagina.
- **Paginazione** Mostra o nascondi il supporto di Paginazione in fondo alla pagina che permette all'Utente di navigare verso le pagine aggiuntive.
- **Sommario Paginazione** Mostra o nascondi il numero della pagina attuale e il totale delle pagine (ad esempio, *Pagina 1 di 2*) in fondo a ciascuna pagina.
- **Data** Mostra o nascondi una data nell'elenco.
- **Formato Data** Stringa opzionale per controllare il formato della data (se mostrata). Se lasciato vuoto, la data utilizzerà il formato DATE_FORMAT_LC1 dal file della lingua (ad esempio, `D M Y` per *31 Dicembre 2012* o `m-d-y` per *12-31-12*).

*Tradotto da openai.com*

