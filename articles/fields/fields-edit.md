<!-- Filename: Help4.x:Fields:_Edit / Display title: Componente: Modifica Campo -->

## Descrizione

La pagina *Componente: Modifica Campo* è simile per tutti i componenti che implementano
i campi, ma il titolo della pagina cambia a seconda del contesto: *Articoli: Modifica Campo*,
*Contatti: Modifica Campo* o *Utenti: Modifica Campo*.

La scheda **Generale** cambia per riflettere il tipo di campo in fase di modifica e una volta
che un campo è stato salvato, il suo tipo non può essere modificato. Tuttavia, è facile
eliminare campi e crearne di nuovi.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Pubblicazione](jdocmanual?article=help/common-elements/edit-publishing).
* [La Scheda Permessi](jdocmanual?article=help/common-elements/edit-permissions).

## Come Accedere

* Seleziona **Contenuti → Campi** dal menu Amministratore. Oppure...
* Seleziona **Contatti → Campi** dal menu Amministratore. Oppure...
* Seleziona **Utenti → Campi** dal menu Amministratore. Poi...
  * Seleziona il pulsante **Nuovo** nella Barra degli Strumenti per creare un nuovo campo. Oppure...
  * Seleziona un **Titolo** dall'elenco per modificare un campo esistente.

**Nota:** C'è un elenco a discesa che consente la creazione di Campi per una
Categoria, e Mail nel componente Contatto. Richiedono un po' di esperienza di codifica per preparare override del template adeguati.

## Schermata

![Campo di modifica degli articoli](../../../it/images/fields/articles-edit-field.png)

## Campi del Formulario

- **Titolo** Il titolo per questo campo.

### Scheda Generale

#### Pannello Sinistro

Parametri per tutti i campi:

- **Tipo** Se crei un campo puoi scegliere uno dei 16 tipi di campo.
  Quando salvi il campo questo tipo è permanente.
- **Nome** Il nome sarà utilizzato per identificare il campo. Lascia
  questo campo vuoto e Joomla riempirà con un valore predefinito dal titolo.
- **Etichetta** Usa un testo descrittivo del campo per l'etichetta del
  campo. Questo testo non è traducibile. Se non inserisci alcun testo per
  un'etichetta, anche il testo del titolo sarà usato come testo dell'etichetta.
- **Descrizione** La descrizione del campo. Un testo che sarà
  mostrato come suggerimento quando l'utente passa il mouse sopra la casella di testo
  mentre lo utilizza nel Backend creando un articolo o un contatto o un
  componente di terze parti che supporta i campi. Questo testo non è
  traducibile. Non vedi questa descrizione nel Frontend.
- **Obbligatorio** Questo è un campo obbligatorio? In questo caso, il campo deve
  essere compilato prima di inviare un articolo o un contatto o un componente di
  terze parti che supporta i campi.

#### Pannello Destro

- **Stato** Lo stato di pubblicazione di questo campo.
  - *Pubblicato* Il campo è visibile mentre si modifica un articolo o un
    contatto. Ed è visibile nel Frontend.
  - *Non Pubblicato* Il campo non sarà visibile agli utenti mentre si modifica un
    articolo o un contatto.
  - *Archiviato* Il campo non sarà più visibile durante la modifica di un articolo o un
    contatto. Puoi aprirlo nei Campi quando imposti il filtro su archiviati.
  - *Cestinato* Il campo è eliminato ma ancora nel database. Può essere
    definitivamente eliminato dal database nei Campi con la funzione Svuota Cestino.
- **Gruppo di Campi** Puoi assegnare un campo a un gruppo di campi.
- **Categoria** Puoi assegnare un campo a una o più categorie. Nota
  che il predefinito *Tutti* non include gli articoli *Non categorizzati*.
- **Accesso** Seleziona il livello di accesso per la visualizzazione di questo campo. I livelli di accesso dipendono da ciò che è stato impostato in *Utenti: Livelli di Accesso*.
- **Lingua** Seleziona la lingua per questo campo. Se non stai utilizzando 
  la funzione multilingue di Joomla, mantieni il predefinito *Tutti*.
- **Nota** Un campo opzionale per fare le tue note personali sul campo.

### Scheda Opzioni

