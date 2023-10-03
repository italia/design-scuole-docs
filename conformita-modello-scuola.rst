Criteri di conformità per la misura 1.4.1
============================================

I criteri di conformità guidano alla corretta adozione del modello in termini di esperienza utente, sicurezza, performance e rispetto della normativa per gli istituti scolastici che partecipano agli avvisi di finanziamento di `PA digitale 2026 <https://padigitale2026.gov.it/>`_.

Il DTD verifica il rispetto di tutti i criteri di conformità tramite controlli automatizzati, parzialmente automatizzati e manuali. A questo proposito, è necessario:

- tener conto dei `requisiti tecnici necessari allo svolgimento delle verifiche <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/it/versione-attuale>`_;
- che il sito sia raggiungibile e funzionante anche durante gli **orari notturni**;
- che il sito sia raggiungibile dagli indirizzi IP **15.160.11.200**, **15.160.250.158** e **18.102.41.229** (è necessario che questi indirizzi non vengano bloccati da un eventuale firewall).


A parte il rispetto dei criteri di conformità, sono comunque considerate obbligatorie tutte le buone pratiche che rendono il sito utile, affidabile, facile da usare e accessibile a tutte le persone: completezza e accuratezza delle informazioni, chiarezza di linguaggio, leggibilità dei testi, formattazione appropriata, qualità delle immagini e dei contenuti multimediali.

In aggiunta, è obbligatoria anche la presenza del LOGO UE, in ottemperanza alla normativa europea (art. 34 del Reg. UE 2021/241), assicurandosi che ci sia la dicitura «Finanziato dall’Unione Europea - Nextgeneration EU» e che il logo abbia lo stesso risalto e visibilità di altri eventuali simboli.


``Esperienza utente``

**C.SC.1.1 - Coerenza dell'utilizzo dei font (librerie di caratteri)**

Il sito utilizza `i font <risorse/template-html-pagine.html#i-font-del-modello>`_ indicati nel modello di sito per le scuole.

