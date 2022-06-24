Conformità al modello di sito scolastico
========================================

I criteri di conformità guidano alla corretta adozione del modello in termini di esperienza utente, sicurezza, performance e rispetto della normativa. 

Per gli istituti scolastici che partecipano a bandi di finanziamento per l’aggiornamento del sito scolastico, il DTD verifica a campione il rispetto dei requisiti di conformità tramite controlli automatizzati, parzialmente automatizzati e manuali.


``Esperienza utente``

**1. Il sito utilizza** `i font <risorse/template-html-pagine.html#i-font-del-modello>`_ **indicati nella documentazione del modello di sito scolastico**

  Casi di non conformità:
  
  - il sito usa prevalentemente o esclusivamente font non indicati nel modello.

  

**2. Il sito usa gli elementi di interfaccia della libreria Bootstrap Italia**

  Casi di non conformità:
  
  - la libreria Bootstrap Italia non è collegata nell'head del sito;
  - la libreria Bootstrap Italia utilizzata è una versione precedente alla 1.6.3.

  
**3. Nel caso in cui il sito utilizzi un CMS, viene usato** `il tema messo a disposizione <risorse/tema-wordpress.html>`_ **nella versione più recente disponibile alla data di inizio lavori**

  Casi di non conformità:
  
  - il sito utilizza un tema del modello scuole ma non utilizza la versione più recente disponibile alla data di inizio lavori.



**4. Il sito presenta tutte le voci di primo livello nell’ordine esatto descritto** `nell’architettura dell’informazione <risorse/architettura-dell-informazione.html>`_

  Casi di non conformità:
  
  - almeno una delle voci di menù di primo livello è assente o inesatta; 
  - le voci di menu di primo livello sono in ordine diverso da quanto descritto;
  - sono presenti più di 7 voci di menu di primo livello.

  

**5. Il sito presenta tutte le voci di secondo livello descritte** `nell’architettura dell’informazione <risorse/architettura-dell-informazione.html>`_

  Casi di non conformità:
  
  - è presente meno del 30% delle voci di menù di secondo livello;
  - non è presente un menù di secondo livello.

  

``Normativa``

**6. Il sito presenta l'informativa sul trattamento dei dati personali in linea con la** `normativa GDPR (Artt. 13 e 14, Reg. UE n. 679/2016) <https://www.garanteprivacy.it/regolamentoue>`_

  Casi di non conformità:
  
  - l’informativa sul trattamento dei dati personali non è valida secondo la normativa GDPR;
  - il link all’informativa sul trattamento dei dati personali non è presente nel footer.

  

**7. Il sito presenta una dichiarazione di accessibilità secondo le norme AGID**

  In linea con le `Linee guida AGID per la dichiarazione di accessibilità <https://www.agid.gov.it/it/design-servizi/accessibilita/dichiarazione-accessibilita>`_, le `Linee guida AGID sull’accessibilità degli strumenti informatici <https://docs.italia.it/AgID/documenti-in-consultazione/lg-accessibilita-docs/it/stabile/index.html>`_, la `Legge 9 gennaio 2004 n. 4 <https://www.normattiva.it/atto/caricaDettaglioAtto?atto.dataPubblicazioneGazzetta=2004-01-17&atto.codiceRedazionale=004G0015&atto.articolo.numero=0&atto.articolo.sottoArticolo=1&atto.articolo.sottoArticolo1=10&qId=cb6b9a05-f5c3-40ac-81b8-f89e73e5b4c7&tabID=0.029511124589268523&title=lbl.dettaglioAtto>`_, le `Web Content Accessibility Guidelines (WCAG 2.1) <https://www.w3.org/Translations/WCAG21-it/#background-on-wcag-2>`_ e la `Direttiva Reg. UE n. 2102/2016 <https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX%3A32016L2102>`_.

  Casi di non conformità:
  
  - la dichiarazione di accessibilità non è valida secondo le norme AGID;
  - il link alla dichiarazione di accessibilità non è presente nel footer del sito.

  

**8. Il sito presenta cookie tecnici in linea con le** `Linee guida cookie e altri strumenti di tracciamento - 10 giugno 2021 del Garante per la protezione dei dati personali <https://www.garanteprivacy.it/home/docweb/-/docweb-display/docweb/9677876>`_

  Casi di non conformità:
  
  - il sito presenta cookie che non rispettano le linee guida del Garante per la protezione dei dati personali.


