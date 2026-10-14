<!--
{
    "source": "https://docs.joomla.org/Help4.x:Editors",
    "title": "Editor: Introduzione",
    "description": " ",
    "author": ""
}
-->

## TinyMCE

TinyMCE è l'editor predefinito per gli utenti Frontend e Backend. L'editor
consente agli utenti di utilizzare un'interfaccia familiare di elaborazione
testi durante la modifica dei contenuti.

TinyMCE può essere configurato con 3 diversi set di pulsanti della barra
degli strumenti. Questa impostazione si trova nel plugin Editor - TinyMCE.

### Barre degli strumenti

#### Preset semplice

Il set di barre degli strumenti 2 fornisce una riga di pulsanti come mostrato
di seguito. Il set è assegnato per impostazione predefinita al gruppo di
utenti Pubblico.

![Barra degli strumenti TinyMCE set 2](../../../it/images/editors/editors/01-set-2.png)

- I pulsanti consentono di rendere il testo in grassetto, sottolineato o barrato.
- Annulla e Ripeti.
- Elenco non ordinato, Elenco ordinato.
- Incolla come testo: spesso, quando si copia e incolla del testo da altre
  fonti, come file PDF, documenti di testo o pagine web, il testo selezionato
  contiene informazioni di formattazione non necessarie o desiderate. L'uso
  di "Incolla come testo" rimuoverà tutta la formattazione dal testo.

#### Preset medio

Il set di barre degli strumenti 1 fornisce due righe di pulsanti come mostrato
di seguito. Il set è assegnato per impostazione predefinita ai gruppi di
utenti Manager e Registrati.

![Barra degli strumenti TinyMCE set 1](../../../it/images/editors/editors/02-set-1.png)

Questa opzione fornisce tutti gli stessi pulsanti documentati nella barra
degli strumenti Set 2 sopra descritta. Inoltre, sono disponibili le seguenti
opzioni.

#### Medio: riga superiore

- Contenuto CMS: l'elenco a discesa consente di accedere al collegamento a un
  articolo, contatto, campo, media, menu o modulo.

Articolo: l'esempio mostra come creare facilmente un collegamento a qualsiasi articolo
del sito corrente.

![Finestra modale del selettore di collegamenti TinyMCE](../../../it/images/editors/editors/03-link-button.png)

Per creare un collegamento all'articolo desiderato:

- Posizionare il cursore nel punto dell'articolo in cui si desidera inserire il
  titolo dell'articolo collegato.
- Fare clic sul pulsante Articolo per aprire la finestra.
- Fare clic sul titolo per selezionare l'articolo desiderato nella finestra. È
  possibile utilizzare la ricerca e i filtri per trovare l'articolo desiderato.
- Un collegamento con il titolo dell'articolo verrà inserito nella posizione
  corrente del cursore.
- Se necessario, è possibile modificare il testo del collegamento.

Allo stesso modo è possibile collegare altri elementi come Media, Moduli e così via.

Interruzione di pagina: questo pulsante consente di inserire un'interruzione di pagina
all'interno di un articolo. Un'interruzione di pagina consente di navigare tra le
pagine quando l'articolo viene visualizzato in un layout. È utile per gli articoli
lunghi. Quando si preme questo pulsante, viene visualizzata una finestra come mostrato
di seguito:

