<!--
{
    "source": "https://docs.joomla.org/Help4.x:Joomla_Update",
    "title": "Aggiornamento di Joomla: introduzione",
    "description": " ",
    "author": ""
}
-->

## Descrizione

Questa pagina consente di aggiornare Joomla! utilizzando un pacchetto di aggiornamento dal repository del codice di Joomla!
È consigliabile e più sicuro lasciare che Joomla si aggiorni autonomamente utilizzando questo
metodo.

## Come accedere

Nel **Dashboard principale → Pannello notifiche** l'icona di Joomla mostrerà
uno dei due messaggi:
- **Joomla è aggiornato**
- **X.Y.Z disponibile - Aggiorna ora!**

Seleziona l'icona.

Inoltre, il **Sistema → Pannello aggiornamenti → Joomla** mostrerà un segno di spunta, a indicare che
è aggiornato, oppure un numero di versione, a indicare che è disponibile una nuova versione.

## Schermata

Se il sito è aggiornato, verrà visualizzata questa schermata:

![Caricamento e aggiornamento: aggiornato](../../../en/images/joomla-update/joomla-update/01-upload-update-up-to-date.png)

Se è disponibile un aggiornamento, verrà visualizzata questa schermata:

![Caricamento e aggiornamento: aggiornamento disponibile](../../../en/images/joomla-update/joomla-update/02-upload-update-available.png)

Se si aggiorna una versione principale o secondaria, verrà visualizzata una schermata di controllo preliminare dell'aggiornamento:

![Caricamento e aggiornamento: controllo preliminare dell'aggiornamento](../../../en/images/joomla-update/joomla-update/03-upload-update-pre-update-check.png)

Seleziona ciascuna delle tre voci di menu per verificare se è necessario intervenire.

## Avvia aggiornamento

Se non stai utilizzando l'ultima versione di Joomla, puoi installare
l'ultimo aggiornamento da questa pagina. Per farlo, assicurati di aver eseguito un backup
e seleziona la casella di controllo **Sono consapevole...** per indicare che l'hai fatto. Quindi
seleziona il pulsante **Avvia aggiornamento** e Joomla installerà l'ultima versione.

La schermata dell'aggiornamento mostra una barra di avanzamento mentre l'aggiornamento è in corso.

### Carica e aggiorna

Puoi utilizzare questo pulsante per aggiornare Joomla se il server è protetto da un
firewall o non è altrimenti in grado di contattare i server degli aggiornamenti. Prima
scarica il pacchetto di aggiornamento di Joomla in formato ZIP dalla pagina ufficiale
dei download di Joomla.

Devi impostare *upload_max_filesize* e *post_max_size* di PHP su 64 MB
e il limite di memoria di PHP su 256 MB. In caso contrario, l'aggiornamento potrebbe non riuscire. Un buon
motivo per eseguire quel backup!

![Carica e aggiorna: carica e installa](../../../en/images/joomla-update/joomla-update/04-upload-update-upload-install.png)

## Opzioni di aggiornamento

Il pulsante Opzioni della barra degli strumenti consente di selezionare il tipo di aggiornamento:

- **Predefinito** Viene utilizzato per i siti configurati per rimanere con la versione installata.
- **Joomla Next** Viene utilizzato per i siti che normalmente passano alla versione principale
  successiva non appena viene rilasciata una versione stabile.
- **URL personalizzato** Per consentire agli sviluppatori di selezionare una fonte di aggiornamento.

*Tradotto da openai.com*