``Sicurezza``

**9. Il sito ha un certificato https valido e attivo**

  In linea con le `Raccomandazioni AgID in merito allo standard Transport Layer Security (TLS) <https://cert-agid.gov.it/wp-content/uploads/2020/11/AgID-RACCSECTLS-01.pdf>`_
  
  Casi di non conformità:
  
  - il certificato https non è presente;
  - il certificato https è scaduto;
  - il certificato https è obsoleto.





Raccomandazioni
~~~~~~~~~~~~~~~

Per migliorare ulteriormente l'esperienza degli utenti e garantire l'uso di tecnologie aggiornate, restano valide altre indicazioni di legge e buone pratiche.

**1.  I contenuti del sito della scuola sono taggati con le voci della** `lista degli argomenti “Le parole della scuola” <risorse/architettura-dell-informazione.html#vocabolari-e-tassonomie>`_ **fornita nel documento di architettura dell'informazione**

  Da evitare:
  
  - più del 50% degli argomenti non appartengono alle voci del modello scuole.


**2. Le schede informative di servizio presentano tutti gli attributi obbligatori e nell’ordine segnalato nel** `documento di architettura dell’informazione <risorse/architettura-dell-informazione.html>`_

  Da evitare:
  
  - anche solo una scheda servizio non presenta più di una delle informazioni obbligatorie;
  - anche solo una scheda servizio presenta le informazioni obbligatorie in un ordine diverso.



**3. La scuola mette a disposizione il software nel** `catalogo del riuso <https://developers.italia.it/it/search?type=software_reuse&sort_by=release_date&page=0#fcf648cecc13b59b84915e7cace32504634d00e6>`_ **sotto licenza aperta**

  In linea con le Linee Guida `Riuso delle soluzioni e standard aperti <https://docs.italia.it/italia/piano-triennale-ict/codice-amministrazione-digitale-docs/it/v2021-07-30/_rst/capo_VI-articolo_69.html?highlight=riuso>`_ e `Acquisizione e riuso di software per le pubbliche amministrazioni <https://www.agid.gov.it/it/design-servizi/riuso-open-source/linee-guida-acquisizione-riuso-software-pa>`_

  Da evitare:
  
  - i repository con i file sorgente del sito del Comune non sono inseriti sul catalogo del riuso.

  
  
**4. Il sito della scuola pubblica dati, documenti e informazioni con licenza aperta (es. CC-BY 4.0)**

  In linea con `Linee guida AgID per l'acquisizione e il riuso software PA <https://www.agid.gov.it/it/design-servizi/riuso-open-source/linee-guida-acquisizione-riuso-software-pa>`_, l'`Art. 52 d.lgs. 82/2005 del CAD <https://docs.italia.it/italia/piano-triennale-ict/codice-amministrazione-digitale-docs/it/stabile/_rst/capo_V-sezione_I-articolo_52.html>`_,  l'`Art. 7, comma 1, D.Lgs. n. 33/2013 <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2013-03-14;33>`_ e il `D.lgs. n. 36/2006 <https://www.normattiva.it/uri-res/N2Ls?urn:nir:stato:decreto.legislativo:2006-01-24;36!vig=>`_
  
  Da evitare:
  
  - la scuola non segue le linee guida AGID sulla pubblicazione di dati, documenti o informazioni.

  

**5. Il sito usa tecnologie e infrastrutture cloud**

In linea con la `Strategia Cloud Italia <https://cloud.italia.it/strategia-cloud-pa/>`_

.. note::
L’uso di infrastrutture cloud consente un’erogazione più sicura, efficiente e scalabile del sito comunale. L’adozione di queste tecnologie può essere finanziata attraverso la categoria «servizi informativi e open data» all’interno della misura 1.2 Abilitazione e facilitazione migrazione al Cloud.


**6. Il sito della scuola presenta livelli di performance idonei**

  Da evitare:
  
  - il sito presenta livelli di prestazione (media pesata di 6 metriche standard) inferiori a 50 secondo quanto calcolato tramite le `librerie Lighthouse <https://web.dev/performance-scoring/>`_.
