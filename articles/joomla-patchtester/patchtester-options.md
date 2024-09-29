<!-- Filename: Help4.x:Components_Patch_Tester_Options / Display title: Opzioni Tester di Patch -->

## Descrizione

Il *Joomla! Patch Tester* è utilizzato dai Tester per verificare che le patch di codice
prodotte dagli Sviluppatori facciano effettivamente ciò che dovrebbero fare senza
effetti collaterali indesiderati. La pagina *Opzioni* è utilizzata per configurare la connessione a Github.

### Elementi Comuni

Alcuni elementi di questa pagina sono trattati in articoli di Aiuto separati:

* [Barre degli Strumenti](jdocmanual?article=help/common-elements/toolbars).
* [La Scheda Permessi](jdocmanual?article=help/common-elements/edit-permissions).

Maggiori Informazioni: [Una Guida per Principianti al Test dei Bug di Joomla](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## Come Accedere

- Seleziona **Componenti → Tester Patch** dal menu dell'Amministratore.
  - Seleziona il pulsante *Opzioni* sulla Barra degli Strumenti.

## Screenshot

![Modulo Opzioni Patchtester](../../../it/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

## Campi del Modulo

### Scheda Repository GitHub

- **Repository GitHub** Il predefinito è `Joomla! CMS`. Usalo.

### Scheda Autenticazione GitHub

Hai bisogno di un account GitHub e di un Token GitHub. Tutto gratuito - vedi la scheda di Autenticazione GitHub per i dettagli.

![Opzioni Patchtester scheda di autenticazione github](../../../it/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **Metodo di Autenticazione GitHub** Scegli il metodo Token. Il
  metodo delle Credenziali non funzionerà da settembre 2020.
- **Token GitHub** Incolla il Token ottenuto da GitHub.

### Scheda Impostazioni Server CI

Queste impostazioni vengono utilizzate per i test automatici. Usa i predefiniti per i test manuali.

![Opzioni Patchtester scheda impostazioni server ci](../../../it/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **Indirizzo Server CI** Predefinito: `https://ci.joomla.org`
- **Attiva Integrazione CI** Predefinito: Disattivato

*Tradotto da openai.com*

