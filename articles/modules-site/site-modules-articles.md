<!--
{
    "source": "https://docs.joomla.org/Help5.x:Site_Modules:_Articles",
    "title": "Moduli: Articoli",
    "description": " ",
    "author": ""
}
-->

## Descrizione

Il modulo **Articoli** visualizza un elenco di articoli. È destinato a sostituire
altri cinque moduli per gli articoli:

* [Moduli: Articoli - Archiviati](jdocmanual?article=help/modules-site/site-modules-articles-archived).
* [Moduli: Articoli - Categoria](jdocmanual?article=help/modules-site/site-modules-articles-category).
* [Moduli: Articoli - Più recenti](jdocmanual?article=help/modules-site/site-modules-articles-latest).
* [Moduli: Articoli - Più letti](jdocmanual?article=help/modules-site/site-modules-articles-most-read).
* [Moduli: Articoli - Newsflash](jdocmanual?article=help/modules-site/site-modules-articles-newsflash).

Le opzioni del modulo **Articoli** sono configurate principalmente tramite quattro schede:

- La *scheda Opzioni di filtraggio* viene utilizzata per specificare quali articoli visualizzare.
- La *scheda Opzioni di visualizzazione* specifica come vengono visualizzati gli articoli nel modulo e quali dettagli vengono inclusi.
- La *scheda Opzioni di ordinamento* viene utilizzata per configurare la precedenza degli articoli.
- La *scheda Opzioni di raggruppamento* viene utilizzata per configurare la precedenza degli articoli.

**Importante:** il modulo viene visualizzato solo quando sono presenti uno o più articoli corrispondenti da visualizzare. Se è vuoto, il modulo non viene visualizzato.

### Elementi comuni

