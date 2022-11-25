Conformità al modello di sito scolastico
========================================

I criteri di conformità guidano alla corretta adozione del modello in termini di esperienza utente, sicurezza, performance e rispetto della normativa. 

Per gli istituti scolastici che partecipano agli avvisi di finanziamento di `PA digitale 2026 <https://padigitale2026.gov.it/>`_ per l’aggiornamento del sito scolastico, il DTD verifica il rispetto dei requisiti di conformità tramite controlli automatizzati, parzialmente automatizzati e manuali. Pertanto, è necessario tener conto dei `requisiti tecnici necessari allo svolgimento delle verifiche <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/it/versione-attuale>`_.




``Esperienza utente``

**C.SC.1.1 - Coerenza dell'utilizzo dei font (librerie di caratteri)**

Il sito utilizza `i font <risorse/template-html-pagine.html#i-font-del-modello>`_ indicati nel modello di sito per le scuole.

Riferimenti normativi e tecnici: `sezione La tipografia <https://docs.italia.it/italia/designers-italia/design-linee-guida-docs/it/stabile/doc/user-interface/il-disegno-di-un-interfaccia-e-lo-ui-kit.html#la-tipografia>`_ all’interno delle `Linee guida di design per i servizi web della Pubblica Amministrazione <https://docs.italia.it/italia/designers-italia/design-linee-guida-docs/it/stabile/index.html>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Tutti i titoli (heading) e tutti i paragrafi delle pagine del sito in lingua italiana devono usare esclusivamente i font Titillium Web, Lora e Roboto Mono **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio
     
   * - **Tolleranza**
     - Tutti i titoli (heading) e tutti i paragrafi delle pagine del sito in lingua italiana devono includere Titillium Web o Lora tra i font utilizzati **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio
     
   * - **Fallimento**
     - Anche solo un titolo (heading) o un paragrafo in qualsiasi pagina del sito in lingua italiana non include Titillium Web o Lora tra i font utilizzati **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio


  

**C.SC.1.2 - Libreria di elementi di interfaccia**

Il sito utilizza la libreria Bootstrap Italia in una versione più recente di 1.6.


Riferimenti normativi e tecnici: `Bootstrap Italia <https://italia.github.io/bootstrap-italia/docs/componenti/introduzione/>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il sito utilizza la libreria Bootstrap Italia in una versione uguale o superiore alla 1.6.0 **e** la libreria Bootstrap Italia è collegata nell’head del sito
     
   * - **Tolleranza**
     - /
     
   * - **Fallimento**
     - Il sito non utilizza la libreria Bootstrap Italia **o** la libreria Bootstrap Italia non è collegata nell’head del sito **o** la versione utilizzata è precedente alla 1.6.0

 

**C.SC.1.3 - Utilizzo di temi per CMS (Content Management System)**

Nel caso in cui il sito utilizzi `tema messo a disposizione <risorse/tema-wordpress.html>`_ nella documentazione del modello di sito scolastico, lo utilizza nella versione più recente disponibile alla data di inizio lavori.

Riferimenti normativi e tecnici: i temi CMS sono raggiungibili tramite `Designers Italia <https://designers.italia.it/modello/comuni/>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il sito utilizza un tema CMS del modello scuole **e** ne utilizza la versione più recente disponibile alla data di inizio lavori **e** ne utilizza una versione uguale o superiore alla v2.0
     
   * - **Tolleranza**
     - Il sito non utilizza un tema CMS del modello scuole
     
   * - **Fallimento**
     - Il sito utilizza un tema CMS del modello scuole ma non ne utilizza la versione più recente disponibile alla data di inizio lavori o ne utilizza una versione precedente alla v2.0
     
     

**C.SC.1.4 - Voci di menù di primo livello**

Il sito presenta tutte le voci di menù di primo livello, nell'esatto ordine descritto nella documentazione del modello scuole.

Riferimenti normativi e tecnici: le voci del menù sono indicate nel `Grafico dell’alberatura <https://docs.google.com/drawings/d/1yEFOj3S7vciOoehm9Sa51ahvzsEXpqHCiPria-K7o_k/edit>`_ all’interno del `documento di Architettura dell’informazione del modello scuole <https://docs.google.com/spreadsheets/d/1MoayTY05SE4ixtgBsfsdngdrFJf_Z2KNvDkMF3tKfc8/edit#gid=782511705>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.


