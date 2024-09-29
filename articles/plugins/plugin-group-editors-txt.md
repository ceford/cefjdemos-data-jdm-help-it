<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Editor_Group / Display title: Gruppo di Redattori -->

## Descrizione del Gruppo

I plugin dell'editor aiutano gli utenti a inserire testo con markup o layout per scopi speciali, come frammenti di HTML o codice. Per utilizzare un Editor, lo sviluppatore software contrassegna il campo di inserimento dati come tipo `Editor`. Se nessun plugin dell'editor è abilitato, viene visualizzato come un semplice campo di textarea. Con uno o più plugin dell'editor abilitati, viene utilizzato il plugin predefinito del sito, impostato nella Configurazione Globale, a meno che non venga sostituito dal plugin preferito dall'utente, impostato nel Profilo Utente. Joomla ha i tre plugin di editor principali elencati di seguito. Potrebbero essere disponibili ulteriori plugin di editor di terze parti. Alcuni editor hanno una selezione molto ampia di opzioni.

### Editor - CodeMirror

L'editor CodeMirror è un editor di codice che fornisce un editor più adatto per il codice sorgente. Ha la definizione della sintassi del codice per molti linguaggi di programmazione. Può mostrare tag non corrispondenti e aiuta anche a mantenere l'indentazione del codice coerente.

![Opzioni del modulo CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror.png)

- **Numeri delle righe** Visualizza i numeri delle righe nell'editor.
- **Raggruppamento del codice** Consente di raggruppare blocchi di codice.
- **Bordi** Marcatore di codice e raggruppamento del codice.
- **Evidenzia riga attiva** Aggiunge un'evidenziazione alla riga su cui si trova il cursore.
- **Evidenzia selezione corrispondente** Evidenzia le istanze della parola selezionata in tutto il documento.
- **Correggi tag** Evidenzia i tag corrispondenti.
- **Correggi parentesi** Evidenzia le parentesi corrispondenti.
- **Completamento tag** Completamento tag automatico.
- **Completamento parentesi** Completamento parentesi automatico.
- **Mappatura chiavi** Fa funzionare CodeMirror come altri editor popolari.
- **Attiva/disattiva schermo intero** Seleziona il tasto funzione da usare per attivare/disattivare la modalità schermo intero.
- **Usa modificatori** Seleziona eventuali tasti modificatori da usare con il tasto di attivazione/disattivazione schermo intero.

![Opzioni avanzate del modulo CodeMirror](../../../en/images/plugins/plugin-group-editor-codemirror-advanced.png)

- **Tema** Imposta i colori per l'editor.
- **Colore della riga attiva** Il colore da usare per evidenziare la riga attiva. Verrà visualizzato al 50% di opacità.
- **Colore dei tag corrispondenti** Il colore di sfondo da usare per evidenziare i tag corrispondenti. Verrà visualizzato al 50% di opacità.
- **Carattere** Il carattere da usare nell'editor. Se non installato, verrà caricato da https://www.google.com/fonts/.
- **Dimensione carattere (px)** La dimensione del carattere nell'editor.
- **Altezza delle righe (em)** L'altezza di una riga di testo. Questo in ems significa che 1.0 è uguale alla dimensione del carattere e 2.0 è uguale a 2 volte la dimensione del carattere.
- **Stile della barra di scorrimento** Seleziona lo stile della barra di scorrimento che desideri che CodeMirror utilizzi.
- **Anteprima** Esempio di come saranno visualizzati i campi dell'editor CodeMirror con le impostazioni correnti (salva per aggiornare).

### Editor - Nessuno

Questo plugin carica un editor di testo di base. Questa opzione può essere utilizzata quando si incolla del codice HTML da un'altra fonte e non si desidera che l'HTML venga alterato da un editor WYSIWYG. Questo plugin non ha opzioni.

### Editor - TinyMCE

L'editor TinyMCE è un editor WYSIWYG ed è l'editor predefinito per l'inserimento di HTML in Joomla!.

![Modulo delle opzioni del plugin TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce.png)

- **Imposta scheda selezionata** Seleziona la funzionalità *Set 2*, *Set 1* o *Set 0*. Con *Set 2* selezionato, vedi l'editor per l'uso *Pubblico*. *Set 1* selezionato è predefinito per Manager e Registrati, *Set 0* selezionato è predefinito per Amministratori, Editor e Super Utenti.

Ogni scheda ha una lunga lista di opzioni non illustrate qui. La seguente lista è una selezione.

