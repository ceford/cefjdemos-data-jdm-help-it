<!-- Filename: Help4.x:Components_Version_History / Display title: Modifica la Cronologia delle Versioni -->

## Descrizione

Un popup della Cronologia delle Versioni mostra le versioni precedenti dell'elemento che si sta modificando. È disponibile per Articoli, Banner e Clienti, Contatti, Feed di Notizie, Note Utente e tutte le Categorie.

Ogni volta che un elemento viene salvato, viene creata automaticamente una nuova versione. Il numero di versioni da mantenere per ogni elemento viene impostato nelle Opzioni del componente. Una o più versioni possono essere contrassegnate per essere mantenute per sempre. Tali versioni non saranno eliminate automaticamente anche se viene superato il numero massimo di versioni inserito nelle opzioni.

**Nota:** Se si utilizza la versione, i campi personalizzati non sono memorizzati in versioni diverse.

## Come Accedere

Seleziona il pulsante **Versioni** nella Barra degli Strumenti di una pagina di modifica dell'elemento.

## Screenshot

![Popup della cronologia delle versioni](../../../it/images/common-elements/articles-edit-versions.png)

## Intestazioni di Colonna

- **Checkbox** Seleziona questa casella per scegliere uno o più elementi. Per selezionare tutti
gli elementi, seleziona la casella nell’intestazione della colonna. Dopo aver selezionato le caselle,
seleziona un pulsante della barra degli strumenti per eseguire un'azione sugli elementi selezionati.
- **Date** L'orario e la data in cui la versione è stata salvata. Selezionando questo
collegamento si apre l'anteprima di quella versione in una finestra pop-up. Nota che una
delle date sarà seguita da un simbolo di stella. Questo indica che questa
è la versione attualmente salvata e in fase di modifica.
- **Nota Versione** Una Nota Versione può essere utilizzata per aiutare a identificare la natura delle
modifiche da una versione all'altra. Una Nota Versione inserita prima di salvare un
elemento sarà mostrata in questa colonna.
- **Conserva per Sempre** Questa colonna mostra se la versione è stata contrassegnata per
essere conservata per sempre. Normalmente, ogni versione sarà conservata secondo
le impostazioni nella pagina delle opzioni del componente. Le impostazioni predefinite sono
di mantenere un massimo di 10 versioni precedenti di un elemento. Quando un elemento viene salvato che
ha già 10 versioni salvate, la versione più vecchia viene eliminata. Se una versione è
contrassegnata come Conserva per Sempre, non sarà contata come una delle versioni salvate e
non sarà eliminata quando viene raggiunto il numero massimo.
  - Per attivare o disattivare lo stato Conserva per Sempre, seleziona un pulsante *No* o *Sì* oppure seleziona
  la casella di controllo della versione e poi seleziona il pulsante Conserva On/Off nella barra degli strumenti.
- **Autore** L'utente che ha salvato questa versione.
- **Conteggio Caratteri** Il numero totale di caratteri salvati in questa versione. Nota
che questo include i nomi delle colonne del database così come i caratteri effettivamente
digitati.

## Barra degli strumenti

- **Ripristina** La versione corrente dell'elemento è contrassegnata da una stella a
destra della Data. Per ripristinare una delle altre versioni salvate,
seleziona la casella di controllo per la versione desiderata e seleziona il
pulsante Ripristina. La versione corrente dell'elemento sarà sostituita con
la versione selezionata e la schermata di modifica verrà ricaricata con la versione ripristinata caricata nell'editor.
- **Anteprima** Per visualizzare in anteprima una versione, seleziona la colonna Data per la versione desiderata oppure seleziona la casella di controllo e poi il pulsante Anteprima. Verrà caricata una finestra popup separata che mostrerà la versione selezionata dell'elemento.
- **Confronta** Per confrontare due versioni e vedere cosa è stato modificato, seleziona le
caselle di controllo per ciascuna delle versioni e poi il pulsante Confronta. Si aprirà una
nuova finestra del browser che mostrerà un elenco di campi modificati e le modifiche
apportate in quei campi.
  - La prima colonna è il nome del campo, la seconda è la versione più vecchia, la
terza è la versione più recente e l'ultima colonna evidenzia le
differenze tra le due versioni.
- **Mantieni On/Off** Questo pulsante attiva o disattiva la funzione Mantieni per Sempre per una
versione. Normalmente, la versione più vecchia di un elemento verrà eliminata automaticamente
quando il numero massimo di versioni (impostato nelle Opzioni per il componente) è stato superato. Se imposti la proprietà Mantieni per Sempre per una versione, essa non sarà mai eliminata automaticamente.
- **Elimina** Questo pulsante consente l'eliminazione manuale di una o più versioni. Seleziona
la casella di controllo per le versioni da eliminare e poi seleziona il pulsante Elimina. Nota che questo *non* elimina l'elemento in fase di modifica. Elimina solo la cronologia delle versioni per l'elemento.

*Tradotto da openai.com*

