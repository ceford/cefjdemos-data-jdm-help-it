<!-- Filename: Help4.x:Glossary / Display title: Glossario -->

Il Glossario di Joomla! è utile per spiegare i termini comuni utilizzati nei tutorial di Joomla!, nelle schermate di aiuto e nella documentazione avanzata.

## Lista di Controllo degli Accessi

## Alias

## Anchor

Un'ancora viene creata utilizzando il tag `<a>` in HTML. Un'ancora ti permette di posizionare un segnalibro all'interno di una pagina HTML. In Joomla!, puoi posizionare un'ancora all'interno di un articolo (ad esempio, utilizzando l'editor TinyMCE). Questo ti consente di creare un link che andrà direttamente a quel punto nell'articolo.

Il codice sorgente HTML per un'ancora è il seguente:

    <a name="my_anchor" title="My Anchor"></a>

Puoi collegarti a un'ancora all'interno della stessa pagina utilizzando il codice HTML

    <a href="#my_anchor" ></a>

Cliccando su quel link verrai portato direttamente alla posizione del tag ancora.

Puoi collegarti a un'ancora in una pagina diversa aggiungendo "#" più il nome dell'ancora alla fine dell'URL. Nell'esempio sopra, se l'URL dell'articolo fosse `http://www.mysite.com/my_article.html`, allora potresti collegarti direttamente all'ancora in quella pagina con l'URL `http://www.mysite.com/my_article.html#my_anchor`.

## Articolo

## Foglio di Stile a Cascata (CSS)

Un Foglio di Stile a Cascata o CSS è utilizzato per controllare la presentazione di una pagina XHTML. Ad esempio, un file CSS spesso controlla il font, i margini, il colore, la grafica di sfondo e altri aspetti dell'aspetto di una pagina web. CSS ti permette di separare il contenuto di una pagina XHTML dal suo aspetto. In Joomla!, i file CSS (per esempio, template.css) fanno normalmente parte del template.

**Vedi anche:** Template, Suffisso Classe Pagina, Suffisso Classe Modulo

## Categoria

Ogni parte di un sito web alimentato da Joomla! o di qualsiasi tipo di CMS ha bisogno di un metodo per visualizzare e memorizzare i suoi contenuti in modo logico. Il metodo usuale prevede l'uso di categorie e sottocategorie. Joomla! permette diversi modi per visualizzare e utilizzare i contenuti controllati dalla categorizzazione. Alcuni dei tipi di contenuto che hanno categorizzazione sono Articoli (il contenuto principale delle pagine web), Banner e Contatti.

Una categoria denominata *Senza categoria* è la categoria predefinita assegnata alla maggior parte dei tipi di contenuto. La categoria *Senza categoria* non è descrittiva e dovrebbe essere utilizzata solo quando necessario per tipi di contenuto che non rientrano in una categoria specifica.

Quando si creano e si assegnano categorie, è importante avere una struttura pianificata. Ad esempio, questo è un modo per categorizzare diversi articoli sugli uccelli:

- Crea due categorie di articoli principali denominate *Animali* e *Piante*.
- Sotto la categoria *Animali*, crea sottocategorie denominate *Uccelli* e 
  *Mammiferi*.
- Sotto la sottocategoria *Uccelli*, crea categorie intitolate *Falchi*, *Pappagalli* 
  e *Passeri*. Questa è la struttura risultante delle categorie:

```
- Animali
  - Uccelli
    - Falchi
    - Pappagalli
    - Passeri
  - Mammiferi
```

Ora puoi creare più articoli nelle sottocategorie Falchi, Pappagalli e Passeri utilizzando i diversi generi o nomi comuni dei tipi specifici di questi uccelli.

## Chrome

Le caratteristiche visibili dell'interfaccia grafica di un'applicazione sono talvolta
dette *chrome*.

## Componente

## Core

La parola *core* in Joomla! Si riferisce ai file distribuiti che sono necessari per creare e amministrare un sito web basato sul CMS Joomla. Il core di Joomla contiene tutte le funzionalità necessarie per creare e gestire un nuovo sito web in modo rapido e semplice.

## Prefisso della Tabella del Database

Il prefisso della tabella del database è una stringa (di pochi caratteri) anteposta
al nome delle tabelle di Joomla!. Utilizzare un prefisso consente di eseguire più
installazioni di Joomla! utilizzando un unico database.