Alcuni elementi di questa pagina sono trattati in articoli della Guida separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La scheda Moduli: Moduli](jdocmanual?article=help/modules/modules-module-tab).
* [La scheda Moduli: Assegnazione menu](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [La scheda Moduli: Avanzate](jdocmanual?article=help/modules/modules-advanced-tab).
* [La scheda Permessi](jdocmanual?article=help/common-elements/edit-permissions).

## Come accedere

- Seleziona **Contenuti → Moduli del sito** o **Sistema → Pannello di gestione → Moduli del sito**
  dal menu Amministratore oppure **Pannello del sito → Moduli** dalla Dashboard principale.
  Quindi...
  - Per creare un nuovo modulo: seleziona il pulsante **Nuovo** dalla barra degli strumenti nell'elenco
    *Moduli*. Quindi...
     - Seleziona il modulo **Articoli**.
  - Per modificare un modulo esistente: trova il modulo nell'elenco dei moduli installati
    e seleziona il collegamento del titolo nella colonna **Titolo**.

## Schermata

![Modulo Articoli, scheda modulo](../../../it/images/modules-site/site-modules-articles/01-module-tab.png)

## Campi del modulo

### Scheda Modulo

#### Pannello sinistro

- **Modalità**
  - La *Modalità normale* configura il modulo per visualizzare un elenco statico di articoli.
  - La *Modalità dinamica* configura il modulo per rilevare se sta utilizzando o meno una vista Categoria e visualizzerà di conseguenza l'elenco degli articoli all'interno di tale categoria. Quando si sceglie la Modalità dinamica, è consigliabile lasciare il modulo impostato per essere visualizzato su tutte le pagine, poiché deciderà dinamicamente se visualizzare o meno qualcosa.
- **Articoli da visualizzare** Il numero massimo di articoli da visualizzare.
- **Tipo di filtraggio della categoria** Specifica come vengono filtrati gli articoli in base alle categorie fornite nel campo *Categoria*.
  - *Inclusivo* Vengono visualizzati solo gli articoli delle categorie specificate.
  - *Esclusivo* Gli articoli delle categorie specificate vengono esclusi.
- **Categoria** Mostra o esclude gli articoli delle categorie selezionate. Funziona in aggiunta agli altri parametri di filtraggio.
- **Articoli delle sottocategorie** Visibile solo quando il parametro *Escludi o includi articoli* è impostato su *Includi*. Include o esclude gli articoli delle categorie che sono sottocategorie delle categorie fornite nel campo *Categoria*.
- **Profondità della categoria** Visibile solo quando il parametro *Articoli delle sottocategorie* è impostato su *Includi*. Specifica quanti livelli di sottocategorie vengono utilizzati.
- **Escludi o includi articoli** Include o esclude articoli specifici.
- **Articoli da includere** Visibile solo quando il parametro *Escludi o includi articoli* è impostato su *Includi*. Se vuoto, vengono inclusi tutti gli articoli; altrimenti vengono inclusi solo gli articoli selezionati.
- **Escludi articolo corrente** Visibile solo quando il parametro *Escludi o includi articoli* è impostato su *Escludi*. Esclude o include l'articolo corrente.
- **Articoli da escludere** Visibile solo quando il parametro *Escludi o includi articoli* è impostato su *Escludi*. Specifica gli articoli da escludere dall'elenco.

### Scheda Opzioni di visualizzazione

![Scheda del modulo del modulo Articoli](../../../it/images/modules-site/site-modules-articles/02-display-options-tab.png)

- **Solo titolo (elenchi)** (*Sì/No*). Se impostato su *Sì*, l'elenco degli articoli è costituito esclusivamente dai titoli degli articoli, collegati all'articolo. Tutte le altre opzioni sono nascoste.
- **Layout**
  - *Verticale* Gli articoli vengono visualizzati in un'unica colonna verticale.
  - *Orizzontale* Gli articoli vengono visualizzati in un massimo di 1-4 colonne verticali, a seconda della larghezza del modulo; la larghezza del modulo è determinata dalla posizione del modulo, dal layout della pagina, dal template, dalla larghezza dello schermo, dalla larghezza di visualizzazione del browser e da altri fattori. 
- **Numero massimo di colonne** Questa opzione viene visualizzata solo quando il Layout è impostato su Orizzontale. Specifica il numero massimo di colonne in un layout orizzontale (*2–4*).
- **Titolo dell'articolo** Mostra o nasconde il titolo dell'articolo.
- **Livello dell'intestazione** Questa opzione viene visualizzata solo quando *Titolo dell'articolo* è impostato su *Mostra*. Specifica il livello dell'intestazione HTML del titolo dell'articolo (*h1–h5, nessuno*). 
- **Link al titolo** Questa opzione viene visualizzata solo quando *Titolo dell'articolo* è impostato su *Mostra*. 
  - *Sì* Il titolo è un collegamento ipertestuale all'articolo.
  - *No* Il titolo non è un collegamento ipertestuale all'articolo.
- **Autore** Mostra o nasconde l'autore dell'articolo.
- **Categoria** Mostra o nasconde la categoria dell'articolo.
- **Link alla categoria** Viene visualizzato solo se *Categoria* è mostrato.
  - *Mostra* Collega il titolo della categoria alla relativa pagina.
  - *Nascondi* Mostra il titolo della categoria, ma non lo collega.
- **Data** Mostra o nasconde la data dell'articolo.
- **Campo data** Questa opzione viene visualizzata solo quando *Data* è impostato su *Mostra*. Specifica quale data dell'articolo visualizzare: *Data di creazione/Data di modifica/Data di inizio pubblicazione*.
- **Formato data** Questa opzione viene visualizzata solo quando *Data* è impostato su *Mostra*. Specifica il formato della data, ad esempio Y-m-d H-i-s. Per informazioni sulla formattazione, consultare il [manuale PHP](https://www.php.net/manual/en/datetime.format.php).
- **Visualizzazioni** Mostra o nasconde il numero di volte in cui l'articolo è stato visualizzato.
- **Layout delle informazioni sull'articolo** Viene visualizzato solo se uno dei campi dei metadati precedenti (*Autore, Categoria, Data o Visualizzazioni*) è mostrato. Specifica come visualizzare i metadati dell'articolo:
  - *Più righe* Ogni parametro viene visualizzato sulla propria riga.
  - *Riga singola* I parametri vengono visualizzati uno accanto all'altro su un'unica riga, che può andare a capo a seconda delle loro dimensioni e della larghezza del modulo.
- **Tag** Mostra o nasconde i tag dell'articolo.
- **Attiva gli eventi dei plugin** Impostare su *Sì* per attivare eventi aggiuntivi dei plugin e visualizzare contenuti aggiuntivi, come campi personalizzati o informazioni sulle votazioni.
- **Testo introduttivo** Mostra o nasconde il testo introduttivo dell'articolo. La quantità di testo visualizzata è controllata dal *parametro Limite del testo introduttivo (caratteri)*.
- **Limite del testo introduttivo (caratteri)** Questa opzione viene visualizzata solo quando *Testo introduttivo* è impostato su *Mostra*. Specifica il numero di caratteri introduttivi visualizzati. Se impostato su 0, viene visualizzato il testo dell'intero articolo. 
- **Mostra immagini dell'articolo** Questa opzione viene visualizzata solo quando *Testo introduttivo* è impostato su *Mostra* e *Limite del testo introduttivo (caratteri)* è impostato su zero (che visualizza il testo completo dell'articolo). Se impostato su *Mostra*, le immagini dell'articolo vengono visualizzate insieme al testo.
- **Mostra immagine introduttiva/completa** Visualizza l'immagine introduttiva dell'articolo, l'immagine completa o nessuna immagine sopra il titolo e i dettagli dell'articolo.
- **Link "Leggi tutto"** Mostra o nasconde un link "Leggi tutto" sotto i dettagli dell'articolo.
- **Leggi tutto con titolo** Questa opzione viene visualizzata solo quando l'opzione *Leggi tutto* è impostata su *Mostra*. Aggiunge il titolo al link *Leggi tutto*.
- **Limite di "Leggi tutto" (caratteri)** Questa opzione viene visualizzata solo quando l'opzione *Leggi tutto con titolo* è impostata su *Mostra*. Specifica il numero massimo di caratteri del titolo da visualizzare nel link *Leggi tutto*.

### Scheda Opzioni di filtraggio

![Scheda del modulo del modulo Articoli](../../../it/images/modules-site/site-modules-articles/03-filtering-options-tab.png)

- **Articoli in evidenza**
  - *Mostra* Consente la visualizzazione degli articoli in evidenza nell'elenco.
  - *Nascondi* Esclude gli articoli in evidenza dall'elenco.
  - *Solo* Mostra nell'elenco solo gli articoli in evidenza.
- **Articoli archiviati** Specifica come visualizzare gli articoli archiviati nell'elenco.
  - *Nessuno* Esclude gli articoli archiviati dall'elenco.
  - *Solo* Mostra nell'elenco solo gli articoli archiviati.
- **Tag** Se specificato, limita l'elenco ai soli articoli che hanno uno o più dei tag specificati.
- **Tipo di filtraggio per autore** Filtra l'elenco per autore.
  - *Inclusivo* Limita l'elenco ai soli articoli degli autori specificati.
  - *Esclusivo* Esclude gli articoli degli autori specificati.
  - *Solo dall'utente corrente* Visualizza solo gli articoli scritti dall'utente corrente.
- **Autori** Elenco degli autori da includere o escludere. 
- **Tipo di filtraggio per alias autore** Filtra l'elenco per alias autore.
  - *Inclusivo* Limita l'elenco ai soli articoli degli alias autore specificati.
  - *Esclusivo* Esclude gli articoli degli alias autore specificati.
- **Alias autore** Elenco degli alias autore da includere o escludere. 
- **Filtraggio per data** Specifica come filtrare gli articoli per data.
  - *Disattivato* Nessun filtraggio per data.
  - *Intervallo di date* Limita l'elenco agli articoli con date comprese nell'intervallo di date specificato. 
  - *Data relativa* Limita l'elenco agli articoli che rientrano in un numero specificato di giorni rispetto alla data corrente.
- **Campo dell'intervallo di date** Questa opzione viene visualizzata solo quando *Filtraggio per data* è impostato su *Intervallo di date* o *Data relativa*. Specifica quale data dell'articolo utilizzare per il filtraggio per data (*Data di creazione/Data di modifica/Data di inizio pubblicazione*).
- **Inizio intervallo di date** Questa opzione viene visualizzata solo quando *Filtraggio per data* è impostato su *Intervallo di date*. Specifica la data e l'ora di inizio del filtro per intervallo di date.
- **Alla data** Questa opzione viene visualizzata solo quando *Filtraggio per data* è impostato su *Intervallo di date*. Specifica la data e l'ora di fine del filtro per intervallo di date.
- **Data relativa** Questa opzione viene visualizzata solo quando *Filtraggio per data* è impostato su *Data relativa*. Specifica il numero di giorni relativi alla data corrente da includere nell'elenco degli articoli.

### Scheda Opzioni di ordinamento

![Scheda del modulo del modulo Articoli](../../../it/images/modules-site/site-modules-articles/04-ordering-options-tab.png)

- **Campo dell'articolo per cui ordinare**
  - *Ordine degli articoli* L'ordine in cui gli articoli sono disposti manualmente nella schermata *Contenuti > Articoli* dell'amministratore.
  - *Ordine degli articoli in evidenza* L'ordine in cui gli articoli in evidenza sono disposti nella schermata *Contenuti > Articoli in evidenza* dell'amministratore.
  - *Visualizzazioni* Ordinamento in base al numero di visualizzazioni della pagina.
  - *Titolo* Ordinamento in base al titolo dell'articolo.
  - *ID* Ordinamento in base al numero ID dell'articolo.
  - *Alias* L'alias di navigazione dell'articolo.
  - *Data di creazione/Data di modifica/Data di inizio pubblicazione/Data di fine pubblicazione* Ordinamento in base alla data dell'articolo.
  - *Casuale* Ordinamento casuale ogni volta che si accede o si aggiorna la pagina. *Direzione di ordinamento* viene ignorata.

### Scheda Opzioni di raggruppamento

![Scheda del modulo del modulo Articoli](../../../it/images/modules-site/site-modules-articles/05-grouping-options-tab.png)

Il *Campo di raggruppamento per data* e il *Formato di visualizzazione di mese e anno* sono visibili solo quando è selezionato un raggruppamento correlato alla data.

- **Raggruppamento degli articoli**
  - *Nessuno* Nessun raggruppamento.
  - *Anno* Visualizza l'anno come intestazione.
  - *Mese e anno* Visualizza il mese e l'anno come intestazione.
  - *Autore* Visualizza l'*Alias autore* o l'*Autore* come intestazione. 
  - *Categoria* Le categorie vengono visualizzate come intestazioni.
  - *Tag* I tag vengono visualizzati come intestazioni. Gli articoli con più tag vengono visualizzati sotto più intestazioni.
- **Campo di raggruppamento per data** Visualizzato solo quando è selezionato *Anno* o *Mese e anno*. La data dell'articolo in base alla quale raggruppare (*Data di creazione/Data di modifica/Data di inizio pubblicazione*).
- **Formato di visualizzazione di mese e anno** Visualizzato solo quando è selezionato *Anno* o *Mese e anno*. Specifica come visualizzare l'intestazione di mese e anno. Per informazioni sulla formattazione, consultare il [manuale PHP](https://www.php.net/manual/en/datetime.format.php).
- **Direzione del raggruppamento** Specifica come ordinare le intestazioni dei gruppi (*Crescente/Decrescente*).

## Schermata del frontend

*Le immagini del sito frontend di esempio sono state ottenute con il template Cassiopeia.*

Modulo Articoli nella barra laterale destra che mostra solo i titoli.

![Schermata del sito del modulo con solo i titoli degli articoli](../../../en/images/modules-site/site-modules-articles/06-site-titles.png)

Modulo Articoli nella barra laterale destra che mostra titolo, autore e data.

![Schermata del sito del modulo con titolo, autore e data degli articoli](../../../en/images/modules-site/site-modules-articles/07-title-author-date.png)

Modulo Articoli nella posizione principale superiore che mostra il testo introduttivo e l'immagine, nonché un pulsante *Leggi tutto*.

![Schermata del sito del modulo nella posizione superiore e del pulsante Leggi tutto](../../../en/images/modules-site/site-modules-articles/08-top-text-image-readmore.png)

Modulo Articoli nella posizione principale superiore configurato per un layout orizzontale con testo introduttivo e immagine, nonché un pulsante *Leggi tutto*.

![Schermata del sito del modulo con testo introduttivo dell'articolo, immagine e pulsante Leggi tutto](../../../en/images/modules-site/site-modules-articles/09-text-image-readmore.png)

## Esempi di configurazione

Il modulo Articoli mostra un elenco di articoli in diversi formati e layout. È stato progettato con l'obiettivo di creare un singolo modulo altamente configurabile, in grado di sostituire le funzionalità limitate di cinque moduli Articoli separati. Questa sezione offre semplici esempi di configurazione del modulo per ciascuno di questi ruoli.

## Articoli - Archiviati

Il modulo *Articoli - Archiviati* mostra un elenco di intestazioni mese/anno per i mesi che contengono articoli archiviati. L'intestazione è un link alla vista degli articoli archiviati, in cui vengono visualizzati i singoli articoli. Il modulo *Articoli* può essere configurato per ottenere un risultato simile.

**Impostazioni di configurazione**

| Scheda             | Parametro          | Impostazione |
|-------------------|--------------------|---------|
| Opzioni di visualizzazione   | Solo titolo (elenchi) | Sì     |
| Opzioni di filtraggio | Articoli archiviati  | Solo    |
| Opzioni di raggruppamento  | Raggruppamento articoli   | Mese e anno |
| Opzioni di raggruppamento  | Formato di visualizzazione mese e anno | F, Y |

![Confronto degli articoli archiviati utilizzando ciascun metodo](../../../en/images/modules-site/site-modules-articles/10-config-archived.png)

<big>*Note*</big>

Il modulo *Articoli - Archiviati* mostra un singolo link a una pagina degli articoli archiviati che visualizza l'elenco degli articoli archiviati, insieme alla possibilità di modificare la data dell'archivio. Il modulo *Articoli* mostra direttamente l'elenco degli articoli; il raggruppamento per mese e anno è facoltativo. L'elenco può essere filtrato con precisione utilizzando i numerosi controlli disponibili ed è disponibile un'ampia gamma di opzioni di visualizzazione per mostrare ulteriori dettagli degli articoli. 

## Articoli - Categoria

Il modulo *Articoli - Categoria* mostra un elenco di link agli articoli appartenenti a una categoria specificata.

**Impostazioni di configurazione**

| Scheda             | Parametro          | Impostazione |
|-----------------|--------------------|----|
| Modulo          | Categoria           | [specificare la categoria e le sottocategorie desiderate]|
| Opzioni di visualizzazione | Solo titolo (elenchi) | Sì |

![Confronto degli articoli per categoria utilizzando ciascun metodo](../../../en/images/modules-site/site-modules-articles/11-config-category.png)

## Articoli - Più recenti

Il modulo *Articoli - Più recenti* mostra un elenco di link agli articoli più recenti.

**Impostazioni di configurazione**

| Scheda              | Parametro          | Impostazione |
|------------------|--------------------|----|
| Opzioni di visualizzazione  | Solo titolo (elenchi) | Sì |
| Opzioni di ordinamento | Campo articolo in base a cui ordinare | Data di inizio pubblicazione|
| Opzioni di ordinamento | Direzione di ordinamento | Decrescente |

![Confronto degli articoli più recenti utilizzando ciascun metodo](../../../en/images/modules-site/site-modules-articles/12-config-latest.png)

<big>*Note*</big>

Il modulo *Articoli* non offre l'ordinamento *Modificati* presente nel modulo *Articoli - Più recenti*, ma dispone di diverse opzioni di ordinamento non presenti nel modulo *Articoli - Più recenti*. 

## Articoli - Più letti

Il modulo *Articoli - Più letti* mostra un elenco di link agli articoli con il maggior numero di visualizzazioni.

**Impostazioni di configurazione**

| Scheda              | Parametro          | Impostazione |
|------------------|--------------------|----|
| Opzioni di visualizzazione  | Solo titolo (elenchi) | Sì |
| Opzioni di ordinamento | Campo articolo in base a cui ordinare | Visualizzazioni |
| Opzioni di ordinamento | Direzione di ordinamento | Decrescente |

![Confronto degli articoli più letti utilizzando ciascun metodo](../../../en/images/modules-site/site-modules-articles/13-config-most-read.png)

## Articoli - Newsflash

Il modulo *Articoli - Newsflash* visualizza il testo di uno o più articoli. Per impostazione predefinita, viene mostrato solo il testo dell'articolo; tuttavia, può essere configurato per mostrare il titolo, le immagini, i link "Leggi tutto" e altro ancora. In questo caso è configurato per visualizzare il titolo titolo e il testo di più articoli. In questo esempio, il modulo *Articoli* è configurato per replicare questo comportamento di base.

**Impostazioni di configurazione**

| Scheda            | Parametro          | Impostazione |
|------------------|--------------------|----|
| Opzioni di ordinamento | Campo dell'articolo per cui ordinare | Data di inizio pubblicazione |
| Opzioni di ordinamento | Direzione dell'ordinamento | Decrescente |
| Opzioni di visualizzazione  | Solo titolo (elenchi) | No |
| Opzioni di visualizzazione  | Link del titolo         | No |
| Opzioni di visualizzazione  | Testo introduttivo          | Mostra |
| Opzioni di visualizzazione  | Limite del testo introduttivo (caratteri) | 0 (per testo illimitato) |

![Confronto tra i newsflash di articoli utilizzando ciascun metodo](../../../en/images/modules-site/site-modules-articles/14-config-news-flash.png)

*Tradotto da openai.com*