![Scheda opzioni modifica campo articoli](../../../it/images/fields/articles-edit-field-options-tab.png)

#### Opzioni Formulario

- **Segnaposto** Un testo segnaposto che apparirà all'interno del campo
  come suggerimento per l'input. Il segnaposto è attivo nel Backend
  mentre si crea un articolo o un contatto o un componente di terze parti che
  supporta i campi. Non lo vedi nel Frontend.
- **Classe Campo** Gli attributi della classe del campo quando il campo è
  renderizzato. Se sono necessarie classi diverse, elencale con spazi.
- **Classe Etichetta (Formulario)** Classe CSS da applicare all'etichetta del 
  campo quando è in modalità di modifica (inserimento di input nel campo).
- **Modificabile In** In quale parte del sito il campo dovrebbe essere mostrato?
  Nel Backend, nel Frontend o entrambi?
- **Attributo Mostra su** Mostra o nascondi condizionalmente il campo a seconda
  del valore di altri campi. La sintassi da usare qui, per esempio:
  `lista-degli-elementi:valore1[O]lista-degli-elementi:valore2`
  - lista-degli-elementi: Il *nome* di un campo già creato sul
    quale questo campo dipenderà per essere mostrato.
  - valore1: Il valore necessario affinché il campo su cui dipende sia
    mostrato.
  - `[O]`: Per creare una scelta tra più campi. Nell'esempio,
    questo campo sarà mostrato quando il campo *lista-degli-elementi* ha il valore:
    *valore1* O *valore2*
  - `[E]`: Per combinare più campi. Questo campo sarà mostrato solo
    quando il campo *lista-degli-elementi* ha il valore: *valore1* E *valore2*
  - Puoi anche usare il valore *non uguale a* come in
    *lista-degli-elementi!:valore1* La sintassi mostrerà questo campo solo quando
    *lista-degli-elementi* non è uguale a *valore1*
  - Per mostrare questo campo quando il campo *lista-degli-elementi* è selezionato e
    non ha un valore vuoto, usa la sintassi *lista-degli-elementi!:* (senza un
    valore specificato).

**Nota:** I campi del sotto-formulario gestiscono l'identificatore *nome* di *lista-degli-elementi*
diversamente. Se crei un campo personalizzato Sotto-formulario e aggiungi questo
campo condizionale lì, devi usare *campo\[ID\]*
invece di *lista-degli-elementi*, dove ID è l'ID del campo
*lista-degli-elementi*. Pertanto, l'attributo *mostra su* per questo campo condizionale
che stai creando deve essere: `campo36:valore1[O]campo36:valore2` dove
36 è l'ID del campo 'Lista degli elementi'.

#### Opzioni di Visualizzazione

- **Classe di Visualizzazione** La classe del contenitore del campo nell'output.
- **Classe Valore** La classe del valore del campo nell'output.
- **Etichetta** Mostra l'etichetta quando il campo viene renderizzato.
- **Classe Etichetta (Output)** Classe CSS da applicare all'etichetta del campo quando
  viene mostrata (visualizzando l'output di un campo).
- **Visualizzazione Automatica** Joomla offre alcuni eventi di contenuto che sono
  attivati ​​durante il processo di creazione del contenuto. Questo è il posto dove
  definire come i campi dovrebbero essere integrati nel contenuto. Puoi
  scegliere
  - Dopo il Titolo
  - Prima del Contenuto Visualizzato
  - Dopo il Contenuto Visualizzato
  - Non visualizzare automaticamente
- **Prefisso** Testo fisso da visualizzare prima di un campo, per esempio £.
- **Suffisso** Testo fisso da visualizzare dopo un campo, per esempio €.
- **Layout** Se esiste un layout personalizzato, sarebbe selezionato qui.
- **Mostra Quando Sola Lettura** Se il campo è di sola lettura (forse l'
  utente non ha il livello di accesso) dovrebbe il campo essere visualizzato o
  nascosto.

#### Ricerca Intelligente

- **Indice di Ricerca**  Avvertenza: Quando *Rendi ricercabile* è selezionato, il contenuto
  del campo viene indicizzato con i permessi di visualizzazione dell'elemento di contenuto.
  Questo potrebbe portare a una divulgazione inaspettata di informazioni.

*Tradotto da openai.com*

