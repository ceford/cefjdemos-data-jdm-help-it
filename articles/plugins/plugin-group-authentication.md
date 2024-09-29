<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group / Display title: Gruppo di Autenticazione -->

## Descrizione del Gruppo

I plugin in questo gruppo sono utilizzati per il login standard degli utenti alle interfacce del Sito o dell'Amministratore. L'impostazione predefinita è l'Autenticazione di Joomla. Il metodo *Cookie* viene utilizzato insieme alla funzione *Remember Me* solo per il login al Sito. Il cookie viene impostato dopo il primo login con uno degli altri metodi.

## Autenticazione - Cookie

![plugin di autenticazione cookie](../../../en/images/plugins/plugin-group-authentication-cookie.png)

- **Durata del Cookie** Il numero di giorni fino alla scadenza del cookie di autenticazione. Altri fattori potrebbero causarne la scadenza prima di questo termine. Durate più lunghe sono meno sicure.
- **Lunghezza della Chiave** La lunghezza della chiave da utilizzare per crittografare il cookie. Lunghezze maggiori sono più sicure, ma rallenteranno le prestazioni.

## Autenticazione - Joomla

Questo plugin elabora il metodo di autenticazione utente predefinito in Joomla. Non ha opzioni.

## Autenticazione - LDAP

Questo plugin gestisce l'autenticazione degli utenti contro un server LDAP.

![plugin di autenticazione ldap](../../../en/images/plugins/plugin-group-authentication-ldap.png)

- **Host** L'URL dell'host. Ad esempio, `openldap.mycompany.org`.
- **Porta** Il numero di porta. Il valore predefinito è 389.
- **LDAP V3** Se questo host utilizza o meno la versione 3 di LDAP. Il valore predefinito è LDAP v2.
- **Negozia TLS** Se utilizzare o meno la crittografia TLS con questo host. Se impostato su *Sì*, tutto il traffico da e verso questo server deve essere crittografato.
- **Segui i Referral** Se impostare il flag LDAP_OPT_REFERRALS su Sì o No. Per gli host Windows 2003 deve essere impostato su No.
- **Metodo di Autorizzazione** *Bind Directly as User* o *Bind and Search*.
- **Base DN** Il DN di base del tuo server LDAP.
- **Stringa di Ricerca** Una stringa di query utilizzata per cercare un determinato utente. La parola chiave `[search]` viene sostituita dal login digitato dall'utente. Ad esempio: `uid=[search]`. È possibile inserire più di una stringa di ricerca. Separare ciascuna con un punto e virgola `;`. Questo viene utilizzato solo durante la ricerca.
- **DN dell'Utente** La parola chiave [username] viene sostituita dinamicamente dal nome utente digitato dall'utente. Un esempio di stringa è: `uid=[username], dc=[my-domain], dc=[com]`. È possibile inserire più di una stringa. Separare ciascuna con un punto e virgola `;`. Questo viene utilizzato solo se il Metodo di Autorizzazione sopra è impostato su *Bind Directly as User*.
- **Username di Connessione e Password di Connessione** Questi definiscono i parametri di connessione per la fase di ricerca del DN. Per una ricerca anonima, lasciare entrambi questi campi vuoti. Per una connessione amministrativa, lo *Username di Connessione* è il nome utente di un account amministrativo (ad esempio, *Administrator*). In questo caso, la *Password di Connessione* è la password effettiva di questo account amministrativo.
- **Mappa: Nome Completo** L'attributo LDAP che contiene il nome completo dell'utente.
- **Mappa: Email** L'attributo LDAP che contiene l'indirizzo email dell'utente.
- **Mappa: ID Utente** L'attributo LDAP che contiene l'ID di accesso dell'utente. Per Active Directory, questo è `sAMAccountName`.
- **Debug** Abilita il debug preimpostato a livello 7.

*Tradotto da openai.com*  