Il prefisso della tabella del database può essere impostato durante l'installazione. Modificarlo
successivamente è possibile, ma richiede l'accesso al database tramite un
mezzo non-Joomla o un'estensione di Joomla come Akeeba Admin Tools e
causerà qualche tempo di inattività.

Gli sviluppatori di estensioni devono utilizzare la stringa `#__` per rappresentare il prefisso.
Questo verrà sostituito dal vero prefisso a runtime.

## Estensione

## LDAP


## Lingua

Le lingue sono forse il tipo di estensione più basilare e critico. Le lingue sono confezionate come pacchetto di lingua principale o pacchetto di lingua estensione. Questi pacchetti consistono in file INI che contengono coppie chiave/valore per fornire la traduzione delle stringhe di testo statiche all'interno del codice sorgente di Joomla!. Questo permette sia al nucleo di Joomla! che ai componenti e moduli di terze parti di essere internazionalizzati. I pacchetti di lingua principali includono anche un file meta XML che descrive la lingua e fornisce informazioni sui caratteri da utilizzare per la generazione del contenuto PDF.

## Menu

In Joomla!, un **Menu** è un modulo che contiene un insieme di **elementi del menu** utilizzati per la navigazione. Ogni elemento del menu definisce un URL a una pagina del sito. Contiene impostazioni che controllano la visualizzazione del contenuto e dello stile della pagina.

## Model-View-Controller

Joomla fa ampio uso del
<a href="http://en.wikipedia.org/wiki/Model-view-controller"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Model-View-Controller</a> design
pattern.

Quando Joomla viene avviato per elaborare una richiesta da parte di un utente, come un GET
per una particolare pagina, o un POST contenente dati di un modulo, una delle prime
cose che Joomla fa è analizzare l'URL per determinare quale
componente sarà responsabile dell'elaborazione della richiesta e trasferirà
il controllo a quel componente.

Se il componente è stato progettato secondo il pattern MVC, esso
passerà il controllo al controller. Il controller è responsabile di
analizzare la richiesta e determinare quale(i) modello(i) sarà necessario soddisfare
la richiesta e quale vista dovrebbe essere usata per restituire i risultati
all'utente.

Il modello incapsula i dati utilizzati dal componente. Nella maggior parte dei casi
questi dati proverranno da un database, sia il database Joomla, sia qualche
database esterno, ma è anche possibile che il modello ottenga i dati
da altre fonti, come attraverso un'API di servizi web che gira su un altro
server. Il modello è anche responsabile dell'aggiornamento del database dove
appropriato. Lo scopo del modello è quello di isolare il controller e
la vista dai dettagli di come i dati vengono ottenuti o modificati.

La vista è responsabile della generazione dell'output che viene inviato
al browser dal componente. Chiama il modello per qualsiasi informazione di cui
necessita e la formatta in modo appropriato. Per esempio, un elenco di elementi di dati
estratti dal modello potrebbe essere incapsulato in una tabella HTML dalla vista.

Poiché Joomla è progettato per essere altamente modulare, l'output dal
componente è generalmente solo parte della pagina web completa che l'utente
vedrà alla fine. Una volta che la vista ha generato l'output, il
componente passa il controllo nuovamente al framework di Joomla che poi carica
e esegue il template. Il template combina l'output del
componente, e qualsiasi modulo attivo nella pagina corrente, in modo che possa
essere consegnato al browser come una singola pagina.

Per fornire maggiore potenza e flessibilità ai web designer, che possono essere
interessati solo alla creazione di nuovi design piuttosto che alla manipolazione del
codice sottostante, Joomla divide la vista tradizionale in una vista separata
e layout. La vista estrae i dati dal modello, come in un pattern MVC
tradizionale, ma poi rende semplicemente disponibili quei dati al layout, che
è responsabile della formattazione dei dati per la presentazione all'utente. Il
vantaggio di avere questa divisione è che il sistema di template di Joomla
fornisce un meccanismo semplice per i layout di essere sovrascritti nel
template. Questi override del layout (spesso chiamati "template overrides"
perché fanno parte del template, sebbene in realtà sia il layout ad essere
sovrascritto) sono inclusi nel template e danno al designer del template un
controllo completo su tutto l'output dal core di Joomla e qualsiasi estensione di terze parti installata che rispetti il pattern di design MVC.

## Modulo