.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Le voci obbligatorie del menù sono presenti, corrette e nell'ordine giusto:
     
        - "Scuola"
        - "Servizi"
        - "Novità"
        - “Didattica”
       **e** non sono presenti voci aggiuntive oltre a quelle obbligatorie **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - Le voci obbligatorie del menù sono presenti, corrette e nell’ordine giusto **e** sono presenti fino a 3 voci aggiuntive **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.

   * - **Fallimento**
     - Almeno una delle voci obbligatorie è assente o inesatta **o** le voci obbligatorie sono in ordine errato **o** sono presenti 8 o più voci nel menù di primo livello del sito **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.



**C.SC.1.5 - Voci di menu di secondo livello**

Il sito presenta almeno il 30% delle voci di menu di secondo livello in base a quanto descritto dalla documentazione del modello di sito per le scuole.

Riferimenti normativi e tecnici: le voci del menù sono indicate nel `Grafico dell’alberatura <https://docs.google.com/drawings/d/1yEFOj3S7vciOoehm9Sa51ahvzsEXpqHCiPria-K7o_k/edit>`_ all’interno del `documento di Architettura dell’informazione del modello scuole <https://docs.google.com/spreadsheets/d/1MoayTY05SE4ixtgBsfsdngdrFJf_Z2KNvDkMF3tKfc8/edit#gid=782511705>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.


.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Tutte le voci di menu di secondo livello usate rispecchiano quelli presenti nella `documentazione <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_:
     
        - Per la sezione *Scuola*, sono: “Presentazione”, “I luoghi”, “Le persone”, “I numeri della scuola”, “Le carte della scuola”, “Organizzazione”, “La storia”;
        - Per la sezione *Servizi*, sono: “Famiglie e studenti”, “Personale scolastico”, “Percorsi di studio”;
        - Per la sezione *Novità*, sono: “Le notizie”, “Le circolari”, “Calendario eventi”, “Albo online”;
        - Per la sezione *Didattica*, sono: “Offerta formativa”, “Le schede didattiche”, "I progetti delle classi";
       **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - Almeno il 30% delle voci di menu di secondo livello usate rispecchiano quelli presenti nella `documentazione <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_ **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.

   * - **Fallimento**
     - Meno del 30% delle voci di menu di secondo livello usate rispecchiano quelle presenti nella `documentazione <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_ **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.

  

``Normativa``

**C.SC.2.1 - Informativa privacy**

Il sito presenta l'informativa sul trattamento dei dati personali, secondo quanto previsto dalla normativa vigente.

Riferimenti tecnici e normativi: `Normativa GDPR (Artt. 13 e 14, Reg. UE n. 679/2016) <https://www.garanteprivacy.it/regolamentoue>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il link all’informativa sul trattamento dei dati personali è presente nel footer del sito **e** invia a una informativa sul trattamento dei dati personali valida secondo il regolamento GDPR **e** la pagina di destinazione è sicura (ovvero presenta un certificato https valido e attivo) **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - Il link all’informativa sul trattamento dei dati personali è presente nel footer del sito **e** invia a una informativa sul trattamento dei dati personali valida secondo il regolamento GDPR **e** la pagina di destinazione non è sicura (ovvero non presenta un certificato https valido e attivo) **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.

   * - **Fallimento**
     - Il link all’informativa sul trattamento dei dati personali non è presente nel footer del sito **o** invia a una informativa sul trattamento dei dati personali non valida secondo il regolamento GDPR **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.



**C.SC.2.2 - Dichiarazione di accessibilità** 

Il sito espone la dichiarazione di accessibilità in conformità al modello e alle linee guida rese disponibili da AgID in ottemperanza alla normativa vigente in materia di accessibilità e con livelli di accessibilità contemplati nelle specifiche tecniche WCAG 2.1.

Riferimenti tecnici e normativi: `Linee guida AGID per la dichiarazione di accessibilità <https://www.agid.gov.it/it/design-servizi/accessibilita/dichiarazione-accessibilita>`_, le `Linee guida AgID sull’accessibilità degli strumenti informatici <https://docs.italia.it/AgID/documenti-in-consultazione/lg-accessibilita-docs/it/stabile/index.html>`_, la `Legge 9 gennaio 2004 n. 4 <https://www.normattiva.it/atto/caricaDettaglioAtto?atto.dataPubblicazioneGazzetta=2004-01-17&atto.codiceRedazionale=004G0015&atto.articolo.numero=0&atto.articolo.sottoArticolo=1&atto.articolo.sottoArticolo1=10&qId=cb6b9a05-f5c3-40ac-81b8-f89e73e5b4c7&tabID=0.029511124589268523&title=lbl.dettaglioAtto>`_, le `Web Content Accessibility Guidelines (WCAG 2.1) <https://www.w3.org/Translations/WCAG21-it/#background-on-wcag-2>`_ e la `Direttiva Reg. UE n. 2102/2016 <https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX%3A32016L2102>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il link alla dichiarazione di accessibilità è presente nel footer del sito **e** invia a una dichiarazione di accessibilità valida secondo le norme AgID **e** il sito presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.
     
   * - **Tolleranza**
     - /

   * - **Fallimento**
     - Il link alla dichiarazione di accessibilità non è presente nel footer del sito **o** il link invia a una dichiarazione di accessibilità non valida secondo le norme AgID **o** il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.


