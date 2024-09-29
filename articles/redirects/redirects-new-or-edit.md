<!-- Filename: Help4.x:Redirects:_New_or_Edit / Display title: Reindirizzamenti: Nuovi o Modifica -->

## Descrizione

La pagina *Reindirizzamenti: Nuovo o Modifica* viene utilizzata per aggiungere un nuovo reindirizzamento o modificare uno esistente. L'URL dal quale vuoi reindirizzare non deve essere un URL funzionante sul tuo sito web che carichi effettivamente una pagina web. Può essere l'URL di una pagina web che hai disabilitato nell'interfaccia di amministrazione di Joomla! L'URL di origine che specifichi quando crei il reindirizzamento dovrebbe essere l'URL completo come lo scriveresti nel tuo browser web. Anche l'URL di destinazione che specifichi quando crei un reindirizzamento deve essere l'URL completo.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli strumenti](jdocmanual?article=help/common-elements/toolbars).

## Come accedere

- Seleziona **Sistema → Reindirizzamenti** dal menu dell'Amministratore. Poi...
  - Per creare un nuovo reindirizzamento, fai clic sul pulsante **Nuovo** nella barra degli strumenti. Oppure...
  - Per modificare un reindirizzamento esistente, fai clic sul suo link nella colonna **URL Scaduto**.

## Screenshot

![Reinvia collegamenti](../../../it/images/redirects/redirects-edit.png)

## Campi del modulo

### Modifica/Nuovo Link \#1 scheda

- **URL Scaduto** L'URL da reindirizzare.
- **Nuovo URL** L'URL a cui reindirizzare.
- **Stato** Stato della pubblicazione dell'elemento. I valori possibili sono:
  - *Abilitato* L'elemento è abilitato. Questo è l'unico stato che permette agli utenti regolari del sito di visualizzare questo elemento.
  - *Disabilitato* L'elemento è disabilitato.
  - *Archiviato* L'elemento è stato archiviato.
  - *Nel cestino* L'elemento è stato inviato al cestino.
- **Commento** Un commento visibile solo da un amministratore. È principalmente inteso solo per riferimento dell'amministratore.
- **ID** Questo è un numero di identificazione unico per questo elemento assegnato automaticamente da Joomla. Viene utilizzato per identificare l'elemento internamente e non è possibile cambiare questo numero. Quando si crea un nuovo elemento, questo campo visualizza "0" fino a quando non si salva la nuova voce, a quel punto viene assegnato un nuovo ID.
- **Data di creazione** Data in cui l'elemento (Articolo, Categoria, ecc.) è stato creato.
- **Data ultima modifica** Mostra l'ultima data in cui l'elemento è stato modificato.

## Come Creare un Redirect

1. Innanzitutto assicurati di aver abilitato l'opzione *Usa la riscrittura degli URL* nelle opzioni di Configurazione Globale della tua installazione Joomla!. Nota che abilitare solo l'opzione *Usa la riscrittura degli URL* non è sufficiente. Devi anche compiere il passo aggiuntivo di rinominare il file `htaccess.txt` nella directory del server web dove hai installato Joomla! in `.htaccess` o in qualsiasi altro nome di file richiesto dal tuo server web Apache per direttive di configurazione aggiuntive. Nel file di configurazione di Apache questa impostazione è chiamata `AccessFileName` e per impostazione predefinita è impostata su `.htaccess`.
2. Successivamente, apri la pagina *Redirect: Collegamenti* e seleziona il pulsante della toolbar *Nuovo*.
3. Nella pagina *Redirects: Nuovo*, inserisci le informazioni del redirect. Quando inserisci gli URL nei campi *URL Scaduto* e *Nuovo URL*, inserisci l'URL completo come faresti nel tuo browser web per visualizzarlo. L'*URL Scaduto* dovrebbe essere un URL che non risolve nessuna pagina web valida sul tuo sito. Puoi specificare un URL di origine per una pagina web Joomla! che hai messo in stato disabilitato nel backend dell'amministratore. Assicurati che l'opzione *Stato* sia impostata su **Abilitato**.
4. Seleziona il pulsante della toolbar **Salva & Chiudi** per salvare il nuovo redirect e metterlo in effetto.

## Consigli

- Quando si inseriscono gli URL nei campi *URL Scaduto/Sorgente* e *Nuovo URL/Destinazione*, inserire l'URL completo come lo si digiterebbe nel proprio browser web per visualizzare la pagina web.

*Tradotto da openai.com*

