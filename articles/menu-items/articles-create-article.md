<!-- Filename: Help4.x:Menu_Item:_Create_Article / Display title: Crea Articolo -->

## Descrizione

L'elemento di menu *Crea Articolo* consente agli utenti di inviare un articolo tramite l'interfaccia del sito. Di solito, questo è disponibile solo per gli utenti che hanno effettuato l'accesso al frontend del sito. Gli utenti devono avere il permesso di creare articoli.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Dettagli](jdocmanual?article=help/menu-items-common/menu-item-details).
* [La Scheda Tipo di Collegamento](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [La Scheda Visualizzazione Pagina](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [La Scheda Metadata](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [La Scheda Associazioni](jdocmanual?article=help/common-elements/edit-associations).
* [La Scheda Assegnazione Modulo](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Come Accedere

Seleziona **Menu → \[nome del menu\]** dal menu Amministratore.

Per aggiungere una Voce di Menu:

1.  Seleziona il pulsante **Nuovo** nella Barra degli Strumenti.
2.  Seleziona il pulsante **Seleziona** del *Tipo di Voce di Menu*.
3.  Seleziona l'elemento **Articoli** nel dialogo popup.
4.  Seleziona l'elemento **Crea Articolo**.

Per modificare una Voce di Menu:

- Seleziona un **Titolo** dall'elenco.

## Schermata

![Menu Articolo Crea Dettagli Articolo scheda](../../../it/images/menu-items/articles-create-article-details-tab.png)

## Campi del modulo

- **Titolo** Il titolo che verrà visualizzato per questo elemento di menu.
- **Alias** Il nome interno dell'elemento di menu. Normalmente, puoi lasciare
  questo campo vuoto e Joomla compilerà automaticamente un valore predefinito 
  in minuscolo e con trattini invece degli spazi.

### Dettagli

#### Pannello Sinistro

- **Tipo di elemento di menu** Il tipo di elemento di menu selezionato quando 
  questo elemento di menu è stato creato. Questo può essere uno dei tipi di 
  elementi di menu core o un tipo di elemento di menu fornito da un'estensione
  installata. 
- **Link** Il link generato dal sistema per questo elemento di menu. Questo campo 
  non può essere modificato ed è solo a scopo informativo.
- **Finestra di destinazione** Seleziona dall'elenco a discesa.
- **Stile del modello** Seleziona dall'elenco a discesa.

#### Pannello Destro

- **Menu** Mostra in quale menu apparirà il link.

### Opzioni

![Articoli del menu Crea scheda dettagli articolo](../../../it/images/menu-items/articles-create-article-options-tab.png)

- **Categoria specifica**
  - *Sì* Gli articoli saranno assegnati alla categoria specificata. L'utente 
    non potrà selezionare una categoria.
  - *No* L'utente può selezionare la categoria dalla casella di riepilogo. 
    Verranno mostrate solo le categorie per cui l'utente ha il permesso 
    di *Creare*.
- **Reindirizzamento dopo invio/annulamento** Seleziona la pagina a cui l'utente 
  verrà reindirizzato dopo un invio riuscito dell'articolo.
- **Reindirizzamento personalizzato su annullamento**
  - *Sì* Imposta una pagina a cui reindirizzare quando l'utente annulla 
    l'invio dell'articolo.
  - *No* Quando l'utente annulla l'invio dell'articolo, verrà reindirizzato 
    alla pagina di *Reindirizzamento dopo invio/annulamento*.

## Esempio di Screenshot del Frontend

Questo screenshot mostra il template Frontend di base di Joomla **Cassiopeia** con tutte le opzioni 
dell'Editing Layout impostate su 'Nascondi'.

[articles-create-article-frontend.png](../../../it/images/menu-items/articles-create-article-frontend.png)

## Suggerimenti

Un utente non autorizzato normalmente otterrà un errore quando selezionerà una voce di menu *Crea Articolo*. Per questo motivo, è prassi normale assegnare alla voce di menu un Livello di Accesso di visualizzazione che può essere visto solo dagli utenti autorizzati ad aggiungere articoli.

*Tradotto da openai.com*