## Suffisso Classe Modulo

Un suffisso classe modulo è un parametro usato nei moduli per aggiungere una nuova classe CSS a un modulo. Viene utilizzato insieme agli stili definiti in un file user.css per cambiare l'aspetto standard di un modulo.

Il nuovo nome della classe può essere usato per aggiungere qualsiasi stile desiderato al modulo senza dover ricreare tutto il codice CSS esistente. Nota che, se crei un nuovo nome di classe, assicurati che abbia un nome unico e non entri in conflitto con nomi di classi esistenti.

## Posizione del Modulo

## Modulo chrome

## PHP

PHP è un linguaggio di scripting per computer progettato per creare pagine web dinamiche. PHP è ampiamente utilizzato per lo sviluppo web e può essere incorporato in HTML. Generalmente viene eseguito su un server web, prendendo come input il codice PHP e creando pagine web come output. Joomla! è principalmente scritto utilizzando il linguaggio PHP.

## Suffisso Classe Pagina

Un Suffisso Classe Pagina è un parametro utilizzato negli elementi di menu del contenuto per aggiungere una nuova classe CSS al layout della pagina. Viene utilizzato in combinazione con gli stili definiti in un file user.css per modificare l'aspetto standard di un modulo.

Il nuovo nome della classe può essere utilizzato per aggiungere qualsiasi stile desiderato alla pagina senza dover ricreare tutto il codice CSS esistente. Nota che, se crei un nuovo nome di classe, assicurati che abbia un nome univoco e che non entri in conflitto con nomi di classi esistenti.

Sure! Here is the translation:

## Patch

## Patch

## Plugin


## URL Amichevoli per i Motori di Ricerca

Gli URL amichevoli per i motori di ricerca sono un termine comunemente abbreviato come SEF URLs
o semplicemente SEF. Gli URL normali di Joomla! sembrano qualcosa del genere:

    http://www.tuosito.org/index.php?option=com_content&view=section&id=3&Itemid=41

Puoi opzionalmente far visualizzare gli URL come pagine HTML statiche come
questa:

    http://www.tuosito.org/faq.html

Ci sono opzioni integrate per generare URL SEF. Queste sono abilitate nelle 
*Impostazioni SEO* (Ottimizzazione per i Motori di Ricerca) nella scheda Sito della 
pagina di Configurazione Globale. Esistono anche estensioni di terze parti che creano 
URL SEF per Joomla!.

## Menu a tendina divisi

Un menu a tendina diviso è un menu in cui i diversi livelli di un singolo menu vengono visualizzati in due 
o più posizioni su una singola pagina web.

Ad esempio, un requisito comune è che un menu di elementi di primo livello compaia 
nella parte superiore della pagina. Quando uno degli elementi viene cliccato, l'utente 
viene portato a una pagina in cui un menu secondario, ad esempio sulla sinistra della pagina, 
mostra elementi di secondo livello all'interno dell'ambito dell'elemento di primo livello.

I menu appaiono in posizioni separate sulla pagina, ma sono correlati perché uno mostra solo 
elementi di primo livello mentre l'altro mostra elementi di secondo livello. Questa idea può essere 
estesa per includere menu per elementi di terzo livello e oltre.

Questo può essere implementato in Joomla utilizzando un singolo menu a più livelli, 
quindi creando più di un modulo di menu ciascuno riferito a un diverso livello.

## Modello

Un modello è un tipo di estensione Joomla! che controlla l'aspetto della pagina.
- Un modello del sito controlla l'aspetto pubblico del contenuto del sito.
- Un modello dell'amministratore controlla l'aspetto del sito per attività amministrative come: gestione di utenti, menu, articoli, categorie, moduli, componenti, plugin e modelli.

## Stile del modello

## Pacchetto di Aggiornamento

Un Pacchetto di Aggiornamento in Joomla! è un pacchetto di file che contiene
i file che sono stati modificati tra le versioni di Joomla!. Quando questo archivio viene
decompresso, sostituisce la vecchia versione dei file modificati con la nuova
versione. Ad esempio, se cinquanta file sono stati modificati tra la versione 5.1
e 5.2, il pacchetto di aggiornamento conterrebbe questi cinquanta file e istruzioni
su come eseguire l'aggiornamento. A volte ciò include aggiornamenti del database e
l'eliminazione di file non più utilizzati.

*Tradotto da openai.com*

