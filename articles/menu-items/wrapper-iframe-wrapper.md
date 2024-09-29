<!-- Filename: Help4.x:Menu_Item:_Iframe_Wrapper / Display title: Contenitore Iframe -->

## Descrizione

Il tipo di voce di menu *Iframe Wrapper* viene utilizzato per creare una pagina con contenuto incorporato utilizzando un IFrame con controllo della dimensione, larghezza e altezza dell'iframe.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Dettagli](jdocmanual?article=help/menu-items-common/menu-item-details).
* [La Scheda Tipo di Link](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [La Scheda Visualizzazione Pagina](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [La Scheda Metadata](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [La Scheda Associazioni](jdocmanual?article=help/common-elements/edit-associations).
* [La Scheda Assegnazione Modulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Come Accedere

Per creare un nuovo elemento di menu IFrame Wrapper:

- Seleziona **Menus → \[nome del menu\]** dal menu dell'Amministratore
  (ad esempio, **Menus → Menu Principale**). Poi...
  - Seleziona il pulsante **Nuovo** nella Toolbar. Poi...
  - Seleziona il pulsante Seleziona Tipo di Voce del Menu.
  - Nella finestra di dialogo modale, seleziona l'elemento Utenti per aprire un elenco e poi
    seleziona l'elemento di menu **Iframe Wrapper**.

Per modificare un elemento di menu *IFrame Wrapper* esistente:

- Seleziona il suo Titolo nella lista *Menu: Elementi*.

## Schermata

![Dettagli della scheda wrapper Iframe](../../../it/images/menu-items/wrapper-iframe-wrapper-details-tab.png)

## Campi del Modulo

### Scheda Parametri Barra di Scorrimento

![Scheda parametri barra di scorrimento wrapper Iframe](../../../it/images/menu-items/wrapper-scroll-bar-parameters-tab.png)

- **Larghezza** Larghezza della finestra IFrame. Inserire un numero di pixel o una percentuale. Ad esempio, *550* significa 550 pixel; *75%* significa il 75% della larghezza del contenitore `<main>`. Un numero assoluto di pixel potrebbe essere più ampio del contenitore e causare problemi di layout. In caso di dubbio, provare con il 100%.
- **Altezza** Altezza della finestra IFrame. Inserire un numero di pixel. Ad esempio, *550* significa 550 pixel.

### Scheda Avanzata

![Scheda avanzata wrapper Iframe](../../../it/images/menu-items/wrapper-advanced-tab.png)

- **Altezza automatica** Imposta automaticamente l'altezza a quella della pagina esterna. *Nota* - questo funzionerà solo se la pagina esterna è sul **lo stesso dominio**. Ad esempio, `http://www.esempio.com` l'html esterno deve essere nella struttura di file radice di `esempio.com`. I sottodomini non funzioneranno, poiché un sottodominio è considerato un dominio separato.
- **Aggiunta automatica** Prefix web address automaticamente con http://. Questa funzionalità rileverà automaticamente e non prefisserà un URL con http:// o https:// già utilizzato nell'URL.
- **Lazy Loading** ...

*Tradotto da openai.com*

