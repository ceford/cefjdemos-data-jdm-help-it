<!-- Filename: Help4.x:Component:_Fields / Display title: Componente: Campi -->

## Descrizione

I campi sono utilizzati per visualizzare attributi aggiuntivi di Articoli, Contatti o Utenti.
I dati vengono inseriti in un modulo di Modifica dell'Amministratore e visualizzati nel Sito. 
Un esempio:

Supponiamo che tu scriva articoli su aspetti della natura, a volte Fiori, a volte 
Animali. Un campo che potresti voler registrare e visualizzare per entrambi è il 
Nome Latino, che richiede un campo di testo. Un altro potrebbe essere l'Habitat: Bosco, Stagno, 
Prato, e così via, che richiede una lista a discesa. Per i fiori potresti voler
registrare la Stagione di Fioritura utilizzando 4 checkbox, uno per ogni stagione, o 12 
checkbox, uno per ogni mese.

I campi vuoti nel modulo di inserimento non vengono visualizzati nell'output del Sito, quindi 
potresti tenere tutti i campi in un lungo elenco. Tuttavia, di solito è meglio usare 
categorie per i tuoi Articoli, ad esempio Fiori e Animali. I campi possono essere assegnati 
a più di una Categoria. Quindi i campi Nome Latino e Habitat sarebbero assegnati 
a entrambi, ma la Stagione di Fioritura verrebbe assegnata solo alla categoria Fiori.

Se un campo non è assegnato a un gruppo, apparirà nel modulo di Modifica in una 
scheda Campi. Se un campo è assegnato a un gruppo, apparirà in una scheda con 
quel nome. Quindi, per il gruppo Fiori sembra opportuno creare un gruppo 
denominato Dati dei Fiori (o semplicemente Fiori, anche se usare lo stesso nome per cose diverse può creare confusione). E per gli altri campi comuni potresti usare un gruppo Natura.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [Filtri di Elenco](jdocmanual?article=help/common-elements/list-filters).
* [Intestazioni delle Colonne di Elenco](jdocmanual?article=help/common-elements/list-column-headers).
* [Ordinamento degli Elementi di Elenco](jdocmanual?article=help/common-elements/list-ordering).
* [Paginazione dell'Elenco](jdocmanual?article=help/common-elements/list-pagination).
* [Elaborazione in Batch dell'Elenco](jdocmanual?article=help/common-elements/list-batch-process).

### Articolo Correlato

* C'è un esempio più lungo sull'uso di [Campi e Gruppi di Campi](jdocmanual?article=user/fields/fields-and-field-groups)
* C'è un articolo della Rivista della Comunità che include l'utilizzo di campi personalizzati 
in una categoria per [Creare un banner dalla descrizione della categoria di Joomla](https://magazine.joomla.org/all-issues/july-2024/create-a-banner-from-joomla-s-category-description).

## Come Accedere

* Seleziona **Contenuti → Campi** dal menu dell'Amministratore.
* Seleziona **Articoli** dall'elenco a discesa *Articoli/Categorie*.
  * Seleziona il pulsante **Nuovo** nella *Toolbar* per aggiungere un nuovo campo.
  * Seleziona un **Titolo** dall'elenco per modificare un campo esistente.

**Nota:** C'è un elenco a discesa che consente la creazione di Campi per una
Categoria e Mail nel componente Contatti. Richiedono un po' di esperienza di codifica per preparare i sovrascrittura dei template adatti.

## Screenshot

![Elenco dei campi degli articoli](../../../it/images/fields/articles-fields-list.png)

Ci sono 16 tipi di campo disponibili, ciascuno implementato come un plugin. È probabile che ne diventino disponibili altri in futuro.

*Tradotto da openai.com*