Riferimenti normativi e tecnici: `sezione La tipografia <https://docs.italia.it/italia/designers-italia/manuale-operativo-design-docs/it/versione-corrente/doc/esperienza-utente/progettare-e-costruire-in-alta-fedelta.html#la-tipografia>`_ all’interno del `Manuale operativo di design <https://docs.italia.it/italia/designers-italia/manuale-operativo-design-docs/it/>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Tutti i titoli (heading) e tutti i paragrafi delle pagine del sito in lingua italiana utilizzano esclusivamente i font Titillium Web, Lora o Roboto Mono come font di default **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio
     
   * - **Tolleranza**
     - Tutti i titoli (heading) e tutti i paragrafi delle pagine del sito in lingua italiana utilizzano Titillium Web, Lora o Roboto Mono come font di default ma sono presenti degli elementi all’interno dei titoli o dei paragrafi che usano altri font di default **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio
     
   * - **Fallimento**
     - Anche solo un titolo (heading) o un paragrafo in qualsiasi pagina del sito in lingua italiana non utilizza Titillium Web, Lora o Roboto Mono come font di default **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio


  

**C.SC.1.2 - Libreria di elementi di interfaccia**

Il sito utilizza la libreria Bootstrap Italia in una versione più recente di 1.6.


Riferimenti normativi e tecnici: `Bootstrap Italia <https://italia.github.io/bootstrap-italia/docs/componenti/introduzione/>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - In tutte le pagine del sito viene utilizzata la libreria Bootstrap Italia **e** la libreria Bootstrap Italia è presente nel tag <head> delle pagine del sito **e** si usano i fondamenti visuali (almeno griglie, spaziature, tipografia) messi a disposizione da Bootstrap Italia **e** si usano solo componenti messi a disposizione da Bootstrap Italia, laddove presenti (es: se c'è bisogno di creare un form è obbligatorio utilizzare i componenti di tipo "form" disponibili nella libreria) **e** la versione in uso è uguale o superiore alla 1.6 **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio
     
   * - **Tolleranza**
     - /
     
   * - **Fallimento**
     - In anche solo una delle pagine del sito non viene utilizzata la libreria Bootstrap Italia **o** la libreria Bootstrap Italia non è presente nel tag <head> delle pagine del sito **o** non si usano i fondamenti visuali (almeno griglie, spaziature, tipografia) messi a disposizione da Bootstrap Italia ** o non si usano solo componenti messi a disposizione da Bootstrap Italia, laddove presenti (es: se c'è bisogno di creare un form è obbligatorio utilizzare i componenti di tipo "form" disponibili nella libreria) **o** la versione in uso è precedente alla 1.6 **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio

 

**C.SC.1.3 - Utilizzo di temi per CMS (Content Management System)**

Nel caso in cui il sito utilizzi `tema messo a disposizione <risorse/tema-wordpress.html>`_ nella documentazione del modello di sito scolastico, lo utilizza nella versione 2.0 o successive.

Riferimenti normativi e tecnici: i temi CMS sono raggiungibili tramite `Designers Italia <https://designers.italia.it/modello/comuni/>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il sito utilizza un tema CMS del modello scuole **e** ne utilizza una versione uguale o superiore alla 2.0
     
   * - **Tolleranza**
     - Il sito non utilizza un tema CMS del modello scuole
     
   * - **Fallimento**
     - Il sito utilizza un tema CMS del modello scuole ma ne utilizza una versione precedente alla 2.0
     
     

**C.SC.1.4 - Voci di menù di primo livello**

Il sito presenta tutte le voci di menù di primo livello, nell'esatto ordine descritto nella documentazione del modello scuole.

Riferimenti normativi e tecnici: le voci del menù sono indicate nel `Grafico dell’alberatura (PDF 27KB) <https://designers.italia.it/files/resources/modelli/scuole/adotta-il-modello-di-sito-scolastico/definisci-architettura-e-contenuti/Alberatura-ModelloScuole-DesignersItalia.pdf>`_ all’interno del `documento di Architettura dell’informazione del modello scuole (ODS 337KB) <https://designers.italia.it/files/resources/modelli/scuole/adotta-il-modello-di-sito-scolastico/definisci-architettura-e-contenuti/Architettura-informazione-sito-scuole.ods>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.


.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - In tutte le pagine del sito le voci obbligatorie del menù sono presenti, corrette e nell'ordine giusto ("Scuola", "Servizi", "Novità", “Didattica”) **e** non sono presenti voci aggiuntive oltre a quelle obbligatorie **e** tramite le voci di menu di primo livello è possibile raggiungere le corrispondenti pagine di primo livello **e** la posizione della pagina deve essere indicata nella struttura delle breadcrumb e rispecchiare quella del menu **e** le URL delle pagine devono seguire l’organizzazione dei menu **e** le pagine raggiungibili dalle voci di menu e le relative sezioni di pagina hanno un contenuto coerente con i titoli delle pagine **e** tutte le pagine raggiungibili dal menu di primo livello appartengono al dominio della scuola **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - In tutte le pagine del sito le voci obbligatorie del menù sono presenti, corrette e nell’ordine giusto ("Scuola", "Servizi", "Novità", “Didattica”) **e** sono presenti fino a 3 voci aggiuntive **e** tramite le voci di menu di primo livello è possibile raggiungere le corrispondenti pagine di primo livello **e** la posizione della pagina deve essere indicata nella struttura delle breadcrumb e rispecchiare quella del menu **e** le pagine raggiungibili dalle voci di menu e le relative sezioni di pagina hanno un contenuto coerente con i titoli delle pagine **e** tutte le pagine raggiungibili dal menu di primo livello appartengono al dominio della scuola **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.

   * - **Fallimento**
     - In anche solo una delle pagine del sito almeno una delle voci obbligatorie è assente o inesatta **o** le voci obbligatorie sono in ordine errato **o** sono presenti 8 o più voci nel menù del sito **o** tramite le voci di menu di primo livello non è possibile raggiungere le corrispondenti pagine di primo livello **o** la posizione di anche solo una pagina non è indicata nella struttura delle breadcrumb o non rispecchia quella del menu **o** anche solo una delle pagine raggiungibili dalle voci di menu o le relative sezioni di pagina non hanno un contenuto coerente con i titoli delle pagine **o** anche solo una delle pagine raggiungibili dal menu di primo livello non appartiene al dominio della scuola **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.



**C.SC.1.5 - Voci di menu di secondo livello**

Il sito presenta le voci di menù di secondo livello come descritto nella documentazione del modello di sito della scuola.

Riferimenti normativi e tecnici: le voci del menù sono indicate nel `Grafico dell’alberatura (PDF 27KB) <https://designers.italia.it/files/resources/modelli/scuole/adotta-il-modello-di-sito-scolastico/definisci-architettura-e-contenuti/Alberatura-ModelloScuole-DesignersItalia.pdf>`_ all’interno del `documento di Architettura dell’informazione del modello scuole (ODS 337KB) <https://designers.italia.it/files/resources/modelli/scuole/adotta-il-modello-di-sito-scolastico/definisci-architettura-e-contenuti/Architettura-informazione-sito-scuole.ods>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.


.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - In tutte le pagine del sito tutte le voci di menu di secondo livello usate rispecchiano quelli presenti nella `documentazione <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_:
     
        - Per la sezione *Scuola*, sono: “Presentazione”, “I luoghi”, “Le persone”, “I numeri della scuola”, “Le carte della scuola”, “Organizzazione”, “La storia”;
        - Per la sezione *Servizi*, sono: “Famiglie e studenti”, “Personale scolastico”, “Percorsi di studio”;
        - Per la sezione *Novità*, sono: “Le notizie”, “Le circolari”, “Calendario eventi”, “Albo online”;
        - Per la sezione *Didattica*, sono: “Offerta formativa”, “Le schede didattiche”, "I progetti delle classi";
       **e** i titoli delle pagine raggiungibili dal menu e i rispettivi titoli usati nelle breadcrumb devono corrispondere alle voci di menu **e** la posizione della pagina deve essere indicata nella struttura delle breadcrumb e rispecchiare quella del menu **e** le pagine raggiungibili dalle voci di menu e le relative sezioni di pagina hanno un contenuto coerente con i titoli delle pagine **e**  tutte le pagine raggiungibili dal menu di secondo livello appartengono al dominio della scuola **e** le URL delle pagine devono seguire l’organizzazione dei menu **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - In tutte le pagine del sito almeno il 30% delle voci di menu di secondo livello usate rispecchiano quelli presenti nella `documentazione <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_ **e** i titoli delle pagine raggiungibili dal menu e i rispettivi titoli usati nelle breadcrumb devono corrispondere alle voci di menu **e** la posizione della pagina deve essere indicata nella struttura delle breadcrumb e rispecchiare quella del menu **e** le pagine raggiungibili dalle voci di menu e le relative sezioni di pagina hanno un contenuto coerente con i titoli delle pagine **e** tutte le pagine raggiungibili dal menu di secondo livello appartengono al dominio della scuola **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.

   * - **Fallimento**
     - In anche solo una pagina del sito meno del 30% delle voci di menu di secondo livello usate rispecchiano quelle presenti nella `documentazione <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_ **o** anche solo il titolo di una pagina raggiungibile dal menu o il rispettivo titolo usato nelle breadcrumb non corrispondono alle voci di menu **o** la posizione di anche solo una pagina non è indicata nella struttura delle breadcrumb o non rispecchia quella del menu **o** anche solo una delle pagine raggiungibili dalle voci di menu o le relative sezioni di pagina non hanno un contenuto coerente con i titoli delle pagine **o** anche solo una delle pagine raggiungibili dal menu di secondo livello non appartiene al dominio della scuola **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.

  

``Normativa``

**C.SC.2.1 - Informativa privacy**

Il sito presenta l'informativa sul trattamento dei dati personali, secondo quanto previsto dalla normativa vigente.

Riferimenti tecnici e normativi: `Normativa GDPR (Artt. 13 e 14, Reg. UE n. 679/2016) <https://www.garanteprivacy.it/regolamentoue>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il link all’informativa sul trattamento dei dati personali è presente nel footer del sito **e** invia all'informativa sul trattamento dei dati personali **e** la pagina di destinazione è sicura (ovvero presenta un certificato https valido e attivo) **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - /
   * - **Fallimento**
     - Il link all’informativa sul trattamento dei dati personali non è presente nel footer del sito **o** non invia all'informativa sul trattamento dei dati personali **o** la pagina di destinazione non è sicura (ovvero non presenta un certificato https valido e attivo) **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.



**C.SC.2.2 - Dichiarazione di accessibilità** 

Il sito espone la dichiarazione di accessibilità in conformità al modello e alle linee guida rese disponibili da AGID in ottemperanza alla normativa vigente in materia di accessibilità e con livelli di accessibilità contemplati nelle specifiche tecniche WCAG 2.1.

Riferimenti tecnici e normativi: `Linee guida AGID per la dichiarazione di accessibilità <https://www.agid.gov.it/it/design-servizi/accessibilita/dichiarazione-accessibilita>`_, le `Linee guida AgID sull’accessibilità degli strumenti informatici <https://docs.italia.it/AgID/documenti-in-consultazione/lg-accessibilita-docs/it/stabile/index.html>`_, la `Legge 9 gennaio 2004 n. 4 <https://www.normattiva.it/atto/caricaDettaglioAtto?atto.dataPubblicazioneGazzetta=2004-01-17&atto.codiceRedazionale=004G0015&atto.articolo.numero=0&atto.articolo.sottoArticolo=1&atto.articolo.sottoArticolo1=10&qId=cb6b9a05-f5c3-40ac-81b8-f89e73e5b4c7&tabID=0.029511124589268523&title=lbl.dettaglioAtto>`_, le `Web Content Accessibility Guidelines (WCAG 2.1) <https://www.w3.org/Translations/WCAG21-it/#background-on-wcag-2>`_ e la `Direttiva Reg. UE n. 2102/2016 <https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX%3A32016L2102>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il link alla dichiarazione di accessibilità è presente nel footer del sito **e** invia a una dichiarazione di accessibilità secondo le norme AGID **e** la dichiarazione è conforme, anche parzialmente, alle specifiche tecniche WCAG 2.1 **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - /

   * - **Fallimento**
     - Il link alla dichiarazione di accessibilità non è presente nel footer del sito **o** non invia a una dichiarazione di accessibilità secondo le norme AGID **o** la dichiarazione non è conforme alle specifiche tecniche WCAG 2.1 **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.


**C.SC.2.3 - Cookie**

Il sito presenta cookie tecnici in linea con la normativa vigente.

Riferimenti tecnici e normativi: `Linee guida cookie e altri strumenti di tracciamento - 10 giugno 2021 del Garante per la protezione dei dati personali <https://www.garanteprivacy.it/home/docweb/-/docweb-display/docweb/9677876>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il dominio di tutti i cookie già presenti in tutte le pagine del sito, ovvero senza che sia stata espressa una preferenza da parte dell’utente riguardo il loro uso, è corrispondente al dominio del sito web della scuola **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - /

   * - **Fallimento**
     - Il dominio di anche solo un cookie già presente in anche solo una pagina del sito, ovvero senza che sia stata espressa una preferenza da parte dell’utente riguardo il suo uso, non è corrispondente al dominio del sito web della scuola **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.




``Sicurezza``

**C.SC.3.1 - Certificato https**

Il sito ha un certificato https valido e attivo.

Riferimenti tecnici e normativi: `Raccomandazioni AgID in merito allo standard Transport Layer Security (TLS) <https://cert-agid.gov.it/wp-content/uploads/2020/11/AgID-RACCSECTLS-01.pdf>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Tutte le pagine del sito utilizzano il protocollo https **e** il certificato https è valido **e** il certificato https non è obsoleto (la versione del TLS e la suite di cifratura associata sono adatte).
     
   * - **Tolleranza**
     - /

   * - **Fallimento**
     - Anche solo una pagina del sito non utilizza il protocollo https **o** il certificato https è scaduto **o** il certificato https è obsoleto (la versione del TLS è obsoleta o la suite di cifratura associata è inadatta).






Raccomandazioni
~~~~~~~~~~~~~~~

Per migliorare ulteriormente l’esperienza dei cittadini e garantire l’uso di tecnologie aggiornate, vengono indicate raccomandazioni progettuali aggiuntive che seppur non sono parte delle verifiche di conformità tecnica, rimangono valide secondo le indicazioni di legge e le linee guida.

**R.SC.1.1 - Vocabolari controllati**

Il sito utilizza i vocabolari forniti dal modello di sito per le scuole.

Riferimenti normativi e tecnici: il vocabolario controllato del modello è disponibile alla voce Le parole della scuola all’interno del `documento di Architettura dell’informazione del modello scuole (ODS 337KB) <https://designers.italia.it/files/resources/modelli/scuole/adotta-il-modello-di-sito-scolastico/definisci-architettura-e-contenuti/Architettura-informazione-sito-scuole.ods>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

Da evitare:

- più del 50% degli argomenti non appartengono alle voci del modello scuole;
- l’elenco completo degli argomenti utilizzati non è presente nella pagina dei risultati di ricerca;
- il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.


**R.SC.1.2 - Schede informative di servizio**

Le schede informative dei servizi mostrano gli attributi segnalati all’interno dell’architettura dell’informazione, nell’ordine segnalato nella documentazione del modello.

Riferimenti normativi e tecnici: sezione "CT: Servizio" all’interno del `documento di Architettura dell’informazione del modello scuole (ODS 337KB) <https://designers.italia.it/files/resources/modelli/scuole/adotta-il-modello-di-sito-scolastico/definisci-architettura-e-contenuti/Architettura-informazione-sito-scuole.ods>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.


Da evitare:

- anche solo in una scheda servizio più di 2 delle voci richieste e i relativi contenuti non sono presenti: “Tipologia” (contenuto breadcrumb), “Titolo”, “Argomenti”, “Descrizione breve”, “A cosa serve”, “Come si accede al servizio”, “Luogo” (deve presentare “indirizzo”, “posizione GPS tramite mappa”, “orario per il pubblico”, “email”, “PEC”, “telefono”), “Tempi e scadenze”, “Contatti”, “Struttura responsabile”, “Metadati”;

- anche solo in una scheda servizio più di 1 delle voci utilizzate tra le seguenti non è nell’ordine corretto: “Cos’è“, “Come si accede al servizio”, “Cosa serve”, “Tempi e scadenze”, “Contatti”, “Ulteriori informazioni”;

- il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.
 
 
**R.SC.2.1 - Riuso**

La scuola mette a riuso sotto licenza aperta il software secondo le Linee Guida “acquisizione e riuso di software e riuso di software per le pubbliche amministrazioni.

Riferimenti tecnici e normativi: `Codice dell’amministrazione digitale (d’ora in poi anche “CAD”) - Art. 69 (Riuso delle soluzioni e standard aperti) <https://docs.italia.it/italia/piano-triennale-ict/codice-amministrazione-digitale-docs/it/stabile/_rst/capo_VI-articolo_69.html>`_; `AGID - Linee guida su acquisizione e riuso di software per le pubbliche amministrazioni <https://www.agid.gov.it/it/design-servizi/riuso-open-source/linee-guida-acquisizione-riuso-software-pa>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

Da evitare:

- i repository con i file sorgente del sito della scuola non sono inseriti sul `catalogo del riuso <https://developers.italia.it/it/search?pnrr=1&type=all_catalogue&sort_by=release_date&page=0>`_.


**R.SC.2.2 - Licenza e attribuzione**

Il sito della scuola pubblica dati, documenti e informazioni con licenza aperta comunicandolo nella pagina delle note legali del sito come descritto nella documentazione del modello di sito scolastico.

Riferimenti normativi e tecnici: `CAD - Art. 52 d.lgs. 82/2005 <https://docs.italia.it/italia/piano-triennale-ict/codice-amministrazione-digitale-docs/it/stabile/_rst/capo_V-sezione_I-articolo_52.html>`_; `art. 7, comma 1, D.Lgs. n. 33/2013 <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2013-03-14;33>`_; `d.lgs. n. 36/2006 <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2006-01-24;36!vig=>`_; `AGID - Linee guida su acquisizione e riuso di software per le pubbliche amministrazioni <https://www.agid.gov.it/it/design-servizi/riuso-open-source/linee-guida-acquisizione-riuso-software-pa>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.


Da evitare:

- la scuola non pubblica dati, documenti o informazioni con licenza aperta CC-BY 4.0;
- la licenza non viene comunicata nella pagina delle “note legali“ raggiungibile da un link nel footer del sito;
- all’interno della pagina delle “note legali” non è presente una sezione “Licenza dei contenuti” che riporta la dicitura raccomandata:
   
   “In applicazione del principio open by default ai sensi dell’articolo 52 del decreto legislativo 7 marzo 2005, n. 82 (CAD) e salvo dove diversamente specificato (compresi i contenuti incorporati di terzi), i dati, i documenti e le informazioni pubblicati sul sito sono rilasciati con `licenza CC-BY 4.0 <https://creativecommons.org/licenses/by/4.0/legalcode.it>`_. Gli utenti sono quindi liberi di condividere (riprodurre, distribuire, comunicare al pubblico, esporre in pubblico), rappresentare, eseguire e recitare questo materiale con qualsiasi mezzo e formato e modificare (trasformare il materiale e utilizzarlo per opere derivate) per qualsiasi fine, anche commerciale con il solo onere di attribuzione, senza apporre restrizioni aggiuntive.”

- il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

  
**R.SC.2.3 - Infrastrutture cloud**

Il sito della scuola è ospitato su infrastrutture qualificate ai sensi della normativa vigente.

Riferimenti tecnici e normativi: per consentire un'erogazione più sicura, efficiente e scalabile del sito delle scuole, può essere utile considerare di impostare l'infrastruttura che lo ospita in cloud, secondo quanto descritto nella `Strategia Cloud Italia <https://cloud.italia.it/strategia-cloud-pa/>`_. Hosting e re-hosting non sono finanziabili ai sensi del presente avviso, tuttavia tali costi di infrastruttura potrebbero essere coperti dalla *misura 1.2 Abilitazione e facilitazione migrazione al Cloud per le scuola*, attraverso la scelta del servizio per l'amministrazione "Sito web"; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.


**R.SC.3.1 - Velocità e tempi di risposta**

Il sito della scuola presenta livelli di prestazioni (media pesata di 6 metriche standard) pari o superiori a 50 secondo quanto calcolato tramite le librerie Lighthouse.

Riferimenti normativi e tecnici: `LIGHTHOUSE performance scoring guide <https://web.dev/performance-scoring/>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

Da evitare:

- il sito presenta livelli di prestazione (media pesata di 6 metriche standard) inferiori a 50 quando testato in modalità “mobile” tramite le `librerie Lighthouse <https://web.dev/performance-scoring/>`_.


Buone pratiche necessarie per superare l'asseverazione
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. Ogni pagina/contenuto deve essere pubblicato nella sezione più coerente rispetto all'alberatura del sito e tutte le pagine devono avere breadcrumb coerenti con la loro posizione nel menu e nella struttura del sito. (Esempio: la pagina relativa alla notizia "Iscrizioni a.s. 2023/24" non passerebbe il controllo con la seguente breadcrumb "Home > Iscrizioni a.s.2023/24". La breadcrumb corretta sarebbe " Home > Novità > Le notizie > Iscrizioni a.s. 2023/24").

2. Voci di menu e titoli di pagina non possono essere interamente in maiuscolo o in corsivo (a meno che non siano sigle o acronimi)

3. Usare in modo corretto e sporadico il grassetto, il corsivo e il maiuscolo

4. Tutte le pagine devono avere un titolo coerente con il tipo di contenuto, breadcrumb coerenti con l'alberatura del sito e contenuti chiari, coerenti, corretti e completi delle informazioni essenziali. In particolare, i seguenti content type devono includere almeno i seguenti attributi (N.B. Le descrizioni devono essere sempre presenti come testo in pagina):

.. list-table::
   :widths: 10 30 30
   :header-rows: 1

   * - Content Type
     - Sezione di riferimento
     - Attributi obbligatori
     
   * - Struttura organizzativa
     - Scuola > Organizzazione
     - - Descrizione (breve o estesa)
       - Cosa fa (Descrizione dei compiti assegnati alla struttura)
       - Almeno uno tra: (1) Sede con indirizzo, (2) Orari per il pubblico, (3) Contatti

   * - Percorso/Indirizzo di studio
     - Servizi > Percorsi di studio
     - - Grado del percorso/indirizzo (per esempio: Infanzia, Primaria, Secondaria primo grado, Secondaria secondo grado, Percorsi di istruione e formazione professionale)
       - Descrizione (breve o estesa)
       - Almeno uno tra: (1) Come accede al percorso/indirizzo, (2) Contatti

   * - Documenti
     - Scuola > Le carte della scuola
     - - Descrizione (breve o estesa)
       - Documento principale (allegato scaricabile o link al documento)
       - Almeno uno tra: (1) Ufficio respondabile del documento, (2) Tipo di documento (per esempio: Documento didattico, Regolamento, Verbale, etc)

   * - Circolare
     - Novità > Circolari
     - - Tipologia circolare (a chi è rivolta, se personale o famiglie/studenti)
       - Almeno uno tra: (1) Testo della circolare, (2) Descrizione del contenuto della circolare

   * - Scheda didattica
     - Didattica > Schede didattiche
     - - Obiettivi della scheda didattica
       - Descrizione delle attività proposte
