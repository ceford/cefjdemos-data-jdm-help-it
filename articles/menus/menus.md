<!-- Filename: Help4.x:Menus / Display title: Menu -->

## Descrizione

I menu permettono a un utente di navigare attraverso il sito. Un menu è un oggetto che contiene uno o più elementi di menu. Ogni elemento di menu punta a una pagina logica sul sito. Un modulo di menu è necessario per posizionare il menu sulla pagina. Un menu può avere più di un modulo. Per esempio, un modulo potrebbe mostrare solo gli elementi di menu di primo livello e un secondo modulo potrebbe mostrare gli elementi di menu di livello 2.

La pagina *Menu* fornisce una panoramica dei menu disponibili su un sito Joomla. Questo include i dettagli del numero di elementi pubblicati, non pubblicati e cestinati di ogni singolo menu, e i nomi dei moduli collegati.

Il processo per aggiungere un menu al sito è normalmente il seguente:

1.  Creare un nuovo menu (utilizzando questa pagina).
2.  Creare uno o più nuovi elementi di menu per il menu. Ogni elemento di menu avrà un tipo specifico di elemento di menu.
3.  Creare uno o più moduli di menu per visualizzare il menu sul sito.
    - Selezionare gli elementi di menu (pagine) che visualizzeranno il modulo.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri Lista](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni delle Colonne della Lista](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordinamento degli Elementi della Lista](jdocmanual?article=help/common-elements/list-ordering).
* [Paginazione della Lista](jdocmanual?article=help/common-elements/list-pagination).
## Come Accedere

- Seleziona **Menu → Gestisci** dal menu dell'Amministratore.

## Schermata

![lista dei menu](../../../it/images/menus/menus-list.png)

## Intestazioni delle Colonne

- **Titolo** Il nome del menu.
- **Elementi del Menu** Un link agli elementi del menu per il menu.
- **\# Pubblicati** Numero di elementi del menu pubblicati in questo menu.
- **\# Non Pubblicati** Numero di elementi del menu non pubblicati in questo menu.
- **\# Cestinati** Numero di elementi del menu cestinati in questo menu.
- **Moduli Collegati** Un menu a tendina mostra il nome, il livello di accesso e la posizione del template di qualsiasi modulo del menu associato al menu.

## Consigli
- I pulsanti numerati portano a un elenco filtrato degli elementi del menu per quel menu.
- Un menu dovrebbe avere un titolo breve e descrittivo adatto all'uso in elenchi e menu a tendina.
- La *Descrizione* è un promemoria utile dello scopo per cui è stato creato il menu.
- Se un menu non ha moduli associati, il pulsante della colonna *Moduli Collegati* è un collegamento a una finestra di dialogo modale *Aggiungi un modulo per questo menu*.
- Se elimini un menu esistente, non dimenticare che verranno eliminati anche tutti gli elementi del menu rispettivo. C'è un messaggio di avviso:

  **Sei sicuro di voler eliminare questi menu? Confermando, verranno eliminati i tipi di menu selezionati, tutti i loro elementi e i moduli del menu associati.**
- Il Menu Principale ha l'elemento di menu predefinito del sito. **Non dovrebbe essere cancellato**! L'elemento di menu predefinito definisce la pagina visualizzata durante una visita all'URL del dominio del sito, come `www.esempio.com`. Il sito non funzionerà se viene cancellato. Di solito è l'elemento di menu *Home*, ma può essere impostato su qualsiasi elemento di menu, incluso un elemento di menu in un menu nascosto. Se l'elemento di menu predefinito viene modificato, assicurati che anche quell'elemento di menu non venga eliminato!

*Tradotto da openai.com*

