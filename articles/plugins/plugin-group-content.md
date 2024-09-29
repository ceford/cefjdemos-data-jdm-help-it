<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Content_Group / Display title: Gruppo di Contenuti -->

## Descrizione del Gruppo

### Contenuto - Conferma Consenso

![Plugin di conferma del consenso del contenuto](../../../en/images/plugins/plugin-group-content-confirm-consent.png)

- **Breve Informativa sulla Privacy** Avviso breve del testo che verrà visualizzato sopra la checkbox del consenso sulla privacy.
- **Articolo sulla Privacy** Se necessario, seleziona/crea il tuo Articolo sulla Privacy da collegare al tuo modulo.

Per maggiori informazioni, vedi Consenso sulla Privacy - Configurazione del Plugin

### Contenuto - Contatto

![Plugin di contatto del contenuto](../../../en/images/plugins/plugin-group-content-contact.png)

- **Redirezionamento** Puoi collegare il nome dell'autore a:
  - Pagina di contatto associata.
  - Pagina web specificata nel profilo di contatto associato.
  - Email specificata nel profilo di contatto associato.
- **Applica il collegamento anche al nome alias** Collega i dati dell'utente reale anche se un alias dell'autore è impostato nelle opzioni dell'articolo.

### Contenuto - Offuscamento Email

Questo plugin offusca tutte le email nei contenuti usando JavaScript per ingannare gli spambots. Questo aiuta a prevenire che le email contenute negli articoli vengano aggiunte a liste di posta indesiderata. Puoi disabilitare l'Offuscamento Email all'interno di un articolo inserendo {emailcloak=off} in qualsiasi punto del testo dell'articolo. In questo caso, nessun indirizzo email nell'articolo verrà offuscato da questo plugin.

![Plugin di offuscamento delle email del contenuto](../../../en/images/plugins/plugin-group-content-email-cloaking.png)

- **Modalità** Come verranno visualizzate le email. Le opzioni sono *Come indirizzo mailto collegabile* o come *Testo non collegabile*.

### Contenuto - Campi

Questo plugin ti permette di visualizzare un campo personalizzato che è stato inserito con il plugin *Pulsante - Campi* o utilizzando la Sintassi: `{field #}` direttamente nell'area dell'editor. Sintassi:

- **`{field 1}`** visualizzerà il campo con l'ID 1.
- **`{field 1,foo}`** visualizzerà il campo selezionato utilizzando il layout alternativo `foo`.
- **`{fieldgroup 2}`** visualizzerà tutti i campi all'interno del gruppo di campi con l'ID 2.

### Contenuto - Joomla

![Plugin di Joomla del contenuto](../../../en/images/plugins/plugin-group-content-joomla.png)

- **Controllo Eliminazione Categoria** Verifica che le categorie siano completamente vuote prima di essere eliminate.
- **Email al Nuovo Articolo del Sito** Invia un'email agli utenti se *Invia email* è *Attivato* quando viene inviato un nuovo articolo tramite il Frontend.

### Contenuto - Carica Moduli

Questo plugin ti permette di inserire un Modulo all'interno di un Articolo con la sintassi: `{loadposition xx}`, dove `xx` è un codice di posizione definito dall'utente. Ad esempio, se crei un Modulo con il valore di Posizione `myposition1`, digitando il testo `{loadposition myposition1}` all'interno di un Articolo farà sì che quel Modulo venga mostrato in quel punto dell'Articolo.

![Plugin di caricamento moduli del contenuto](../../../en/images/plugins/plugin-group-content-load-modules.png)

- **Stile** Lo stile per il Modulo caricato.

### Contenuto - Interruzione di Pagina

Questo plugin aggiunge funzionalità di indice dei contenuti a un Articolo paginato. Questo viene fatto automaticamente tramite l'uso del pulsante Interruzione di Pagina aggiunto nella parte inferiore del pannello di testo in un Articolo. Il codice HTML è incluso qui come riferimento di ciò che è disponibile. L'Interruzione di Pagina verrà visualizzata nella finestra di testo come una semplice riga orizzontale.

![Plugin di interruzione di pagina del contenuto](../../../en/images/plugins/plugin-group-content-page-break.png)

- **Mostra Titolo del Sito** Se il titolo e gli attributi dell'intestazione del plugin verranno aggiunti o meno al tag Title del Sito.
- **Intestazione Indice Articolo** Mostra o nasconde l'Intestazione dell'Indice dell'Articolo. L'Intestazione viene visualizzata in cima all'Indice dei Contenuti.
- **Intestazione Indice Articolo Personalizzata** Inserisci un testo personalizzato per l'Intestazione dell'Indice dell'Articolo. Se vuoto, verrà utilizzato lo standard.
- **Indice dei Contenuti** Se nascondere o mostrare un indice dei contenuti per Articoli multi-pagina.
- **Mostra tutto** Se offrire o meno agli utenti l'opzione di visualizzare tutte le pagine di un Articolo.
- **Stile di Presentazione** Visualizza l'articolo con pagine separate, schede o slider.

![Descrizione dell'interruzione di pagina del contenuto](../../../en/images/plugins/plugin-group-content-page-break-description.png)

### Contenuto - Navigazione di Pagina

Questo plugin ti permette di aggiungere link di navigazione Avanti & Indietro agli Articoli, ad esempio quando si utilizza un layout di blog o lista. Questa funzione può essere controllata con i seguenti parametri di Joomla!:

- **Mostra Navigazione** nell'Articolo - Configurazione Globale dello schermo
- **Mostra Navigazione** nella sezione Parametri - Componente della voce di Menu - Nuovo/Modifica - Parametri - Componente per lo schermo degli Articoli nei layout degli Articoli.

Nota che, se il plugin di Navigazione di Pagina è disabilitato in questa schermata, non verrà mostrata alcuna Navigazione di Pagina e le impostazioni dei parametri sopra non avranno effetto.

![Plugin di navigazione di pagina del contenuto](../../../en/images/plugins/plugin-group-content-page-navigation.png)

- **Posizione** Posizione del link di navigazione. Le opzioni sono *Sopra* l'Articolo o *Sotto* l'Articolo.
- **Relativo a** Assegna la posizione relativa per i parametri di Posizione. Testo lo posizionerà direttamente sopra o sotto il contenuto dell'articolo. Articolo Completo lo posizionerà sopra o sotto l'intero display, compreso il titolo e il readmore.
- **Testo del Link** Scegli cosa visualizzare come testo del link.

### Contenuto - Ricerca Intelligente

Le modifiche ai contenuti non aggiorneranno l'indice di Ricerca Intelligente se non abiliti questo plugin.

### Contenuto - Vota

![Plugin di voto del contenuto](../../../en/images/plugins/plugin-group-content-vote.png)

- **Posizione** Posizione della votazione.

*Tradotto da openai.com*

