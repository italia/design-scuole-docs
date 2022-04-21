Conformità al modello di sito scolastico
========================================

I criteri di conformità guidano alla corretta adozione del modello in termini di esperienza utente, sicurezza, performance e rispetto della normativa. 

Per gli istituti scolastici che partecipano a bandi di finanziamento per l’aggiornamento del sito scolastico, il DTD verifica a campione il rispetto dei requisiti di conformità tramite controlli automatizzati, parzialmente automatizzati e manuali.


``Esperienza utente``

**1. Il sito utilizza le font indicate nella documentazione del modello di sito scolastico**

  - Conforme: Il sito usa esclusivamente le font indicate nel modello
  - Parzialmente conforme: il sito usa le font indicate nel modello, insieme ad altre
  - Non conforme: Il sito usa soprattutto o esclusivamente font non indicate nel modello
  

**2. Il sito usa gli elementi di interfaccia della libreria Bootstrap Italia in una versione più recente di 1.6**

  - Conforme: La libreria Bootstrap Italia è collegata nell'head del sito e il valore della variabile js/css <BOOTSTRAP_ITALIA_VERSION> è uguale al valore più recente disponibile
  - Parzialmente conforme: La libreria Bootstrap Italia è collegata nell'head del sito ma il valore della variabile js/css <BOOTSTRAP_ITALIA_VERSION> è inferiore al valore <1.6.0>
  - Non conforme: La libreria Bootstrap Italia non è collegata nell'head del sito
  
**3. Nel caso in cui la scuola utilizzi Wordpress come content management system, viene usato il tema messo a disposizione nella versione più recente disponibile alla data di inizio lavori**

  - Conforme: il CMS è aggiornato all'ultima versione disponibile
  - Non conforme: il CMS non è aggiornato


**4. Il sito presenta tutte le voci di primo livello nell’ordine esatto descritto nell’architettura dell’informazione**

  - Conforme: Sono presenti tutte le voci di primo livello, nell’ordine corretto
  - Non conforme: Non tutte le voci sono presenti o lo sono in un ordine diverso
  

**5. Il sito presenta almeno il 30% delle voci di menu di secondo livello in base a quanto descritto dal modello di sito per le scuole**

  - Conforme: Sono presenti almeno il 30% delle voci di secondo livello
  - Non conforme: Sono presenti meno del 30% delle voci di secondo livello o il secondo livello è assente
  

``Normativa``

**6. Il sito presenta l'informativa sul trattamento dei dati personali** 

  In conformità con la `normativa GDPR (Artt. 13 e 14, Reg. UE n. 679/2016) <https://www.garanteprivacy.it/regolamentoue>`_

  - Conforme: L’informativa è presente nel footer
  - Non conforme: L’informativa non è presente nel footer
  

**7. Il sito presenta una dichiarazione di accessibilità**

  In conformità con le `Linee guida AgID per la dichiarazione di accessibilità <https://www.agid.gov.it/it/design-servizi/accessibilita/dichiarazione-accessibilita>`_, le `Linee guida AgID sull’accessibilità degli strumenti informatici <https://docs.italia.it/AgID/documenti-in-consultazione/lg-accessibilita-docs/it/stabile/index.html>`_, la `Legge 9 gennaio 2004 n. 4 <https://www.normattiva.it/atto/caricaDettaglioAtto?atto.dataPubblicazioneGazzetta=2004-01-17&atto.codiceRedazionale=004G0015&atto.articolo.numero=0&atto.articolo.sottoArticolo=1&atto.articolo.sottoArticolo1=10&qId=cb6b9a05-f5c3-40ac-81b8-f89e73e5b4c7&tabID=0.029511124589268523&title=lbl.dettaglioAtto>`_, le `Web Content Accessibility Guidelines (WCAG 2.1) <https://www.w3.org/Translations/WCAG21-it/#background-on-wcag-2>`_ e la `Direttiva Reg. UE n. 2102/2016 <https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX%3A32016L2102>`_.

  - Conforme: La dichiarazione di accessibilità è nel footer e la certificazione è valida secondo le norme AgID
  - Non conforme: La dichiarazione di accessibilità non è presente nel footer, o è presente ma non è valida secondo le norme AgID
  

**8. Il sito presenta cookie tecnici**

  In conformità con le `Linee guida cookie e altri strumenti di tracciamento - 10 giugno 2021 del Garante per la protezione dei dati personali <https://www.garanteprivacy.it/home/docweb/-/docweb-display/docweb/9677876>`_



``Sicurezza``

**9. Il sito ha un certificato https valido e attivo**

  In conformità con le `Raccomandazioni AgID in merito allo standard Transport Layer Security (TLS) <https://cert-agid.gov.it/wp-content/uploads/2020/11/AgID-RACCSECTLS-01.pdf>`_

  - Conforme: il certificato è presente e non è scaduto
  - Non conforme: il certificato non è presente,  o è presente ma è scaduto




Raccomandazioni
~~~~~~~~~~~~~~~

Per migliorare ulteriormente l'esperienza degli utenti e garantire l'uso di tecnologie aggiornate, restano valide altre indicazioni di legge e buone pratiche.

**1. Il sito utilizza i vocabolari forniti dal modello di sito per le scuole**


**2. Le schede informative di servizio presentano gli attributi segnalati nell’architettura dell’informazione, nell'ordine segnalato dal modello**

  - Conforme: Tutte le schede informative di servizio presentano gli attributi segnalati e nell'ordine corretto
  - Non conforme: Anche soltanto una scheda servizio non presenta gli attributi segnalati o li presenta in un ordine diverso


**3. La scuola mette a disposizione il software nel catalogo del riuso sotto licenza aperta**

  In conformità con le Linee Guida Riuso delle soluzioni e standard aperti e `Acquisizione e riuso di software per le pubbliche amministrazioni <https://www.agid.gov.it/it/design-servizi/riuso-open-source/linee-guida-acquisizione-riuso-software-pa>`_

  - Conforme: Il catalogo presenta i repository con i sorgenti del sito del Comune
  - Non conforme: Il catalogo non presenta i repository con i sorgenti del sito del Comune
  
  
**4. Il sito della scuola pubblica dati, documenti e informazioni con licenza aperta (es. CC-BY 4.0)**

  In conformità con `Linee guida AgID per l'acquisizione e il riuso software PA <https://www.agid.gov.it/it/design-servizi/riuso-open-source/linee-guida-acquisizione-riuso-software-pa>`_, l'`Art. 52 d.lgs. 82/2005 del CAD <https://docs.italia.it/italia/piano-triennale-ict/codice-amministrazione-digitale-docs/it/stabile/_rst/capo_V-sezione_I-articolo_52.html>`_,  l'`Art. 7, comma 1, D.Lgs. n. 33/2013 <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2013-03-14;33>`_ e il `D.lgs. n. 36/2006 <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2006-01-24;36!vig=>`_
  

**5. Il sito usa tecnologie e infrastrutture cloud**

In conformità con la `Stategia Cloud Italia <https://cloud.italia.it/strategia-cloud-pa/>`_

L'uso di infrastrutture cloud consente un'erogazione più sicura, efficiente e scalabile del sito comunale. L'adozione di queste tecnologie può essere finanziato attraverso categoria "servizi informativi e open data" all'interno della misura 1.2 Abilitazione e facilitazione migrazione al Cloud.


**6. Il sito della scuola presenta livelli di performance (media pesata di 6 metriche standard) pari o superiori a 50 secondo quanto calcolato tramite le librerie Lighthouse**
https://web.dev/performance-scoring/ 
