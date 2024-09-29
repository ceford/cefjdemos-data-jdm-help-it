<!-- Filename: Help4.x:Menu_Item:_List_All_Categories / Display title: Elenca Tutte le Categorie -->

## Descrizione

Il tipo di voce di menu *Elenca tutte le categorie in una struttura ad albero di categorie dell'articolo* viene utilizzato per mostrare le categorie in un elenco gerarchico. A seconda delle opzioni selezionate per questo layout, puoi fare clic su un titolo di categoria per mostrare gli articoli in quella categoria.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La scheda Dettagli](jdocmanual?article=help/menu-items-common/menu-item-details).
* [La scheda Categoria](jdocmanual?article=help/menu-items-common/menu-item-category).
* [La scheda Layout Blog](jdocmanual?article=help/menu-items-common/menu-item-blog-layout).
* [La scheda Layout Elenchi](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [La scheda Opzioni](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [La scheda Integrazione](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [La scheda Tipo di collegamento](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [La scheda Visualizzazione Pagina](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [La scheda Metadati](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [La scheda Associazioni](jdocmanual?article=help/common-elements/edit-associations).
* [La scheda Assegnazione Moduli](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Come Accedere

Seleziona **Menu → \[nome del menu\]** dal menu dell'Amministratore.

Per aggiungere una Voce di Menu:

1.  Seleziona il pulsante **Nuovo** nella Barra degli strumenti.
2.  Seleziona il pulsante **Seleziona** del Tipo di Voce di Menu.
3.  Seleziona l'elemento **Articoli**.
4.  Seleziona l'elemento **Elenca Tutte le Categorie in un Albero di Categorie di Articoli**.

Per modificare una Voce di Menu:

- seleziona un **Titolo** dall'elenco.


## Screenshot

![Voci di Menu Elenco Articoli Tutte le categorie scheda dettagli](../../../it/images/menu-items/articles-list-all-categories-details-tab.png)

## Campi del Modulo

- **Titolo** Il titolo che verrà visualizzato per questo elemento di menu.
- **Alias** Il nome interno dell'elemento di menu. Normalmente, puoi lasciare
  questo campo vuoto e Joomla inserirà un valore predefinito con il Titolo in minuscolo
  e trattini al posto degli spazi.

### Scheda Dettagli

#### Pannello Sinistro

- **Tipo di Elemento di Menu** Il Tipo di Elemento di Menu selezionato quando questo elemento di menu
  è stato creato. Questo può essere uno dei tipi di elemento di menu core o un tipo di
  elemento di menu fornito da un'estensione installata.
- **Seleziona la Categoria di Livello Superiore**
  - *Radice* Includi tutte le categorie di articoli.
  - Altrimenti, seleziona la categoria di livello superiore desiderata. Tutte le categorie figlio
    della categoria selezionata verranno visualizzate nell'elemento di menu.
- **Link** Il link generato dal sistema per questo elemento di menu. Questo campo
  non può essere modificato ed è solo informativo.
- **Finestra di Destinazione** Seleziona dall'elenco a discesa.
- **Stile del Template** Seleziona dall'elenco a discesa.

#### Pannello Destro

- **Menu** Mostra in quale menu apparirà il link.

### Scheda Categorie

![Menu Item Articoli Elenca Tutte le Categorie  scheda categorie](../../../it/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Descrizione della Categoria di Livello Superiore** Mostra la descrizione della
  categoria di livello superiore.
- **Descrizione Alternativa** Inserisci una descrizione per sostituire la
  descrizione della categoria per l'elemento di menu.
- **Livelli di Sottocategorie** Controlla quanti livelli di sottocategorie
  mostrare.
- **Categorie Vuote** Mostra le categorie che non contengono articoli
  o sottocategorie.
- **Descrizioni delle Sottocategorie** Mostra la descrizione delle
  sottocategorie.
- **\# Articoli nella Categoria** Mostra il conteggio del numero totale di
  articoli in ogni categoria.

### Scheda Layout Blog

Le Opzioni di Layout Blog controllano l'aspetto della navigazione per categorie se
questo comporta un layout blog.

Il modulo del layout blog ha un layout diverso da quello degli Elementi Comuni
sopra ma i campi sono simili.

### Scheda Condivisa

Le Opzioni Condivise si applicano alle Opzioni Condivise in Elenco, Blog e In Primo Piano
a meno che non siano modificate dalle impostazioni del menu.

![Menu Item Articoli Elenca Tutte le Categorie  scheda condivisa](../../../it/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Paginazione** La Paginazione fornisce link di pagina in fondo alla
  pagina che permettono all'utente di navigare verso pagine aggiuntive. Questi sono
  necessari se gli Articoli non possono essere contenuti su una sola pagina.
  - *Nascondi* Link di paginazione non mostrati. *Nota* Gli utenti non potranno
    navigare verso pagine aggiuntive.
  - *Mostra* Link di paginazione mostrati se necessario.
  - *Auto* Link di paginazione mostrati se necessario.
- **Riepilogo Paginazione** Mostra il numero della pagina corrente e il totale delle pagine
  (per esempio, *Pagina 1 di 2*) in fondo a ogni pagina.

## Consigli

- Le categorie possono essere *annidate* in livelli, simili alle cartelle su un'unità
  disco. In teoria, non c'è un limite assoluto al numero di livelli
  che puoi avere. Tuttavia, come questione pratica è consigliato mantenere
  i livelli al minimo. Il layout Mostra Tutte le Categorie potrebbe non funzionare
  correttamente se il numero di livelli mostrati è superiore a 5.
- Se configuri i titoli delle categorie come linkabili, l'utente può esplorare
  la categoria. Quando lo fanno, vedranno normalmente o un elemento di menu Elenco Categorie
  o Blog Categoria, a seconda di quale opzione è selezionata. Se esiste un elemento
  di menu preesistente per questa categoria (ad esempio, un elemento di menu Blog Categoria),
  allora quell'elemento di menu verrà visualizzato nell'esplorazione e le opzioni impostate
  per quell'elemento di menu controlleranno la visualizzazione della pagina. Altrimenti, le opzioni 
  impostate per l'elemento di menu Mostra Tutte le Categorie corrente controlleranno la
  visualizzazione della pagina.
- Puoi impostare l'opzione per esplorare un elenco o un blog in 2 posti.
  - In *Articoli: Opzioni* puoi impostare il valore predefinito per tutte le categorie.
  - In *Categoria: Modifica* puoi impostare un valore per una categoria specifica. Se è 
    impostato, sovrascrive il valore predefinito.
- Per personalizzare un *Formato Data* puoi usare `D M Y` per giorno mese anno o `d-m-y`
  per una versione breve ad esempio 17-08-05. Se lasciato vuoto, viene utilizzata la traduzione
  della chiave DATE_FORMAT_LC1 dal tuo file di lingua.

*Tradotto da openai.com*

