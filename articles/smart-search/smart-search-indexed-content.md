<!-- Filename: Help4.x:Smart_Search:_Indexed_Content / Display title: Ricerca Intelligente: Contenuto Indicizzato  -->

## Descrizione

La pagina *Ricerca Intelligente: Contenuti Indicizzati* mostra un elenco di tutti gli elementi di contenuto 
che sono stati indicizzati in Ricerca Intelligente.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri di Elenco](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni delle Colonne dell'Elenco](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordinamento degli Elementi dell'Elenco](jdocmanual?article=help/common-elements/list-ordering).
* [Paginazione dell'Elenco](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* Se sei nuovo a Ricerca Intelligente dovresti leggere la
  [guida rapida a Ricerca Intelligente](https://docs.joomla.org/Smart_Search_quickstart_guide).

## Come accedere

- Seleziona **Componenti → Ricerca Intelligente → Indice** dal menu dell'Amministratore.

## Schermata

![ricerca intelligente contenuto indicizzato](../../../it/images/smart-search/smart-search-indexed-content.png)

## Crea un Indice

Seleziona il pulsante **Indice** sulla Barra degli Strumenti. Questo aprirà una finestra che mostrerà
i progressi dell'operazione di indicizzazione. L'operazione di indicizzazione può richiedere
tempo a seconda del numero di elementi di contenuto del sito e del numero di parole e frasi di ricerca contenute in ciascun elemento di contenuto. Una barra di progresso indicherà quanto
dell'operazione di indicizzazione è stato completato finora. Non chiudere questa finestra finché l'indicizzazione non è stata completata. Nei siti con una grande quantità di contenuti, questo può richiedere molto tempo (decine di minuti).

Dovresti eseguire l'indicizzatore dopo che è stato introdotto nuovo contenuto nel sito web
che la funzione Smart Search non rileva automaticamente. Ad esempio,
l'importazione in blocco di nuovi contenuti in cui l'importatore non attiva automaticamente
Smart Search per indicizzare ogni nuovo elemento di contenuto. NOTA: L'indicizzatore Smart Search può anche essere eseguito dall'interfaccia a riga di comando (CLI) se necessario. Vedi Impostazione dell'indicizzazione automatica di Smart Search.

## Barra degli strumenti

- **Indice** Esegue l'indicizzatore Smart Search. Apparirà una piccola finestra popup con una barra di avanzamento che procede man mano che l'indicizzazione elabora il contenuto del sito.
- **Azioni** Seleziona una casella di controllo per attivare l'elenco a discesa.
  - **Pubblica** Rende gli elementi selezionati disponibili ai visitatori del sito web.
  - **Sospendi pubblicazione** Rende gli elementi selezionati non disponibili ai visitatori del sito web.
- **Elimina** Elimina gli elementi di contenuto selezionati. Funziona con uno o più elementi di contenuto selezionati. Eliminare un elemento di contenuto da Smart Search lo elimina solo dall'indice e non influisce sull'elemento di contenuto stesso.
- **Manutenzione**
  - **Ottimizza**
  - **Pulisci indice** Pulisce l'indice di Smart Search svuotando tutte le tabelle dell'indice. Per continuare a utilizzare Smart Search, seleziona il pulsante Indice nella barra degli strumenti dopo la pulizia. ATTENZIONE: La pulizia dell'indice svuota anche i filtri dei contenuti. Devono essere reinseriti manualmente dopo un ciclo Pulisci-Indice.
- **Statistiche** Mostra alcune statistiche di base su Smart Search.

## Suggerimenti

- Se esegui l'indicizzatore e ottieni un errore di *undefined null*, controlla
  i permessi sulla directory `/logs` di Joomla. Il server web deve
  avere il permesso di scrittura su quella directory affinché l'indicizzatore funzioni.
- Se l'elenco è vuoto, assicurati che il plug-in di Smart Search sia
  stato abilitato.

*Tradotto da openai.com*

