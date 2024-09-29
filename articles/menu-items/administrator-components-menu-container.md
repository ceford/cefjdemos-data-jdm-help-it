<!-- Filename: Help4.x:Menu_Item:_Components_Menu_Container / Display title: Voce di menu: Contenitore del menu Componenti -->

## Descrizione

Il Contenitore del Menu Componenti viene utilizzato per mostrare un contenitore di componenti nell'interfaccia dell'Amministratore. Un caso d'uso potrebbe essere il seguente:

Supponiamo che tu voglia mostrare solo a determinati utenti collegamenti a un sottoinsieme dei Componenti sul tuo sito. Gli Utenti Super vedranno i collegamenti a tutte le cose, ovviamente. Puoi fare questo nel modo seguente:

- Crea un nuovo Gruppo Utenti chiamato, ad esempio, Filiale, con Pubblico come padre.
- Imposta le Autorizzazioni Globali per questo gruppo su Consenti Accesso all'Amministratore.
- Crea un nuovo menu chiamato, ad esempio, Menu Filiale senza modelli importati.
- Crea un Modulo collegato chiamato, ad esempio, Menu Filiale con menu da mostrare come Menu Filiale. Imposta Controllo Menu su No e Accesso su Pubblico.
- Crea una voce di menu Contenitore del Menu Componenti per il Menu Filiale chiamata, ad esempio, Componenti Filiale.
  - Nascondi qualsiasi componente che non desideri che gli utenti Filiale vedano.
  - Mostra quelli a cui dovrebbero avere accesso.
- Imposta le Autorizzazioni dei Componenti per il Gruppo Filiale su permesso per tutti, eccetto Configura ACL e Configura Opzioni.

Per un Utente Super, il menu dell'Amministratore avrà una duplicazione ovvia dei collegamenti. Tuttavia, un utente di Filiale vedrà solo il menu Componenti Filiale e il Dashboard Iniziale. Dovrai anche regolare i permessi di accesso dei moduli Icona Veloce lì! E hai davvero bisogno di creare un modulo Dashboard per qualsiasi componente a cui gli utenti di Filiale abbiano accesso.

Per gli utenti che necessitano di accesso agli Articoli, puoi aggiungere altre voci di menu al Menu Filiale. In questo modo puoi costruire un menu personalizzato completo per gli utenti di Filiale.

### Elementi Comuni

Alcuni aspetti di questa pagina sono trattati in articoli di aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Tipo di Collegamento](jdocmanual?article=help/menu-items-common/menu-item-link-type).

## Come Accedere

Per creare un nuovo Elemento di Menu del Contenitore Componenti:

- Crea un nuovo Menu da **Menu → Gestisci** nel menu dell'Amministratore.
  - Seleziona **Amministratore** dal selettore a tendina *Sito/Amministratore*.
  - Seleziona il pulsante **Nuovo** nella Barra degli Strumenti. Compila il modulo:
    - **Titolo** Menu Filiale
    - **Nome Unico** menu_filiale
    - **Descrizione** Menu personalizzato per la Filiale.
    - **Importa Preimpostato** Nessuno
    - **Salva**
    - **Permessi** Seleziona il gruppo *Filiale* e imposta tutto su *Consenti*.
    - **Salva & Chiudi**
    - Seleziona il pulsante **Crea un Modulo** e compila il modulo di dialogo:
    - **Titolo** Componenti Filiale
    - **Verifica Menu** No (altrimenti apparirà un messaggio che invita a 
      *attivare la modalità di recupero del menu*.)
    - **Accesso** Speciale
    - **Posizione** Menu
- Seleziona **Menu → \[nome del menu\]** dal menu Amministratore.
- Seleziona il pulsante **Nuovo** nella Barra degli Strumenti per creare un nuovo elemento di menu.
- Seleziona il pulsante **Seleziona** del Tipo di Voce del Menu.
- Seleziona il link **Elenca Contenitore Componenti** da **Link di Sistema** nella
  finestra di dialogo del Tipo di Voce del Menu.

Per modificare un Elemento di Menu del Contenitore Componenti esistente, seleziona il suo Titolo nell'elenco delle Voci di Menu.

## Screenshot

![Contenitore del Menu Componenti](../../../en/images/menu-items/administrator-components-menu-container.png)

## Campi del Modulo

- **Nome** Il nome dell'elemento del menu, ad esempio *Menu Filiale*. Apparirà
  in fondo al menu dell'Amministratore.
- **Alias** Il nome interno dell'elemento. Normalmente, puoi lasciare questo
  campo vuoto e Joomla riempirà automaticamente un valore predefinito con il
  Titolo in minuscolo e con trattini al posto degli spazi.

### Scheda Dettagli

#### Pannello Sinistro

- **Tipo di Voce di Menu** In questo caso *Contenitore del Menu Componenti*.
- **Mostra o Nascondi Voci di Menu** Elenco delle voci di menu con pulsanti per
  impostare lo stato di visibilità. Se un elemento padre è impostato su *Nascondi*,
  anche tutte le voci figlie sono nascoste, anche se sono impostate su *Mostra*.

#### Pannello Destro

- **Menu** Indica in quale menu apparirà il link.
- **Padre** L'elemento (categoria, voce di menu, e così via) che è il
  padre dell'elemento che viene modificato.
- **Ordinamento** Indica l'ordine di questa Voce di Menu nel Menu. L'ordine
  predefinito è aggiungere la Voce di Menu alla fine del Menu. Questa Voce di Menu
  verrà spostata nella posizione d'ordine immediatamente dopo la Voce di Menu
  selezionata dall'elenco a tendina. Si noti che l'Ordine delle Voci di Menu
  può essere cambiato anche nel Gestore delle Voci di Menu.
- **Stato** Lo stato di pubblicazione dell'elemento.
- **Nota** Di solito è per l'uso dell'amministratore del sito (ad esempio,
  per documentare informazioni su questo elemento) e non viene mostrata nel
  Frontend del sito.

## Suggerimenti

- L'elemento **Componenti del Ramo** appare in fondo al menu dell'Amministratore.
  L'accesso al menu principale dell'Amministratore e a questa sezione può essere
  personalizzato per il gruppo Ramo.

*Tradotto da openai.com*