- **Skin del sito** Scegli la skin che verrà applicata all'editor TinyMCE quando viene visualizzato nel tuo sito web.
- **Skin dell'amministratore** Scegli la skin che verrà applicata all'editor TinyMCE quando viene visualizzato nel tuo Backend di Amministrazione.
- **Modalità della barra degli strumenti** Controlla come visualizzare i pulsanti della barra degli strumenti non presenti nella prima riga.
- **Trascina e rilascia immagini** Abilita trascinamento e rilascio per il caricamento delle immagini.
- **Directory delle immagini** La directory con i file delle immagini da elencare relativa alla cartella delle immagini predefinita (impostata in Media > Opzioni).
- **Codifica delle entità** Controlla come vengono codificate le entità HTML. L'impostazione consigliata è `raw`. `named` = usa la codifica delle entità denominate (per esempio, `<`). `numeric` = usa la codifica HTML numerica (per esempio, `%03c`). raw = Non codificare le entità HTML. Si noti che la ricerca dei contenuti potrebbe non funzionare correttamente se l'impostazione non è `raw`.
- **Selezione automatica della lingua** Se Sì, la lingua dell'editor corrisponderà automaticamente alla lingua dell'interfaccia utente selezionata. Se la lingua di TinyMCE non esiste, la lingua dell'editor sarà di default in inglese.
- **Direzione del testo** Se la lingua legge *Da sinistra a destra* o *Da destra a sinistra* (per esempio, come l'arabo). Il predefinito è *Da sinistra a destra*.
- **Classi CSS del modello** Se caricare o meno il file *editor.css*. Se non è trovato tale file per il template predefinito, viene utilizzato il file *editor.css* del template di sistema. Il predefinito è *Sì*.
- **Classi CSS personalizzate** Percorso URL completo opzionale a un file CSS personalizzato. Se inserito, questo sovrascrive l'impostazione delle classi CSS del modello.
- **URL** Se utilizzare URL relativi o assoluti per i link. Il predefinito è *Relative*.
- **Nuove righe** Se interpretare le nuove righe come *Elementi P* o *Elementi BR*. Il predefinito è *Elementi P*.
- **Usare il filtro del testo di Joomla** Se attivo, viene applicato il filtro del testo dalla Configurazione Globale di Joomla per ogni gruppo di utenti. Se disattivato, vengono utilizzati i filtri come definiti qui per tutti i gruppi di utenti.
- **Elementi proibiti** Gli elementi che verranno rimossi dal testo. Il predefinito è *applet*, che rimuoverà gli elementi applet dal testo.
- **Elementi validi** Definisce quali elementi rimarranno nel testo modificato quando l'editor salva (il set di regole predefinito per questa opzione è una combinazione della specifica completa di HTML5 e HTML4).
- **Elementi validi estesi** Elenco opzionale di elementi HTML validi da aggiungere al set di regole esistente.
- **Ridimensionamento** Abilita/disabilita il ridimensionamento dell'area dell'editor (verticalmente e anche orizzontalmente se *Ridimensionamento orizzontale* è abilitato).
- **Ridimensionamento orizzontale** Abilita/disabilita il ridimensionamento orizzontale.
- **Percorso dell'elemento** Se impostato su ON, visualizza le classi impostate per il testo segnato.
- **Conteggio parole** Attiva/disattiva conteggio parole.
- **Markdown** Consente l'uso della sintassi Markdown per creare link, elenchi e altri stili. Questa sintassi speciale viene convertita e salvata come normale html. Ad esempio, l'utente può digitare # testo per produrre un'intestazione o **testo** per rendere il testo in grassetto.
- **Immagine avanzata** Attiva/disattiva una finestra di dialogo per le immagini più avanzata.
- **Elenco avanzato** Attiva/disattiva la possibilità di impostare formati numerici e tipi di elenco puntato in elenchi ordinati e non ordinati.
- **Menu contestuale** Attiva/disattiva il menu contestuale.
- **Plugin personalizzato** Aggiungi plugin TinyMCE personalizzati all'editor specificandoli qui.
- **Pulsante personalizzato** Aggiungi pulsanti TinyMCE personalizzati all'editor specificandoli qui.

#### Scheda avanzata di TinyMCE

![Modulo delle opzioni avanzate di TinyMCE](../../../en/images/plugins/plugin-group-editor-tinymce-advanced.png)

- **Numero di set** Numero di set che possono essere creati. Minimo 3.
- **Altezza HTML** L'altezza, in pixel, della finestra pop-up della modalità HTML.
- **Larghezza HTML** La larghezza, in pixel, della finestra pop-up della modalità HTML.

*Tradotto da openai.com*

