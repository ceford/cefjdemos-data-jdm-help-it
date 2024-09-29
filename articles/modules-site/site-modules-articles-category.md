<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category / Display title: Moduli: Articoli - Categoria -->

## Descrizione

Il tipo di modulo *Articoli - Categoria* visualizza un elenco di articoli pubblicati
da una o più categorie.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Il Moduli: Scheda Moduli](jdocmanual?article=help/modules/modules-module-tab).
* [Il Moduli: Scheda Assegnazione Menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Il Moduli: Scheda Avanzata](jdocmanual?article=help/modules/modules-advanced-tab).
* [La Scheda Permessi](jdocmanual?article=help/common-elements/edit-permissions).

<!-- Da fare: Un tutorial per mostrare come utilizzare questo modulo -->

## Come Accedere

- Seleziona **Sistema → Gestisci Pannello → Moduli del Sito** dal menu
  Amministratore. Poi...
  - Per creare un nuovo modulo: seleziona il pulsante **Nuovo** dalla Barra degli Strumenti. Poi...
    - Seleziona il tipo di modulo richiesto.
  - Per modificare un modulo esistente:
    - Trova il modulo nell'elenco dei moduli installati e seleziona il
      link del titolo nella colonna **Titolo**.

## Schermata

![scheda del modulo di categoria degli articoli](../../../it/images/modules-site/modules-articles-category-module-tab.png)

## Campi del Modulo

- **Titolo** Il titolo del modulo. Questo è anche il titolo visualizzato per il modulo a seconda del campo modulo *Mostra Titolo*.

### Scheda Modulo

#### Pannello Sinistro

- **Modalità** Seleziona la modalità da utilizzare. Se viene scelta la modalità Normale, configura semplicemente il modulo e verrà visualizzato un elenco statico di Articoli sugli elementi del menu a cui assegni il modulo. Se viene scelta la modalità Dinamica, puoi comunque configurare il modulo normalmente, tuttavia ora l'opzione Categoria non verrà più utilizzata. Invece, il modulo rileverà dinamicamente se ci si trova in una vista Categoria e visualizzerà di conseguenza l'elenco degli articoli all'interno di quella Categoria. Quando viene scelta la modalità Dinamica, è meglio lasciare il modulo impostato per essere visualizzato su tutte le pagine, poiché deciderà dinamicamente se visualizzare o meno qualcosa.
- **Mostra sulla Pagina dell'Articolo** Questo elemento appare se viene selezionata la modalità *Dinamica*. Seleziona per Mostrare o Nascondere un elenco di Articoli dalle Pagine degli Articoli. Ciò significa che il modulo si visualizzerà dinamicamente solo sulle Pagine della Categoria.

### Scheda Opzioni di Filtraggio

![scheda opzioni di filtraggio della categoria di articoli](../../../it/images/modules-site/modules-articles-category-filtering-options-tab.png)

- **Articoli in Primo Piano** Mostra o nasconde o seleziona solo gli articoli in primo piano.
- **Conteggio** Il numero di elementi da visualizzare. Il valore predefinito di 0 visualizzerà tutti gli articoli.
- **Tipo di Filtraggio delle Categorie** Includi o escludi le categorie selezionate.
- **Categoria** Seleziona una o più categorie.
- **Articoli della Categoria Figlia** Includi o escludi gli articoli della categoria figlia.
- **Profondità della Categoria** Il numero di livelli di categoria figlia da restituire.
- **Tipo di Filtraggio dell'Autore** Includi o escludi articoli dagli autori selezionati.
- **Autori** Seleziona uno o più autori dall'elenco.
- **Tipo di Filtraggio degli Alias dell'Autore** Includi o escludi gli alias degli autori selezionati.
- **Alias Autori** Seleziona uno o più alias di autori dall'elenco.
- **ID di Articoli da Escludere** Inserisci ogni ID articolo da escludere su una nuova riga.
- **Filtraggio per Data** Seleziona il tipo di filtraggio per data.
- **Campo Intervallo di Date** Seleziona quale intervallo di campi data utilizzare.
- **Intervallo Data di Inizio** Se sopra è stato selezionato l'Intervallo di Date, inserisci una data di inizio.
- **Fino alla Data** Se sopra è stato selezionato l'Intervallo di Date, inserisci una data di fine.
- **Data Relativa** Se sopra è stata selezionata la Data Relativa, inserisci un valore numerico di giorni. I risultati verranno recuperati rispetto alla data corrente e al valore inserito.

### Scheda Opzioni di Ordinamento

![scheda opzioni di ordinamento della categoria di articoli](../../../it/images/modules-site/modules-articles-category-ordering-options-tab.png)

- **Campo Articolo per Ordinare** Seleziona un campo dall'elenco. L'ordinamento per Articoli in Primo Piano dovrebbe essere utilizzato solo quando l'opzione di filtraggio per Articoli in Primo Piano è impostata su *Solo*.
- **Direzione dell'Ordinamento** Seleziona la direzione di ordinamento degli articoli.

### Scheda Opzioni di Raggruppamento

![scheda opzioni di raggruppamento della categoria di articoli](../../../it/images/modules-site/modules-articles-category-grouping-options-tab.png)

- **Raggruppamento degli Articoli** Seleziona un metodo di raggruppamento degli articoli dall'elenco.
- **Direzione del Raggruppamento** Seleziona la direzione dell'ordinamento.
- **Formato di Visualizzazione Mese e Anno** Inserisci un formato data valido.

### Scheda Opzioni di Visualizzazione

![scheda opzioni di visualizzazione della categoria di articoli](../../../it/images/modules-site/modules-articles-category-display-options-tab.png)

- **Titoli Collegati** Mostra titoli come collegamenti agli articoli.
- **Data** Mostra o nascondi la data dell'articolo.
- **Campo Data** Seleziona il campo data da visualizzare.
- **Formato della Data** Inserisci un formato data valido.
- **Categoria** Mostra o nascondi il nome della categoria dell'articolo.
- **Visite** Mostra o nascondi le visite all'articolo.
- **Autore** Mostra o nascondi il nome dell'autore o dell'alias dell'autore.
- **Testo Introduttivo** Mostra o nascondi il testo introduttivo dell'articolo.
- **Limite Testo Introduttivo** Il numero massimo di caratteri da visualizzare.
- **Mostra "Leggi di più"** Mostra o nascondi il collegamento *Leggi di più...* se è stato fornito il testo principale dell'articolo.
- **Mostra Titolo con Leggi di più** Mostra o nascondi il titolo dell'articolo nel collegamento *Leggi di più...*.
- **Limite Leggi di più** Limita il numero di caratteri del titolo dell'articolo da visualizzare nel collegamento *Leggi di più...*.

*Tradotto da openai.com*
