<!-- Filename: Help4.x:Tags:_New_or_Edit / Display title: Etichette: Nuova o Modifica -->

## Descrizione

La pagina *Tag: Nuovo o Modifica* viene utilizzata per aggiungere o modificare tag che possono essere utilizzati per visualizzare il contenuto del sito per nome del tag.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).

## Come Accedere

- Seleziona **Componenti → Tag** nel menu dell'Amministratore. Poi
  - Seleziona il pulsante '**Nuovo'** nella Barra degli Strumenti per creare un nuovo Tag.
  - Seleziona il Titolo di un Tag dalla colonna **Titolo** dell'elenco per modificare
    un tag esistente.

## Screenshot

![modifica dettagli del tag nella scheda tag](../../../it/images/tags/tags-edit-tag-details-tab.png)

## Campi del Modulo

- **Titolo** Il nome di questo elemento. Questo campo è obbligatorio.
- **Alias** Il nome interno dell'elemento. Normalmente, puoi lasciare
  questo campo vuoto e Joomla riempirà automaticamente con un valore di default che è il Titolo in minuscolo e con trattini al posto degli spazi.

### Scheda Dettagli Tag

#### Pannello Sinistro

- **Descrizione** Indica lo scopo di questo tag.

#### Pannello Destro

- **Parente** L'elemento (categoria, voce di menu, ecc.) che è il
  genitore dell'elemento che viene modificato.
- **Stato** Lo stato di pubblicazione dell'elemento.
- **Accesso** Il livello di accesso per la visualizzazione di questo elemento.
- **Lingua** La lingua dell'elemento.
- **Nota** Questo campo è solitamente per l'uso dell'amministratore del sito (ad esempio, per documentare informazioni su questo elemento) e non viene mostrato nel Frontend del sito.
- **Nota Versione** Campo opzionale per identificare questa versione dell'elemento nella finestra della Cronologia Versioni dell'elemento.

### Scheda Opzioni

![tags edit tag options tab](../../../it/images/tags/tags-edit-options-tab.png)

#### Pannello Opzioni

- **Layout** Utilizza un layout dalla vista del componente fornito o sovrascritture nei template.
- **Classe CSS per il link del tag** Aggiungi classi CSS specifiche per il link del tag.
  Se lasciato vuoto, *label label-info* sarà aggiunto dal layout di tag predefinito.

#### Pannelli Immagini

- **Immagine Anteprima** L'immagine che verrà visualizzata come parte della lista.
- **Float** Attributo float per l'immagine.
- **Alt** Testo alternativo per l'immagine.
- **Didascalia** La didascalia per l'immagine.
- **Immagine Completa** Un'immagine che verrà visualizzata nella vista singola del tag.

### Scheda Pubblicazione

![tags edit tag publishing tab](../../../it/images/tags/tags-edit-publishing-tab.png)

#### Pannello Pubblicazione

- **Data di Creazione** Data in cui è stato creato l'elemento (Articolo, Categoria, ecc.).
- **Creato da** Nome dell'utente Joomla che ha creato questo elemento. Questo campo predefinito è l'utente attualmente connesso. Se desideri cambiarlo a un altro utente, clicca sul pulsante Seleziona Utente per selezionare un altro utente.
- **Creato da Alias** Questo campo opzionale ti permette di inserire un alias per questo Autore per questo Articolo. Ciò ti permette di mostrare un nome Autore diverso per questo Articolo.
- **Data di Modifica** Data dell'ultima modifica.
- **Modificato da** Nome utente che ha effettuato l'ultima modifica.
- **Revisione** ...
- **Visite** Il numero di volte che l'elemento è stato visualizzato.
- **ID** Questo è un numero identificativo unico per questo elemento assegnato automaticamente da Joomla. Viene utilizzato per identificare l'elemento internamente e non puoi cambiare questo numero. Quando crei un nuovo elemento, questo campo mostra "0" fino a quando non salvi la nuova voce, momento in cui viene assegnato un nuovo ID.

#### Pannello Metadata

- **Meta Descrizione** Un paragrafo opzionale da utilizzare come descrizione della pagina nell'output HTML. Generalmente, verrà visualizzato nei risultati dei motori di ricerca. Se inserito, questo crea un elemento meta HTML con un attributo name di `<description>` e un attributo content pari al testo inserito.
- **Parole Chiave** Inserimento opzionale di parole chiave. Devono essere inserite separandole con virgole (ad esempio: gatti, cani, animali domestici) e possono essere inserite in maiuscolo o minuscolo. (Ad esempio: *CANI* corrisponderà a *cani* o *Cani*). Le parole chiave possono essere utilizzate in vari modi:
  1.  Per aiutare i motori di ricerca e altri sistemi a classificare il contenuto dell'Articolo.
  2.  In combinazione con i tag dei Banner, per visualizzare Banners specifici in base al contenuto dell'Articolo. Ad esempio, se hai un Banner con un annuncio per prodotti per cani e un altro Banner per prodotti per gatti, puoi far visualizzare il Banner dei cani quando un Utente visualizza un Articolo relativo ai cani e il Banner dei gatti per un Articolo relativo ai gatti. Per fare ciò, devi:
      - Aggiungere le parole chiave "cane" e "gatto" agli Articoli appropriati.
      - Aggiungere i Tag "cane" e "gatto" ai Banners appropriati in Modifica Banners.
      - Impostare il parametro del modulo Banner 'Cerca per Tag' su "Sì" nella lista Moduli del sito: Banners.
  3.  Solo per articoli, in combinazione con il modulo Articoli Correlati, per visualizzare Articoli che condividono almeno una parola chiave in comune. Ad esempio, se l'Articolo corrente visualizzato ha le parole chiave "gatti, cani, scimmie", qualsiasi altro Articolo con almeno una di queste parole chiave verrà mostrato nel modulo 'Articoli Correlati'.
- **Autore** Inserimento opzionale di un nome Autore nei metadata. Se inserito, questo crea un elemento meta HTML con il nome attributo 'autore' e il contenuto come inserito qui.
- **Robot** Le istruzioni per i 'robot' web che visitano questa pagina.
  - *index, follow* Indicizza questa pagina e segui i link su questa pagina.
  - *noindex, follow* Non indicizzare questa pagina, ma segui comunque i link sulla pagina. Ad esempio, potresti fare questo per una pagina della mappa del sito dove vuoi che i link siano indicizzati ma non vuoi che questa pagina appaia nei motori di ricerca.
  - *index, nofollow* Indicizza questa pagina, ma non seguire alcun link sulla pagina. Ad esempio, potresti voler fare questo per un calendario eventi, dove vuoi che la pagina appaia nei motori di ricerca, ma non vuoi indicizzare ogni evento.
  - *noindex, nofollow* Non indicizzare questa pagina né seguire alcun link sulla pagina.
  - *Usa Globale* Impostato nella Configurazione Globale: Impostazioni Metadata.

*Tradotto da openai.com*