![Modulo per l'interruzione di pagina TinyMCE](../../../it/images/editors/editors/04-pagebreak-button.png)

- **Titolo della pagina**. Inserire il titolo da visualizzare per la nuova pagina (ad
  esempio, "Pagina 2").
- **Alias dell'indice**. Campo facoltativo da visualizzare nell'indice per questa pagina.
  In un articolo multipagina, Joomla visualizza un "indice" della pagina che consente
  all'utente di selezionare qualsiasi pagina. Se questo campo è vuoto, verrà utilizzato
  il Titolo della pagina. Se si desidera un titolo diverso nell'indice, inserirlo qui.
- **Inserisci interruzione di pagina**. Fare clic su questo pulsante per inserire
  l'interruzione di pagina con i campi compilati. L'interruzione di pagina verrà
  visualizzata come una linea tratteggiata grigia attraverso l'articolo. Si noti che
  un'interruzione di pagina non può essere modificata. Se è necessario modificare un
  campo nell'interruzione di pagina, fare clic sull'articolo subito dopo l'interruzione
  di pagina, premere Backspace finché l'interruzione di pagina non viene eliminata,
  quindi inserire una nuova interruzione di pagina con le informazioni desiderate.
- La configurazione viene impostata nel plugin Contenuto - Interruzione di pagina.

Leggi tutto: questo pulsante inserisce nell'articolo un'interruzione "Leggi tutto". Questa
viene visualizzata come una linea rossa tratteggiata attraverso l'articolo.

- Se un articolo contiene un'interruzione "Leggi tutto", inizialmente verrà visualizzato
  solo il testo precedente all'interruzione, chiamato Testo introduttivo, insieme a un
  collegamento Leggi tutto. Se l'utente fa clic su questo collegamento, viene visualizzato
  l'intero articolo oppure solo la parte successiva al collegamento Leggi tutto. Questo
  dipende dall'impostazione dei parametri del
  Testo
  introduttivo per l'articolo.
- L'interruzione "Leggi tutto" consente di risparmiare spazio nelle pagine mostrando
  soltanto il Testo introduttivo.
- Se si desidera inserire interruzioni per un articolo visualizzato in un Layout articolo,
  utilizzare il pulsante Interruzione di pagina.

I pulsanti nell'elenco a discesa dei contenuti CMS possono essere disabilitati in
Plugin - editors-xtd.

- I pulsanti in alto a sinistra consentono di rendere il testo in corsivo. Accanto
  si trovano i pulsanti per l'allineamento a sinistra, a destra, centrato e giustificato.
- Formati: selezionare formati predefiniti per Intestazioni, In linea, Blocchi e
  così via.
- Riduci rientro (sposta a sinistra) e Aumenta rientro (rientra a destra).
- 3 puntini: mostra la seconda riga della barra degli strumenti.

#### Medio: seconda riga

- Inserisci/modifica collegamento: per inserire o modificare un collegamento, selezionare il testo collegato e premere questo pulsante. Viene visualizzata una finestra di dialogo popup che consente di inserire i dettagli del collegamento.
- Rimuovi collegamento: per rimuovere un collegamento, evidenziare il testo collegato e premere questo pulsante.
- Ancora: un'ancora è un segnalibro all'interno di un articolo che consente di collegarsi direttamente a quel punto dell'articolo.
- Codice sorgente: viene visualizzato un popup con il codice sorgente HTML, che consente di modificarlo.
- Inserisci una linea orizzontale: per inserire una linea orizzontale, spostare il cursore nella posizione desiderata all'interno dell'articolo e fare clic su questo pulsante.
- Tabella: inserisci nuova tabella, proprietà riga tabella, proprietà cella tabella, inserisci riga prima, inserisci riga dopo, elimina riga, inserisci colonna prima, inserisci colonna dopo, elimina colonna, dividi celle unite della tabella, unisci celle della tabella.
- Pedice, apice, carattere speciale.
- Visualizza l'anteprima del testo in un popup.

#### Preimpostazione avanzata

Il set di barre degli strumenti 0 fornisce le opzioni di modifica più estese, come mostrato di seguito. Il set è assegnato per impostazione predefinita ai gruppi di utenti Amministratore, Editor e Super User.

![Set di dati TinyMCE 0](../../../it/images/editors/editors/05-set-0.png)

Questa opzione fornisce tutti gli stessi pulsanti documentati nella barra degli strumenti del Set 1 sopra. Inoltre, sono disponibili le seguenti opzioni.

#### Avanzato: riga superiore

- Blocchi: paragrafo, titoli, preformattato.
- Caratteri: selezionare il carattere desiderato.
- Dimensione carattere: selezionare la dimensione del carattere desiderata.
- Trova e sostituisci.
- Inserisci/modifica immagine: per inserire un'immagine, posizionare il cursore nella posizione desiderata e premere questo pulsante. Viene visualizzata una finestra di dialogo popup che consente di inserire l'origine, la larghezza o l'altezza e altre informazioni sull'immagine.

#### Avanzato: seconda riga

- Seleziona il colore del testo o il colore dello sfondo.
- Schermo intero.
- Emoticon.
- Inserisci contenuto multimediale: per inserire contenuti multimediali, posizionare il cursore nella posizione desiderata e premere questo pulsante. Viene visualizzata una finestra di dialogo popup che consente di inserire il tipo, il file o l'URL e altre informazioni sul contenuto multimediale.
- Direzione da sinistra a destra o direzione da destra a sinistra: questi pulsanti consentono di inserire o modificare la direzione del testo, ad esempio per le lingue che si leggono da destra a sinistra.
- Taglia, copia, incolla.
- Mostra i caratteri invisibili (come le terminazioni dei paragrafi).
- Mostra i blocchi.
- Spazio unificatore.
- Citazione.
- Inserisci modello.

#### Avanzato: terza riga

- Stampa il testo dell'articolo.
- Inserisci/modifica esempio di codice.
- Inserisci data/ora.
- Cancella formattazione.

### Accessibilità

TinyMCE è compatibile con lettori di schermo come
<a href="https://www.freedomscientific.com/products/software/jaws/"
rel="nofollow noreferrer noopener">JAWS</a> e
<a href="https://www.nvaccess.org/"
rel="nofollow noreferrer noopener">NVDA</a>. È possibile utilizzarlo
efficacemente anche senza usare il mouse.

#### Scorciatoie da tastiera

| Attività                                     | PC                     | macOS                  |
|----------------------------------------------|------------------------|------------------------|
| Attiva/salta alla barra dei menu             | Alt+F9                 | ⌥+F9                 |
| Attiva/salta alla barra degli strumenti      | Alt+F10                | ⌥+F10                |
| Attiva/salta al percorso degli elementi      | Alt+F11                | ⌥+F11                |
| Chiudi menu/sottomenu/finestra di dialogo    | Esc                    | esc                    |
| Torna all'area del contenuto dell'editor     | Esc                    | esc                    |
| Naviga a sinistra/destra nel menu/barra degli strumenti | Tab e tasti freccia | Tab e tasti freccia |

Per ulteriori informazioni, vedere:

- <a href="https://www.tiny.cloud/docs/advanced/accessibility/"
  rel="nofollow noreferrer noopener">TinyMCE - Accessibilità</a>
- Un elenco delle
  <a href="https://www.tiny.cloud/docs/advanced/keyboard-shortcuts/"
  rel="nofollow noreferrer noopener">scorciatoie da tastiera</a> disponibili (PC, Mac)
  all'interno del corpo dell'editor.

## CodeMirror

L'editor «Editor - CodeMirror» è progettato per facilitare l'inserimento di codice HTML in un articolo o in una descrizione. CodeMirror supporta l'evidenziazione della sintassi e il completamento automatico, come mostrato in questa schermata.

![modulo di modifica di CodeMirror](../../../it/images/editors/editors/06-codemirror.png)

- I pulsanti mostrati sotto la finestra di modifica consentono di accedere al collegamento a qualsiasi elemento del sito.
- CodeMirror offre alcuni degli stessi vantaggi dell'utilizzo di «Editor - None», ma semplifica in parte il lavoro con il codice HTML non elaborato.
- La configurazione è impostata nel plugin Editor -
  CodeMirror
  .

## Nessuno

Se per un utente è selezionato «Editor - Nessuno», viene visualizzato un semplice editor di testo. Ciò consente di inserire HTML non formattato e grezzo. È possibile utilizzare il pulsante «Anteprima» della barra degli strumenti per visualizzare in anteprima l'aspetto dell'HTML.

L'opzione «Nessuno» può essere utile quando si inserisce codice HTML «standard» o personalizzato, ad esempio per creare un link PayPal. TinyMCE riformatta automaticamente e rimuove parte del codice HTML quando un file viene salvato. Ciò può impedire il corretto funzionamento di codice HTML complesso.

Se ciò si verifica, è possibile cambiare temporaneamente l'editor in «Nessuno» e creare il contenuto desiderato. Se in futuro si desidera modificare questo contenuto, è importante impostare l'editor su «Nessuno». In caso contrario, se si apre e si salva il contenuto con TinyMCE, si potrebbe perdere il codice HTML personalizzato.

Il plugin «Editor - Nessuno» non prevede configurazioni.

*Tradotto da openai.com*