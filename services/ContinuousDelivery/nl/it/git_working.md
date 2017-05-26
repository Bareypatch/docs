---

copyright:
  years: 2015, 2017
lastupdated: "2017-4-11"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:screen:.screen}
{:codeblock:.codeblock}

# Repository Git e tracciamento del problema (beta)
{: #git_working}

Collabora con il tuo team e gestisci il tuo codice di origine con un repository (repo) Git e il programma di traccia dei problemi ospitato da IBM  e creato con [GitLab Community Edition ![Icona link esterno](../../icons/launch-glyph.svg "Icona link esterno")](https://about.gitlab.com/){:new_window}.
{: shortdesc}

L'integrazione dello strumento Repository Git e tracciamento del problema supporta i team per gestire il codice e per la collaborazione in modi diversi:
   * Gestire i repository Git attraverso i controlli dell'accesso accurati che mantengono il codice sicuro
   * Rivedere il codice e migliorare la collaborazione tramite le richieste di unione
   * Tracciare i problemi e condividere le idee tramite il programma di traccia del problema
   * Documentare i progetti nel sistema wiki

**Nota:** poiché questa integrazione dello strumento è creata in GitLab Community Edition e ospitata da IBM su Bluemix, sono disponibili alcune opzioni GitLab. Ad esempio, Delivery Pipeline fornisce l'integrazione e la fornitura continue per Bluemix; altrimenti, le funzioni di integrazione continua in GitLab non sono supportate. In aggiunta, le funzioni di gestione non sono disponibili perché sono gestite da IBM.

## Limiti dimensione repository e file
{: #git_limits}

I file sono tassativamente limitati a 100 MB. Il limite di dimensione del repository consigliato è 1 GB. Se il tuo repository supera 1 GB, potresti ricevere un'email con una richiesta di riduzione della dimensione del repository.

## Utilizzo di Repository Git e tracciamento del problema in locale
{: #git_authentication}

Puoi accedere localmente ai repository Git memorizzati in Repository Git e tracciamento del problema. Per istruzioni sulla configurazione di Git in locale, vedi [Start using Git on the command line ![icona link esterno](../../icons/launch-glyph.svg "External link icon")](https://git.ng.bluemix.net/help/gitlab-basics/start-using-git){:new_window}.

### Creazione di un token di accesso personale o di una chiave SSH per l'autenticazione  
Per completare le operazioni Git remote, come ad esempio `clone` o `push`, dal tuo repository Git locale, devi utilizzare un token di accesso personale o una chiave SSH per l'autenticazione con GitLab.

* Per configurare un token di accesso personale, consulta [Personal access tokens ![Icona link esterno](../../icons/launch-glyph.svg "External link icon")](https://git.ng.bluemix.net/help/api/README.html#personal-access-tokens){:new_window}.
* Per configurare una chiave SSH, consulta [SSH ![Icona link esterno](../../icons/launch-glyph.svg "External link icon")](https://git.ng.bluemix.net/help/ssh/README){:new_window} o [How to create your SSH Keys ![Icona link esterno](../../icons/launch-glyph.svg "External link icon")](https://git.ng.bluemix.net/help/gitlab-basics/create-your-ssh-keys){:new_window}. L'accesso ai tuoi repository con l'autenticazione SSH potrebbe richiedere ulteriore configurazione per i proxy e i firewall.