**C.SC.2.3 - Cookie**

Il sito presenta cookie tecnici in linea con la normativa vigente.

Riferimenti tecnici e normativi: `Linee guida cookie e altri strumenti di tracciamento - 10 giugno 2021 del Garante per la protezione dei dati personali <https://www.garanteprivacy.it/home/docweb/-/docweb-display/docweb/9677876>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il sito presenta solo cookie che rispettano le linee guida del Garante per la protezione dei dati personali **e** il dominio di tutti i cookie presenti nel sito è corrispondente al dominio del sito web della scuola.
     
   * - **Tolleranza**
     - /

   * - **Fallimento**
     - Il sito presenta cookie che non rispettano le linee guida del Garante per la protezione dei dati personali **o** il dominio di anche solo un cookie presente nel sito non è corrispondente al dominio del sito web della scuola.




``Sicurezza``

**C.SC.3.1 - Certificato https**

Il sito ha un certificato https valido e attivo.

Riferimenti tecnici e normativi: `Raccomandazioni AgID in merito allo standard Transport Layer Security (TLS) <https://cert-agid.gov.it/wp-content/uploads/2020/11/AgID-RACCSECTLS-01.pdf>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

.. list-table::
   :widths: 10 30
   :header-rows: 0

   * - **Successo**
     - Il sito utilizza il protocollo https **e** il certificato https è valido **e** il certificato https non è obsoleto (la versione del TLS e la suite di cifratura associata sono adatte).
     
   * - **Tolleranza**
     - /

   * - **Fallimento**
     - Il sito non utilizza il protocollo https **o** il certificato https è scaduto **o** il certificato https è obsoleto (la versione del TLS è obsoleta o la suite di cifratura associata è inadatta).






Raccomandazioni
~~~~~~~~~~~~~~~

Per migliorare ulteriormente l’esperienza dei cittadini e garantire l’uso di tecnologie aggiornate, vengono indicate raccomandazioni progettuali aggiuntive che seppur non sono parte delle verifiche di conformità tecnica, rimangono valide secondo le indicazioni di legge e le linee guida.

**R.SC.1.1 - Vocabolari controllati**

Il sito utilizza i vocabolari forniti dal modello di sito per le scuole.

Riferimenti normativi e tecnici: il vocabolario controllato del modello è disponibile alla voce `Le parole della scuola <https://docs.google.com/spreadsheets/d/1MoayTY05SE4ixtgBsfsdngdrFJf_Z2KNvDkMF3tKfc8/edit#gid=2135815526>`_ all’interno del `documento di Architettura dell’informazione del modello scuole <https://docs.google.com/spreadsheets/d/1MoayTY05SE4ixtgBsfsdngdrFJf_Z2KNvDkMF3tKfc8/edit#gid=782511705>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.

Da evitare:

- più del 50% degli argomenti non appartengono alle `voci del modello scuole <https://docs.google.com/spreadsheets/d/1MoayTY05SE4ixtgBsfsdngdrFJf_Z2KNvDkMF3tKfc8/edit#gid=2135815526>`_;
- il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_ per questo criterio.


**R.SC.1.2 - Schede informative di servizio**

Le schede informative dei servizi mostrano gli attributi segnalati all’interno dell’architettura dell’informazione, nell’ordine segnalato nella documentazione del modello.

Riferimenti normativi e tecnici: sezione `CT: Servizio <https://docs.google.com/spreadsheets/d/1MoayTY05SE4ixtgBsfsdngdrFJf_Z2KNvDkMF3tKfc8/edit#gid=0>`_ all’interno del `documento di Architettura dell’informazione del modello scuole <https://docs.google.com/spreadsheets/d/1MoayTY05SE4ixtgBsfsdngdrFJf_Z2KNvDkMF3tKfc8/edit#gid=782511705>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_; `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.


Da evitare:

- anche solo una scheda servizio non presenta più di due delle informazioni obbligatorie
- anche solo una scheda servizio presenta le informazioni obbligatorie in un ordine diverso
- il sito non presenta i *data attribute* indicati nella `Documentazione delle App di valutazione dell’adesione ai modelli <https://docs.italia.it/italia/designers-italia/app-valutazione-modelli-docs/>`_.
 
 
**R.SC.2.1 - Riuso**

La scuola mette a riuso sotto licenza aperta il software secondo le Linee Guida “acquisizione e riuso di software e riuso di software per le pubbliche amministrazioni.

Riferimenti tecnici e normativi: `Codice dell’amministrazione digitale (d’ora in poi anche “CAD”) - Art. 69 (Riuso delle soluzioni e standard aperti) <https://docs.italia.it/italia/piano-triennale-ict/codice-amministrazione-digitale-docs/it/stabile/_rst/capo_VI-articolo_69.html>`_; `AGID - Linee guida su acquisizione e riuso di software per le pubbliche amministrazioni <https://www.agid.gov.it/it/design-servizi/riuso-open-source/linee-guida-acquisizione-riuso-software-pa>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

Da evitare:

- i repository con i file sorgente del sito della scuola non sono inseriti sul `catalogo del riuso <https://developers.italia.it/it/search?pnrr=1&type=all_catalogue&sort_by=release_date&page=0>`_.


**R.SC.2.2 - Licenza e attribuzione**

Il sito della scuola pubblica dati, documenti e informazioni con licenza aperta (es. CC-BY 4.0).

Riferimenti normativi e tecnici: `CAD - Art. 52 d.lgs. 82/2005 <https://docs.italia.it/italia/piano-triennale-ict/codice-amministrazione-digitale-docs/it/stabile/_rst/capo_V-sezione_I-articolo_52.html>`_; `art. 7, comma 1, D.Lgs. n. 33/2013 <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2013-03-14;33>`_; `d.lgs. n. 36/2006 <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2006-01-24;36!vig=>`_; `AGID - Linee guida su acquisizione e riuso di software per le pubbliche amministrazioni <https://www.agid.gov.it/it/design-servizi/riuso-open-source/linee-guida-acquisizione-riuso-software-pa>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.


Da evitare:

- la scuola non segue le linee guida AGID sulla pubblicazione di dati, documenti o informazioni;
- all’interno della pagina delle “note legali” non è presente una sezione “Licenza dei contenuti” che riporta la dicitura raccomandata:
   
   “In applicazione del principio open by default ai sensi dell’articolo 52 del decreto legislativo 7 marzo 2005, n. 82 (CAD) e salvo dove diversamente specificato (compresi i contenuti incorporati di terzi), i dati, i documenti e le informazioni pubblicati sul sito sono rilasciati con licenza CC-BY 4.0. Gli utenti sono quindi liberi di condividere (riprodurre, distribuire, comunicare al pubblico, esporre in pubblico), rappresentare, eseguire e recitare questo materiale con qualsiasi mezzo e formato e modificare (trasformare il materiale e utilizzarlo per opere derivate) per qualsiasi fine, anche commerciale con il solo onere di attribuzione, senza apporre restrizioni aggiuntive.”

  
**R.SC.2.3 - Infrastrutture cloud**

Il sito della scuola è ospitato su infrastrutture qualificate ai sensi della normativa vigente.

Riferimenti tecnici e normativi: per consentire un'erogazione più sicura, efficiente e scalabile del sito delle scuole, può essere utile considerare di impostare l'infrastruttura che lo ospita in cloud, secondo quanto descritto nella `Strategia Cloud Italia <https://cloud.italia.it/strategia-cloud-pa/>`_. Hosting e re-hosting non sono finanziabili ai sensi del presente avviso, tuttavia tali costi di infrastruttura potrebbero essere coperti dalla *misura 1.2 Abilitazione e facilitazione migrazione al Cloud per le scuola*, attraverso la scelta del servizio per l'amministrazione "Sito web"; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.


**R.SC.3.1 - Velocità e tempi di risposta**

Il sito della scuola presenta livelli di prestazioni (media pesata di 6 metriche standard) pari o superiori a 50 secondo quanto calcolato tramite le librerie Lighthouse.

Riferimenti normativi e tecnici: `LIGHTHOUSE performance scoring guide <https://web.dev/performance-scoring/>`_; `Documentazione del modello scuole <https://docs.italia.it/italia/designers-italia/design-scuole-docs/it/>`_.

Da evitare:

- il sito presenta livelli di prestazione (media pesata di 6 metriche standard) inferiori a 50 secondo quanto calcolato tramite le `librerie Lighthouse <https://web.dev/performance-scoring/>`_.
